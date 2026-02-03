# Recipe Workflow Agent - Quick Start Guide

## Overview

The **Recipe Workflow Agent** is a comprehensive, unified agent that replaces the previous 6-agent workflow for recipe creation. It produces **complete, publication-ready** Jekyll blog posts in a single invocation.

## What It Replaces

### Before (Multi-Agent Workflow) ❌
```
1. Recipe Creator Agent → creates recipe
2. Image Generation Agent → plans images  
3. Copywriter Agent → writes blog content
4. SEO Specialist Agent → optimizes for search
5. Editor Agent → reviews and refines
6. Publisher Agent → formats for Jekyll
```
**Time**: Multiple hours with manual handoffs

### After (Unified Workflow) ✅
```
1. Recipe Workflow Agent → creates complete post
```
**Time**: Single invocation, minutes not hours

## Benefits

✅ **One-Step Process**: Single agent handles everything  
✅ **Consistent Quality**: Built-in editorial review  
✅ **Publication-Ready**: Copy-paste directly to _posts/  
✅ **Complete Output**: All sections included  
✅ **SEO-Optimized**: Keywords integrated naturally  
✅ **UK Standards**: British English and measurements  
✅ **Image Planning**: Detailed AI generation prompts  
✅ **No Editing Needed**: Ready to publish immediately  

## How to Use

### Basic Usage

```
@copilot using @recipe-workflow create [type] recipe
```

### Example Invocations

**Simple Request:**
```
@copilot using @recipe-workflow create a quick weeknight dinner recipe
```

**Specific Request:**
```
@copilot using @recipe-workflow create a gluten-free vegan chocolate cake for special occasions
```

**Seasonal Request:**
```
@copilot using @recipe-workflow create an autumn soup recipe using seasonal vegetables
```

**Cuisine-Specific:**
```
@copilot using @recipe-workflow create a Mediterranean-inspired lunch recipe
```

**Dietary-Specific:**
```
@copilot using @recipe-workflow create a high-protein breakfast recipe that's nut-free
```

## What You Get

The agent outputs a complete markdown file with:

### 1. Filename Specification
```
YYYY-MM-DD-recipe-name-in-kebab-case.markdown
```

### 2. Complete Jekyll Frontmatter
```yaml
---
layout: post
title: "SEO-Optimized Recipe Title"
date: 2026-02-03 09:00:00 +0000
categories: recipes dinner
tags: vegan quick easy healthy protein
excerpt: "Compelling 150-character description for social media"
prep_time: "15 minutes"
cook_time: "30 minutes"
total_time: "45 minutes"
servings: 4
difficulty: Easy
image_prompt: "Detailed AI image generation prompt..."
---
```

### 3. Blog-Style Content
- Engaging 2-3 paragraph introduction
- "Why You'll Love This Recipe" section
- Nutritional highlights
- Complete ingredient list (UK measurements)
- Step-by-step instructions with timing
- Serving suggestions
- Storage tips
- Substitutions & variations
- Pro tips
- Closing paragraph

### 4. Additional Elements
- Internal linking suggestions
- SEO-optimized structure
- Professional image generation prompt
- British English throughout
- UK measurements (g, ml, °C, Gas Mark)

## Recipe Types

The agent can create recipes across:

### Meal Types
- Breakfast (porridge, smoothies, tofu scrambles)
- Lunch (salads, sandwiches, soups)
- Dinner (curries, pastas, stews, roasts)
- Snacks (energy balls, dips, crackers)
- Desserts (cakes, cookies, puddings)
- Beverages (smoothies, hot drinks)

### Cuisines
- British (pies, roasts, puddings)
- Mediterranean (pasta, risotto, mezze)
- Asian (curries, stir-fries, noodles)
- Middle Eastern (falafel, tagines)
- Mexican (tacos, burritos, salsas)
- Italian (pasta, pizza, antipasti)

### Difficulty Levels
- **Easy**: 30 minutes or less, basic ingredients
- **Medium**: 45-60 minutes, some technique
- **Advanced**: 60+ minutes, impressive results

### Dietary Considerations
- Gluten-free
- Nut-free
- Soy-free
- Oil-free
- High-protein
- Budget-friendly
- Meal-prep friendly

## Usage Tips

### Be Specific
The more detail you provide, the better:
- Meal type (breakfast, dinner, snack)
- Cuisine style (British, Asian, Mediterranean)
- Dietary needs (gluten-free, nut-free)
- Occasion (weeknight, party, holiday)
- Skill level (easy, medium, advanced)
- Season (spring, summer, autumn, winter)

### Example Detailed Request
```
@copilot using @recipe-workflow create an easy weeknight dinner recipe 
that's British-inspired, gluten-free, and perfect for autumn with seasonal 
vegetables
```

### What to Expect

**Agent Will Provide:**
- Complete file content ready to copy
- Filename in correct format
- All required sections
- British English spelling
- UK measurements throughout
- SEO-optimized content
- Professional image prompt

**You Need To:**
1. Copy the content to a new file
2. Save as `_posts/YYYY-MM-DD-recipe-name.markdown`
3. Generate/add the hero image (optional)
4. Commit and push to publish

