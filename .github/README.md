# PlantBased.Blog Copilot Agents & Skills

This directory contains GitHub Copilot agents and skills designed to help create high-quality, SEO-optimized content for PlantBased.Blog, a plant-based recipe and lifestyle blog.

## Overview

The agents and skills in this directory work together to produce well-structured, professionally written, British English content with UK measurements and date formats. They ensure consistency, quality, and SEO optimization across all blog content.

## Directory Structure

```
.github/
├── agents/          # Specialized agents for different content creation roles
│   ├── recipe-workflow.md      # 🆕 UNIFIED: Complete recipe workflow (recommended)
│   ├── recipe-creator.md       # Creates plant-based recipes
│   ├── copywriter.md           # Writes blog posts and articles
│   ├── seo-specialist.md       # Optimizes content for search engines
│   ├── editor.md               # Reviews and refines all content
│   ├── publisher.md            # Handles Jekyll publication workflow
│   ├── image-generation.md     # Guides image creation and description
│   └── affiliate-manager.md    # Manages ethical affiliate content
│
└── skills/          # Shared skills and standards used by all agents
    ├── british-english-standards.md  # UK English language standards
    ├── recipe-formatting.md          # Recipe structure guidelines
    └── seo-optimization.md           # SEO best practices
```

## 🆕 Unified Recipe Workflow Agent (Recommended)

### Recipe Workflow Agent (`recipe-workflow.agent.md`)
**Role**: Comprehensive recipe creation specialist (REPLACES multi-agent workflow)

**What's New**: This unified agent combines ALL six specialized agents into a single, streamlined workflow that produces complete, publication-ready recipe posts in one invocation.

**Capabilities**:
- ✅ **Complete End-to-End Workflow**: Handles everything from concept to publication
- ✅ **Recipe Development**: Creates original, practical plant-based recipes
- ✅ **Professional Copywriting**: Writes engaging blog-style content
- ✅ **SEO Optimization**: Integrates keywords and optimizes structure
- ✅ **Image Planning**: Creates detailed AI image generation prompts
- ✅ **Editorial Review**: Self-validates quality, grammar, and consistency
- ✅ **Publication Formatting**: Outputs complete Jekyll-ready markdown files

**Output**: Publication-ready blog post with:
- Complete Jekyll frontmatter with all metadata
- Engaging introduction and "Why You'll Love This" section
- Detailed ingredients and instructions (UK measurements)
- Pro tips, substitutions, and serving suggestions
- SEO-optimized titles and content
- Detailed image generation prompt
- Internal linking suggestions
- Proper file naming specification

**When to use**: 
- **Primary method** for creating new recipes
- When you want a complete post in one step
- For consistent, high-quality output every time

**Key Skills Used**: All three skills (`recipe-formatting`, `british-english-standards`, `seo-optimization`)

**How to use**:
```
@copilot using @recipe-workflow create a [type] recipe for [occasion/season]
```

**Example**:
```
@copilot using @recipe-workflow create a quick weeknight dinner recipe
@copilot using @recipe-workflow create a festive Christmas dessert
@copilot using @recipe-workflow create a summer BBQ recipe for beginners
```

---

## Traditional Specialized Agents

**Note**: The agents below can still be used individually, but the **Recipe Workflow Agent** is now recommended for recipe creation as it produces complete, publication-ready posts in a single step.

### 1. Recipe Creator Agent (`recipe-creator.md`)
**Role**: Expert recipe developer for plant-based cuisine

**Capabilities**:
- Develops original vegan recipes across all meal types
- Ensures recipes are practical and achievable
- Writes clear, step-by-step instructions
- Provides timing, measurements, and visual cues
- Suggests variations and substitutions
- Creates recipes for various skill levels and dietary needs

**When to use**: Creating new recipes, adapting existing recipes, or improving recipe content

**Key Skills Used**: `recipe-formatting.md`, `british-english-standards.md`

---

### 2. Copywriter Agent (`copywriter.md`)
**Role**: Professional lifestyle and food content writer

**Capabilities**:
- Writes engaging blog posts and articles
- Creates lifestyle guides and how-to content
- Develops informational and inspirational pieces
- Maintains consistent brand voice
- Writes in warm, approachable, yet professional tone
- Structures content for readability and engagement

**When to use**: Creating blog posts, guides, listicles, or any non-recipe content

**Key Skills Used**: `british-english-standards.md`, `seo-optimization.md`

---

### 3. SEO Specialist Agent (`seo-specialist.md`)
**Role**: Search engine optimization expert

**Capabilities**:
- Optimizes titles, headings, and meta descriptions
- Conducts keyword research and integration
- Reviews content structure and readability
- Manages internal and external linking strategies
- Optimizes images (filenames, alt text)
- Ensures Schema markup compatibility
- Focuses on UK search market

