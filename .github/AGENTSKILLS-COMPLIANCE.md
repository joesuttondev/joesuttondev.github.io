# agentskills.io Specification Compliance

This repository follows the [agentskills.io specification](https://agentskills.io/specification) for organizing AI agent skills.

## Structure

### Skills Directory
```
.github/skills/
├── recipe-formatting/
│   └── SKILL.md
├── british-english-standards/
│   └── SKILL.md
└── seo-optimization/
    └── SKILL.md
```

Each skill:
- Is a directory (folder) whose name serves as the skill's unique identifier
- Contains a `SKILL.md` file with metadata and instructions
- Uses lowercase letters, numbers, and hyphens only in the folder name
- Has a folder name that exactly matches the `name` field in the frontmatter

### SKILL.md Format

Each `SKILL.md` file contains:

#### Required YAML Frontmatter
```yaml
---
name: skill-name
description: Clear description of the skill's purpose and when to use it
---
```

- **name**: Must match the folder name exactly (lowercase, hyphenated)
- **description**: Explains what the skill does and when agents should use it

#### Markdown Body
Below the frontmatter, the file contains:
- Detailed instructions for the skill
- Examples and best practices
- Guidelines and standards
- Any relevant documentation

## Agent References

Agent files (in `.github/agents/`) reference skills using the folder name:

```yaml
---
name: Recipe Creator
description: Expert recipe developer specializing in plant-based and vegan cuisine
version: 1.0.0
skills:
  - recipe-formatting
  - british-english-standards
---
```

## Validation

To validate compliance:

```bash
# Check that folder names match frontmatter names
python3 << 'EOF'
import os
import yaml

skills_dir = '.github/skills'
for skill_folder in os.listdir(skills_dir):
    skill_path = os.path.join(skills_dir, skill_folder)
    if os.path.isdir(skill_path):
        skill_md = os.path.join(skill_path, 'SKILL.md')
        if os.path.exists(skill_md):
            with open(skill_md, 'r') as f:
                content = f.read()
                if content.startswith('---'):
                    parts = content.split('---', 2)
                    frontmatter = yaml.safe_load(parts[1])
                    name = frontmatter.get('name')
                    matches = skill_folder == name
                    print(f'{skill_folder}: {"✓" if matches else "✗"} (name: {name})')
EOF
```

## Benefits of This Structure

1. **Vendor Neutral**: Works with multiple AI agent platforms (GitHub Copilot, Claude, etc.)
2. **Progressive Disclosure**: Agents can scan metadata without loading full instructions
3. **Organized**: Clear separation between different skills
4. **Extensible**: Easy to add new skills by creating new directories
5. **Discoverable**: Agents can automatically find and use available skills

## References

- [agentskills.io Specification](https://agentskills.io/specification)
- [Agent Skills Standard Documentation](https://deepwiki.com/karim-bhalwani/agent-skills-collection/5.1-understanding-the-agent-skills-standard)
- [GitHub: agentskills/agentskills](https://github.com/agentskills/agentskills)

## Migration Notes

Previously, skills were single `.md` files with `version` and `type` fields in the frontmatter. These have been:
- Converted to directories with `SKILL.md` files inside
- Simplified to use only `name` and `description` in frontmatter
- Updated to use lowercase hyphenated names matching folder structure

All agent references remain compatible with the new structure.
