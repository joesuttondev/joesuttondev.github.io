---
name: recipe-formatting
description: Standards and guidelines for structuring recipe content with proper Jekyll frontmatter and markdown
---

# Recipe Formatting Skill

## Recipe Structure Standards

### Frontmatter (Jekyll)
```yaml
---
layout: post
title: "Recipe Name"
date: YYYY-MM-DD HH:MM:SS +0000
categories: recipes [cuisine-type] [meal-type]
tags: [dietary-requirements, key-ingredients]
prep_time: "XX minutes"
cook_time: "XX minutes"
total_time: "XX minutes"
servings: X
difficulty: Easy|Medium|Hard
featured_image: /assets/images/recipe-slug.jpg
---
```

### Recipe Content Structure

#### 1. Introduction (50-100 words)
- Brief, engaging description of the dish
- What makes it special or unique
- Who it's perfect for or when to serve it

#### 2. Key Information Section
```markdown
**Prep Time:** XX minutes  
**Cook Time:** XX minutes  
**Total Time:** XX minutes  
**Servings:** X  
**Difficulty:** Easy/Medium/Hard
```

#### 3. Ingredients List
- Use clear, structured markdown lists
- Group ingredients by component if recipe has multiple parts
- Always specify quantities first, then ingredient name
- Include preparation notes in brackets
- Example:
```markdown
## Ingredients

### For the Base
- 250g plain flour
- 1 tsp baking powder
- 100ml plant-based milk (at room temperature)

### For the Topping
- 2 medium courgettes (sliced thinly)
- 1 tbsp olive oil
```

#### 4. Method/Instructions
- Number each step clearly
- One action per step when possible
- Include timing information
- Add temperature settings
- Include visual cues (e.g., "until golden brown")
- Example:
```markdown
## Method

1. Preheat your oven to 180°C (350°F/Gas Mark 4).

2. In a large mixing bowl, combine the flour and baking powder.

3. Gradually add the plant-based milk, stirring until you have a smooth batter.

4. Heat the olive oil in a large frying pan over medium heat.
```

#### 5. Chef's Notes/Tips (Optional but Recommended)
- Storage instructions
- Substitution suggestions
- Make-ahead tips
- Serving suggestions
- Variations

#### 6. Nutritional Information (Optional)
```markdown
## Nutritional Information (Per Serving)

- **Calories:** XXX kcal
- **Protein:** XXg
- **Carbohydrates:** XXg
- **Fat:** XXg
- **Fibre:** XXg
```

## Formatting Guidelines

### Measurements
- Always use UK metric measurements (see british-english-standards skill)
- Be precise: "250g" not "about 250g" in ingredients list
- Use approximations in method if appropriate: "about 5 minutes"

### Temperature
- Always include Gas Mark for ovens
- Format: "180°C (350°F/Gas Mark 4)"

### Timing
- Be specific in instructions
- Include ranges when appropriate: "20-25 minutes"
- Include visual cues: "until golden and bubbling"

### Lists
- Use hyphens (-) for unordered lists
- Use numbers (1.) for ordered lists (method steps)
- Maintain consistent formatting

### Emphasis
- Use **bold** for important terms or warnings
- Use *italics* sparingly for emphasis
- Use > blockquotes for important tips or notes

## SEO Considerations
- Include recipe name in title and first paragraph
- Use relevant keywords naturally
- Add descriptive alt text for images
- Include cooking time and difficulty in metadata
- Use structured headings (H2, H3) appropriately

## Accessibility
- Write clear, concise instructions
- Avoid jargon; explain technical terms
- Provide alternative methods when possible
- Include visual and tactile cues (not just time-based)