**When to use**: Optimizing any content before publication, auditing existing content, or planning new content

**Key Skills Used**: `seo-optimization.md`

---

### 4. Editor Agent (`editor.md`)
**Role**: Professional content editor and quality assurance

**Capabilities**:
- Reviews and refines all content
- Ensures British English compliance
- Checks grammar, spelling, and punctuation
- Verifies factual accuracy
- Maintains brand voice consistency
- Reviews recipe logic and completeness
- Performs final quality checks

**When to use**: Before publishing any content, for content audits, or when quality issues are suspected

**Key Skills Used**: All skills (`british-english-standards.md`, `recipe-formatting.md`, `seo-optimization.md`)

---

### 5. Publisher Agent (`publisher.md`)
**Role**: Publication coordinator for Jekyll site

**Capabilities**:
- Manages Jekyll file structure and naming
- Creates proper frontmatter metadata
- Handles image placement and organization
- Executes publication workflow
- Performs final validation checks
- Manages categories and tags

**When to use**: When ready to publish content, organizing files, or troubleshooting publication issues

**Key Skills Used**: All skills, plus Jekyll-specific knowledge

---

### 6. Image Generation Agent (`image-generation.md`)
**Role**: Visual content specialist

**Capabilities**:
- Plans image requirements for content
- Creates detailed prompts for AI image generation
- Guides food photography concepts
- Defines image specifications and styles
- Ensures brand visual consistency
- Optimizes images for web and SEO

**When to use**: Planning recipe photography, creating visual content, generating AI images, or selecting stock photos

---

### 7. Affiliate Manager Agent (`affiliate-manager.md`)
**Role**: Ethical affiliate marketing specialist

**Capabilities**:
- Integrates affiliate content naturally
- Ensures ASA/FTC compliance
- Writes proper disclosures
- Recommends products ethically
- Manages affiliate partnerships
- Maintains reader trust

**When to use**: Adding product recommendations, creating gift guides, writing product reviews, or managing affiliate links

---

## Skills

### 1. British English Standards (`british-english-standards.md`)
**Purpose**: Ensures consistent UK English usage across all content

**Includes**:
- British spelling rules (colour, centre, realise)
- UK measurements (Celsius, grams, millilitres)
- UK date formats (DD/MM/YYYY)
- British terminology (courgette, aubergine, coriander)
- UK-specific language conventions

**Used by**: All agents

---

### 2. Recipe Formatting (`recipe-formatting.md`)
**Purpose**: Standardizes recipe structure and presentation

**Includes**:
- Jekyll frontmatter template for recipes
- Ingredient list formatting
- Method step structure
- Timing and temperature guidelines
- Chef's notes and tips sections
- Nutritional information format

**Used by**: Recipe Creator, Editor, Publisher agents

---

### 3. SEO Optimization (`seo-optimization.md`)
**Purpose**: Ensures all content is optimized for search engines

**Includes**:
- Title and meta description optimization
- Keyword research and integration strategies
- Content structure requirements
- Internal and external linking guidelines
- Image SEO best practices
- Schema markup considerations
- UK-specific SEO factors

**Used by**: SEO Specialist, Copywriter, Editor agents

---

## How to Use These Agents

### 🆕 Recommended: Unified Recipe Workflow

For recipe creation, use the **Recipe Workflow Agent** for a complete, one-step process:

```
1. Recipe Workflow Agent: Create complete recipe post
   ↓
2. Ready to publish! (Copy to _posts/ directory)
```

**Benefits**:
- ✅ Single agent invocation instead of 5-6
- ✅ No manual handoffs between agents
- ✅ Consistent quality and formatting
- ✅ Complete publication-ready output
- ✅ Faster workflow (minutes vs. hours)

### Traditional Multi-Agent Workflow

For other content types or if you prefer granular control:

1. **Content Creation**
   - Use **Recipe Creator Agent** for recipes
   - Use **Copywriter Agent** for blog posts/articles
   - Consult **Image Generation Agent** for visual planning

2. **Optimization**
   - **SEO Specialist Agent** reviews and optimizes content
   - Ensures keywords and structure are optimal

3. **Review**
   - **Editor Agent** performs comprehensive review
   - Checks quality, accuracy, and compliance

4. **Affiliate Integration** (if applicable)
   - **Affiliate Manager Agent** adds ethical product recommendations

5. **Publication**
   - **Publisher Agent** handles final formatting and publishing

### Example Use Cases

#### Creating a New Recipe (🆕 Recommended Method)
```
1. Recipe Workflow Agent: "Create a cosy autumn soup recipe"
   → Produces complete publication-ready post with:
   - Recipe with UK measurements
   - Engaging blog-style content
   - SEO optimization
   - Image generation prompt
   - All Jekyll frontmatter
   - Ready to copy into _posts/YYYY-MM-DD-recipe-name.markdown
```

