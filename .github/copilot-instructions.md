# PlantBased.Blog - GitHub Copilot Instructions

## Project Overview

PlantBased.Blog is a Jekyll-powered static site dedicated to plant-based living, vegan recipes, and sustainable lifestyle choices. The blog provides high-quality, SEO-optimized content including recipes, how-to guides, and lifestyle articles, all written in British English with UK measurements and standards.

**Target Audience**: People interested in plant-based living, from beginners to experienced vegans, seeking practical recipes and lifestyle guidance.

**Key Features**:
- Plant-based recipe collection with detailed instructions
- Lifestyle and how-to articles
- SEO-optimized content for UK market
- British English language standards
- Automated content generation workflows

## Technology Stack

- **Static Site Generator**: Jekyll 4.4.1
- **Theme**: Minima 2.5
- **Language**: Ruby 3.x
- **Markup**: Markdown
- **Dependency Management**: Bundler
- **Version Control**: Git/GitHub
- **Plugins**: 
  - jekyll-feed (RSS feed generation)

## Content Standards

### Language and Style

- **ALWAYS use British English**: colour, centre, realise, flavour, etc.
- **UK Measurements**: 
  - Temperature: Celsius (°C)
  - Weight: grams (g), kilograms (kg)
  - Volume: millilitres (ml), litres (l)
  - Length: centimetres (cm), metres (m)
- **UK Date Format**: DD/MM/YYYY or "3rd February 2026"
- **British Ingredient Names**: 
  - courgette (not zucchini)
  - aubergine (not eggplant)
  - coriander (not cilantro)
  - rocket (not arugula)
  - spring onion (not scallion)

### Brand Voice

- Warm and welcoming
- Inclusive - all experience levels welcome
- Professional yet approachable
- Encouraging and positive
- Never preachy or judgmental about dietary choices

### Writing Style

- Short paragraphs (2-4 sentences)
- Clear headings and subheadings
- Use bullet points for lists
- Engaging and informative
- SEO-optimized with natural keyword integration

## File Structure and Naming Conventions

### Blog Posts

- **Location**: `_posts/` directory
- **Naming**: `YYYY-MM-DD-post-slug.markdown`
- **Format**: Markdown with YAML frontmatter
- **Example**: `2026-02-03-easy-vegan-shepherds-pie.markdown`

### Content Organization

```
├── _posts/               # Blog posts and recipes
├── _config.yml          # Jekyll configuration
├── about.markdown       # About page
├── index.markdown       # Homepage
├── Gemfile              # Ruby dependencies
└── .github/
    ├── agents/          # Specialized content creation agents
    ├── skills/          # Shared skills and standards
    └── workflows/       # GitHub Actions workflows
```

## Jekyll Frontmatter Requirements

All posts must include proper YAML frontmatter:

```yaml
---
layout: post
title: "Post Title in Title Case"
date: YYYY-MM-DD HH:MM:SS +0000
categories: [category1, category2]
tags: [tag1, tag2, tag3]
excerpt: "Brief summary for SEO and previews"
---
```

### Recipe-Specific Frontmatter

```yaml
---
layout: post
title: "Recipe Name"
date: YYYY-MM-DD HH:MM:SS +0000
categories: [recipes]
tags: [meal-type, cuisine, dietary-info]
excerpt: "Brief recipe description"
prep_time: "15 minutes"
cook_time: "30 minutes"
servings: 4
difficulty: easy|medium|advanced
---
```

## Specialized Agents

This repository uses specialized GitHub Copilot agents for content creation. Always prefer using these agents for their respective tasks:

### Available Agents (in `.github/agents/`)

1. **recipe-creator.agent.md** - Creates plant-based recipes with proper formatting
2. **copywriter.agent.md** - Writes blog posts and articles
3. **seo-specialist.agent.md** - Optimizes content for search engines (UK market)
4. **editor.agent.md** - Reviews and refines all content
5. **publisher.agent.md** - Handles Jekyll publication workflow
6. **image-generation.agent.md** - Plans and describes visual content
7. **affiliate-manager.agent.md** - Manages ethical affiliate content with proper disclosures

### Content Creation Workflow

1. **Create** - Use Recipe Creator or Copywriter agent
2. **Optimize** - Use SEO Specialist agent
3. **Review** - Use Editor agent for quality assurance
4. **Affiliate** (if applicable) - Use Affiliate Manager for product recommendations
5. **Publish** - Use Publisher agent for final formatting and publication

## Shared Skills (in `.github/skills/`)

All agents reference these skills for consistency:

- **british-english-standards.md** - Language conventions and UK standards
- **recipe-formatting.md** - Recipe structure guidelines
- **seo-optimization.md** - SEO best practices for UK market
- **ui-styling-standards.md** - UI design, colour palette, and visual styling guidelines

## Development Commands

### Local Development

```bash
# Install dependencies
bundle install

# Build the site
bundle exec jekyll build

# Serve locally (http://localhost:4000)
bundle exec jekyll serve

# Serve with drafts and future posts
bundle exec jekyll serve --drafts --future
```