## Quality Standards

Every recipe output includes:

### Content Quality
✅ Engaging, well-written content  
✅ Clear, logical recipe structure  
✅ Accurate measurements and timing  
✅ Helpful tips and variations  
✅ Professional tone and style  

### Technical Standards
✅ British English spelling (colour, flavour)  
✅ UK measurements (g, ml, °C, Gas Mark)  
✅ British terminology (courgette, aubergine)  
✅ Proper Jekyll frontmatter  
✅ SEO-optimized throughout  

### Recipe Standards
✅ 100% plant-based ingredients  
✅ Achievable for home cooks  
✅ UK-available ingredients  
✅ Realistic timing and yields  
✅ Complete instructions  

## Troubleshooting

### Issue: Output is too generic
**Solution**: Provide more specific details in your request
```
Instead of: "create a pasta recipe"
Try: "create an easy 20-minute creamy pasta dinner for weeknights"
```

### Issue: Wrong difficulty level
**Solution**: Specify the target audience or skill level
```
"create a beginner-friendly recipe"
"create an impressive recipe for experienced cooks"
```

### Issue: Need different cuisine
**Solution**: Specify the cuisine type and key ingredients
```
"create an Asian-inspired stir-fry"
"create a British comfort food classic"
```

## Example Output Structure

```markdown
FILENAME: 2026-02-03-easy-vegan-shepherds-pie.markdown

---
layout: post
title: "Easy Vegan Shepherd's Pie | British Comfort Food Classic"
date: 2026-02-03 09:00:00 +0000
categories: recipes dinner
tags: vegan british comfort-food easy family-friendly
excerpt: "A hearty, comforting vegan shepherd's pie with lentils and vegetables..."
prep_time: "20 minutes"
cook_time: "40 minutes"
total_time: "60 minutes"
servings: 6
difficulty: Easy
image_prompt: "Professional food photography of vegan shepherd's pie..."
---

[Engaging introduction about the dish, 2-3 paragraphs]

## Why You'll Love This Recipe

- [4-6 compelling bullet points]

## Nutritional Highlights

- [3-5 nutritional benefits]

## Prep Time & Servings

- **Prep Time**: 20 minutes
- **Cook Time**: 40 minutes
- [etc...]

## Ingredients

### For the Filling:
- 250g green lentils
- [Complete list with UK measurements]

### For the Topping:
- 1kg potatoes
- [Complete list]

## Instructions

### Step 1: Prepare the Filling
1. [Clear, detailed instructions]
2. [With timing and visual cues]

[All remaining sections included...]

## Internal Linking Suggestions

Consider linking to:
- [Related Recipe](/recipes/recipe-slug)
```

## Advanced Usage

### Seasonal Recipes
Request recipes using seasonal UK produce:
```
@copilot using @recipe-workflow create a spring recipe featuring 
asparagus and peas
```

### Holiday Recipes
Create festive dishes for UK holidays:
```
@copilot using @recipe-workflow create a Christmas main course 
alternative to turkey
```

### Batch Cooking
Request meal-prep friendly recipes:
```
@copilot using @recipe-workflow create a batch-cooking friendly 
curry recipe
```

### Special Dietary Needs
Specify multiple dietary requirements:
```
@copilot using @recipe-workflow create a gluten-free, nut-free 
dessert that's also refined-sugar-free
```

## FAQs

**Q: Can I edit the output?**  
A: The output is publication-ready, but you can edit if needed. The agent includes all required sections.

**Q: Does it include images?**  
A: It includes a detailed image generation prompt. You'll need to generate the actual image separately.

**Q: Can I request specific ingredients?**  
A: Yes! Specify ingredients in your request: "create a recipe using chickpeas and butternut squash"

**Q: Will it always use British English?**  
A: Yes, the agent is programmed to use British English, UK measurements, and British ingredient names.

**Q: How detailed should my request be?**  
A: The more detail the better, but even simple requests like "create a quick dinner recipe" work well.

**Q: Can I use this for non-recipe content?**  
A: No, this agent is specifically for recipes. Use the Copywriter Agent for articles and guides.

## Next Steps

1. **Try it out**: Start with a simple request
2. **Review output**: Check the generated content
3. **Copy to file**: Save in `_posts/` directory
4. **Add image**: Generate or source the hero image (optional)
5. **Publish**: Commit and push to publish

## Support

For issues or questions:
- Review the main agent file: `.github/agents/recipe-workflow.agent.md`
- Check the skills directory: `.github/skills/`
- Refer to the main README: `.github/README.md`

---

**Quick Reference Card**

```
USAGE: @copilot using @recipe-workflow create [details]

OUTPUT: Complete publication-ready Jekyll blog post

INCLUDES:
✓ Jekyll frontmatter
✓ Blog content
✓ Recipe (UK measurements)
✓ SEO optimization
✓ Image prompt
✓ Tips & variations

READY TO: Copy to _posts/ and publish
```

---

**Version**: 1.0  
**Created**: 3rd February 2026  
**Agent Version**: recipe-workflow.agent.md v1.0.0
