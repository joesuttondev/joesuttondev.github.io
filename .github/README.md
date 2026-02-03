# PlantBased.Blog Copilot Agents & Skills

This directory contains GitHub Copilot agents and skills designed to help create high-quality, SEO-optimized content for PlantBased.Blog, a plant-based recipe and lifestyle blog.

## Overview

The agents and skills in this directory work together to produce well-structured, professionally written, British English content with UK measurements and date formats. They ensure consistency, quality, and SEO optimization across all blog content.

## Directory Structure

```
.github/
├── agents/          # Specialized agents for different content creation roles
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

## Agents

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

### Basic Workflow

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

#### Creating a New Recipe
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

The agents are designed to work together in a collaborative workflow:

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

1. **Start with the right agent**: Use Recipe Creator for recipes, Copywriter for articles
2. **Follow the workflow**: Creation → Optimization → Review → Publication
3. **Reference the skills**: All agents should follow the standards in the skills directory
4. **Be specific**: Provide clear requirements (topic, keywords, target audience)
5. **Iterate**: Use Editor Agent feedback to improve content before publishing
6. **Maintain consistency**: Use the same tone, style, and standards across all content
7. **Think SEO early**: Involve SEO Specialist Agent early in content planning
8. **Be ethical**: Follow Affiliate Manager Agent guidelines for any commercial content

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

**Version**: 1.0  
**Last Updated**: 3rd February 2026  
**Maintained by**: PlantBased.Blog Team