### Testing Changes

- Always test locally before committing
- Check that posts appear correctly at `http://localhost:4000`
- Verify frontmatter is correctly formatted
- Ensure British English spelling is used throughout

## SEO Best Practices

- **Title**: 50-60 characters, include primary keyword
- **Meta Description**: 150-160 characters, compelling summary
- **Headings**: Use H2-H4 hierarchy, include keywords naturally
- **Internal Links**: Link to related posts and pages
- **Alt Text**: Describe images clearly for accessibility and SEO
- **URL Slugs**: Short, descriptive, keyword-rich

## Code Formatting Preferences

### Markdown

- Use ATX-style headers (`#` prefix)
- Use `-` for unordered lists
- Use `1.` for ordered lists (let Markdown auto-number)
- Use fenced code blocks with language specification

### YAML

- Use 2-space indentation
- Quote strings containing special characters
- Use arrays for lists: `[item1, item2]`

### Ruby/Jekyll

- Follow standard Ruby style guide
- Use 2-space indentation
- Keep Gemfile organized and commented

## UI and Styling Guidelines

### Design System

PlantBased.Blog uses a **nature-inspired design system** with modern, clean aesthetics:

- **Colour Palette**: Greens, earth tones, and warm accents (sage, cream, terracotta)
- **Typography**: System fonts for performance and readability
- **Layout**: Clean, spacious, optimised for recipe readability
- **Responsive**: Mobile-first design that works on all devices

### Key Styling Principles

1. **Use Semantic Markdown**: Let CSS handle styling - don't add inline styles
2. **Heading Hierarchy**: Always use H2 → H3 → H4 in proper order
3. **Lists**: Use unordered lists for ingredients, ordered lists for instructions
4. **Blockquotes**: Use for tips, notes, and serving suggestions
5. **Images**: Always include descriptive alt text

### Recipe Formatting for Visual Appeal

When creating recipes, follow this structure for optimal styling:

```markdown
## Ingredients

### For the Base
- Ingredient 1
- Ingredient 2

## Instructions

1. First step with clear description
2. Second step with clear description

> **Top Tip**: Use blockquotes for helpful tips!
```

This produces:
- Ingredients in cream-coloured boxes with green border
- Instructions with numbered circular badges
- Tips in terracotta-bordered callout boxes

### Content Creators - Style Checklist

- ✅ Use proper heading hierarchy (H2 for sections, H3 for subsections)
- ✅ Use unordered lists (`-`) for ingredients
- ✅ Use ordered lists (`1.`) for instructions
- ✅ Use blockquotes (`>`) for tips and notes
- ✅ Include alt text for all images
- ❌ Don't use inline styles or custom HTML
- ❌ Don't use colours outside the defined palette
- ❌ Don't use custom fonts

For complete styling guidelines, see `.github/skills/ui-styling-standards/SKILL.md`

## What NOT to Do

- ❌ Don't use American English spelling
- ❌ Don't use US measurements (cups, Fahrenheit)
- ❌ Don't use American ingredient names
- ❌ Don't be preachy or judgmental about dietary choices
- ❌ Don't create posts without proper frontmatter
- ❌ Don't use incorrect file naming (must be YYYY-MM-DD-slug.markdown)
- ❌ Don't ignore SEO optimization
- ❌ Don't add affiliate content without proper disclosure
- ❌ Don't add inline styles or custom CSS to posts
- ❌ Don't override the defined colour palette
- ❌ Don't break responsive design with fixed widths

## Common Tasks

### Creating a New Recipe

1. Use **Recipe Creator** agent with topic/requirements
2. Save to `_posts/YYYY-MM-DD-recipe-name.markdown`
3. Include proper frontmatter with timing and servings
4. Use British English and UK measurements
5. Run through **SEO Specialist** agent
6. Review with **Editor** agent
7. Test locally with `bundle exec jekyll serve`

### Writing a Blog Post

1. Use **Copywriter** agent with topic outline
2. Save to `_posts/YYYY-MM-DD-post-slug.markdown`
3. Include engaging introduction and clear structure
4. Optimize with **SEO Specialist** agent
5. Review with **Editor** agent
6. Test locally before publishing

### Adding Affiliate Content

1. Work with **Affiliate Manager** agent
2. Always include clear disclosure at top of post
3. Ensure recommendations are ethical and relevant
4. Follow ASA/FTC compliance guidelines
5. Maintain reader trust

## Additional Notes

- This is a GitHub Pages site deployed from the main branch
- All content is public and indexed by search engines
- Focus on high-quality, helpful content for the plant-based community
- Maintain consistency in voice, style, and standards across all content
- Regular content updates help with SEO and audience engagement

## Questions or Issues?

- Check `.github/README.md` for detailed agent documentation
- Review `.github/skills/` for specific standards
- Test locally before pushing changes
- Ensure all content meets British English and SEO standards