#### Creating a New Recipe (Traditional Multi-Agent Method)
```
1. Recipe Creator Agent: Develop "Easy Vegan Shepherd's Pie"
2. Image Generation Agent: Plan hero and process images
3. SEO Specialist Agent: Optimize title and content
4. Editor Agent: Review and refine
5. Publisher Agent: Format and publish
```

#### Writing a Lifestyle Article
```
1. Copywriter Agent: Write "10 Tips for Plant-Based Beginners"
2. SEO Specialist Agent: Optimize for target keywords
3. Affiliate Manager Agent: Add relevant product links (if appropriate)
4. Editor Agent: Final review
5. Publisher Agent: Prepare and publish
```

#### Creating a Product Roundup
```
1. Copywriter Agent: Structure "Best Vegan Cookbooks 2026"
2. Affiliate Manager Agent: Add affiliate links with disclosures
3. SEO Specialist Agent: Optimize for search
4. Image Generation Agent: Plan product showcase images
5. Editor Agent: Ensure compliance and quality
6. Publisher Agent: Format and publish
```

## Key Standards

### Language
- ✅ British English spelling and grammar
- ✅ UK measurements (°C, g, ml, cm)
- ✅ UK date format (DD/MM/YYYY)
- ✅ British ingredient names (courgette, aubergine, coriander)

### Content Quality
- ✅ Engaging and informative
- ✅ Well-structured with clear headings
- ✅ Short paragraphs (2-4 sentences)
- ✅ Accessible to target audience
- ✅ SEO-optimized
- ✅ Factually accurate

### Brand Voice
- ✅ Warm and welcoming
- ✅ Inclusive (all levels welcome)
- ✅ Professional yet approachable
- ✅ Encouraging and positive
- ✅ Never preachy or judgmental

### Jekyll Requirements
- ✅ Proper frontmatter metadata
- ✅ Correct file naming: `YYYY-MM-DD-post-slug.markdown`
- ✅ Appropriate categories and tags
- ✅ Optimized images in correct directories
- ✅ Working internal and external links

## Agent Collaboration

### 🆕 Unified Workflow (Recommended for Recipes)
```
┌────────────────────────────────────────────┐
│        Recipe Workflow Agent               │
│                                            │
│  Combines:                                 │
│  • Recipe Development                      │
│  • Copywriting                             │
│  • SEO Optimization                        │
│  • Image Planning                          │
│  • Editorial Review                        │
│  • Publication Formatting                  │
└────────────────────────────────────────────┘
                   │
                   ▼
           Publication-Ready Post
```

### Traditional Multi-Agent Workflow
The specialized agents are designed to work together in a collaborative workflow:

```
┌─────────────────┐     ┌──────────────┐     ┌─────────────┐
│ Recipe Creator  │────▶│ SEO Specialist│────▶│   Editor    │
│   Copywriter    │     └──────────────┘     └─────────────┘
└─────────────────┘              │                    │
        │                        │                    │
        ▼                        ▼                    ▼
┌─────────────────┐     ┌──────────────┐     ┌─────────────┐
│ Image Generator │     │   Affiliate  │────▶│  Publisher  │
└─────────────────┘     │   Manager    │     └─────────────┘
                        └──────────────┘
```

All agents reference the shared **Skills** for consistency.

## Tips for Best Results

1. **🆕 Use Recipe Workflow Agent for recipes**: One-step process for complete, publication-ready recipe posts
2. **Start with the right agent**: Use Recipe Workflow for recipes, Copywriter for articles
3. **Be specific with Recipe Workflow**: Provide details like meal type, cuisine, difficulty, or occasion
4. **Traditional workflow for articles**: Creation → Optimization → Review → Publication
5. **Reference the skills**: All agents follow the standards in the skills directory
6. **Be specific**: Provide clear requirements (topic, keywords, target audience)
7. **Iterate if needed**: Use Editor Agent for additional refinement if required
8. **Maintain consistency**: Use the same tone, style, and standards across all content
9. **Think SEO early**: Recipe Workflow includes SEO, but for articles involve SEO Specialist early
10. **Be ethical**: Follow Affiliate Manager Agent guidelines for any commercial content

## Updating Agents and Skills

When updating agents or skills:
- Maintain backward compatibility where possible
- Document significant changes
- Update all related agents that reference changed skills
- Test workflow end-to-end after major updates

## Questions or Issues?

If you encounter issues or have suggestions for improving these agents:
1. Review the relevant agent and skill documentation
2. Check if other agents need to be consulted
3. Ensure you're following the complete workflow
4. Consider if the issue requires a skill update (affects all agents) or agent-specific update

---

**Version**: 2.0 (Added Unified Recipe Workflow Agent)  
**Last Updated**: 3rd February 2026  
**Maintained by**: PlantBased.Blog Team
