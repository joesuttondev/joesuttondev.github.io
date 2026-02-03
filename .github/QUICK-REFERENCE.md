# Quick Reference: Copilot Agents & Skills

## Which Agent Should I Use?

| Task | Use This Agent | Notes |
|------|----------------|-------|
| Create a new recipe | **Recipe Creator** | Handles ingredients, method, timing, tips |
| Write a blog post/article | **Copywriter** | Lifestyle content, guides, how-tos, listicles |
| Optimize content for SEO | **SEO Specialist** | Keywords, titles, structure, links |
| Review before publishing | **Editor** | Grammar, accuracy, consistency, quality |
| Add product recommendations | **Affiliate Manager** | Ethical, compliant affiliate integration |
| Plan recipe photos | **Image Generation** | Photography concepts, AI prompts, styling |
| Prepare for publication | **Publisher** | Jekyll formatting, frontmatter, file naming |

## Quick Workflows

### 📝 New Recipe
1. **Recipe Creator** → Create recipe
2. **SEO Specialist** → Optimize title/content
3. **Image Generation** → Plan photos
4. **Editor** → Review
5. **Publisher** → Publish

### ✍️ New Blog Post
1. **Copywriter** → Write article
2. **SEO Specialist** → Optimize
3. **Editor** → Review
4. **Publisher** → Publish

### 🛍️ Product Roundup/Gift Guide
1. **Copywriter** → Structure content
2. **Affiliate Manager** → Add products + disclosures
3. **SEO Specialist** → Optimize
4. **Editor** → Review compliance
5. **Publisher** → Publish

## Essential Standards

### ✅ Always Use
- British English (colour, centre, realise)
- UK measurements (°C, g, ml, Gas Mark)
- UK date format (DD/MM/YYYY or "3rd February 2026")
- British terms (courgette, aubergine, coriander, rocket)

### ❌ Never Use
- American English (color, center, realize)
- Fahrenheit alone (always add Celsius)
- US date format (MM/DD/YYYY)
- American terms (zucchini, eggplant, cilantro, arugula)

## Key Skills Reference

| Skill | Use For |
|-------|---------|
| **british-english-standards** | Language, measurements, terminology |
| **recipe-formatting** | Recipe structure, ingredients, method |
| **seo-optimization** | SEO titles, keywords, content structure |

## Quick Checklists

### Recipe Checklist
- [ ] UK measurements (g, ml, °C with Gas Mark)
- [ ] British ingredient names
- [ ] Numbered method steps
- [ ] Timing for each step
- [ ] Prep/cook/total time in frontmatter
- [ ] Servings specified
- [ ] Tips/notes section included

### Blog Post Checklist
- [ ] Engaging introduction with keyword
- [ ] Clear H2/H3 structure
- [ ] Short paragraphs (2-4 sentences)
- [ ] Internal links (2-4)
- [ ] External links (1-2)
- [ ] Strong conclusion with CTA
- [ ] British English throughout

### Publication Checklist
- [ ] Filename: `YYYY-MM-DD-post-slug.markdown`
- [ ] Complete frontmatter
- [ ] Categories and tags set
- [ ] Images optimized (<200KB)
- [ ] Alt text on all images
- [ ] All links working
- [ ] British English & UK measurements verified

## Common Measurements

| Description | Metric (UK) | Imperial | Gas Mark |
|-------------|-------------|----------|----------|
| Very hot oven | 240°C | 475°F | 9 |
| Hot oven | 220°C | 425°F | 7 |
| Moderate oven | 180°C | 350°F | 4 |
| Cool oven | 150°C | 300°F | 2 |
| | | | |
| Cup flour | 125g | 4.5 oz | - |
| Cup sugar | 200g | 7 oz | - |
| Cup liquid | 250ml | 8 fl oz | - |
| Tablespoon | 15ml | 0.5 fl oz | - |
| Teaspoon | 5ml | - | - |

## British Ingredient Names

| British | American |
|---------|----------|
| Courgette | Zucchini |
| Aubergine | Eggplant |
| Coriander (herb) | Cilantro |
| Rocket | Arugula |
| Spring onions | Scallions |
| Chickpeas | Garbanzo beans |
| Broad beans | Fava beans |
| Mangetout | Snow peas |
| Swede | Rutabaga |
| Cling film | Plastic wrap |
| Kitchen roll | Paper towels |

## Temperature Conversions

**Oven Temperatures:**
- 150°C = 300°F = Gas Mark 2
- 160°C = 325°F = Gas Mark 3
- 180°C = 350°F = Gas Mark 4
- 190°C = 375°F = Gas Mark 5
- 200°C = 400°F = Gas Mark 6
- 220°C = 425°F = Gas Mark 7
- 230°C = 450°F = Gas Mark 8

**Always use:** `180°C (350°F/Gas Mark 4)` format

## SEO Quick Tips

### Good Recipe Title Format
- "[Adjective] [Dish] | [Benefit]"
- Example: "Easy Vegan Lasagne | Family-Friendly Recipe"

### Keyword Placement
1. In title (beginning if possible)
2. First 100 words
3. At least one H2 heading
4. Throughout content naturally (3-5 times)
5. In conclusion

### Internal Links
- 2-4 per post
- Use descriptive anchor text
- Link to related recipes/articles

## Affiliate Disclosure Template

```markdown
*This post contains affiliate links. If you purchase through these 
links, we may earn a small commission at no extra cost to you. 
We only recommend products we genuinely use and believe in.*
```

Place at the beginning of post, before first affiliate link.

## Frontmatter Templates

### Recipe
```yaml
---
layout: post
title: "Recipe Name"
date: 2026-02-03 14:30:00 +0000
categories: recipes desserts
tags: vegan chocolate baking easy
prep_time: "20 minutes"
cook_time: "30 minutes"
total_time: "50 minutes"
servings: 8
difficulty: Easy
---
```

### Blog Post
```yaml
---
layout: post
title: "Post Title"
date: 2026-02-03 14:30:00 +0000
categories: lifestyle nutrition
tags: plant-based health beginners
---
```

## Image Requirements

- **Dimensions**: 1200 x 800 pixels (3:2 ratio) for recipes
- **File size**: <200KB (compressed)
- **Format**: JPEG for photos, PNG for graphics
- **Filename**: `recipe-name-descriptor.jpg` (lowercase, hyphens)
- **Alt text**: Descriptive, includes keywords naturally

Example: `vegan-chocolate-cake-slice.jpg`

## Need More Help?

- See full agent documentation in `.github/agents/`
- Check skill documentation in `.github/skills/`
- Read complete guide in `.github/README.md`

---

**Quick tip**: When in doubt, reference the **british-english-standards** skill and use the **Editor Agent** for final checks!
