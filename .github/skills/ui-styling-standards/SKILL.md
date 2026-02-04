# UI and Styling Standards for PlantBased.Blog

## Overview

This skill defines the visual design standards and UI guidelines for PlantBased.Blog. All content creators, designers, and developers should follow these guidelines to maintain a consistent, modern, and welcoming aesthetic that reflects the plant-based and wellness focus of the site.

## Design Philosophy

**Nature-Inspired & Welcoming**: The design draws inspiration from nature with organic colours, soft edges, and warm tones that create a calming, inviting atmosphere.

**Modern & Clean**: Contemporary design with plenty of white space, clear hierarchy, and intuitive navigation.

**Accessibility-First**: All design choices prioritise readability, contrast, and usability for all visitors.

**Recipe-Focused**: Special attention to recipe presentation with clear ingredient lists, step-by-step instructions, and easy-to-scan layouts.

## Colour Palette

### Primary Colours
- **Primary Green**: `#5a7d5a` - Main brand colour, used for headings, CTAs, and key elements
- **Primary Green Light**: `#7a9d7a` - Hover states and lighter accents
- **Primary Green Dark**: `#3a5a3a` - Dark text, footer, deep emphasis

### Accent Colours
- **Sage**: `#b7c9b7` - Soft accent for borders and subtle backgrounds
- **Cream**: `#f8f6f1` - Warm background for ingredient lists and callouts
- **Terracotta**: `#d97757` - Warm accent for special notes and highlights
- **Golden**: `#daa520` - Accent for special features and awards

### Neutral Colours
- **Text Primary**: `#2d3436` - Main body text
- **Text Secondary**: `#636e72` - Meta information, captions
- **Background Primary**: `#ffffff` - Main content backgrounds
- **Background Secondary**: `#fafaf8` - Page background
- **Border**: `#e8e6e1` - Subtle borders and dividers

## Typography

### Font Stack
```css
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
```

### Font Sizes and Hierarchy
- **H1**: 2.5em (40px base) - Page titles, recipe names
- **H2**: 2em (32px base) - Major sections
- **H3**: 1.5em (24px base) - Subsections
- **Body**: 17px - Main content
- **Small/Meta**: 0.95em (16px) - Dates, categories, secondary info

### Font Weights
- **Regular**: 400 - Body text
- **Medium**: 500 - Navigation links
- **Semibold**: 600 - Buttons, emphasis
- **Bold**: 700 - Headings

### Line Height
- **Headings**: 1.2-1.3
- **Body Text**: 1.7-1.8
- **Lists**: 1.6

## Layout Standards

### Content Width
- **Maximum Width**: 900px - Optimal reading width for recipes and articles
- **Padding**: 3em on desktop, 2em on tablet, 1.5em on mobile
- **Margin**: 2em top/bottom on desktop, 1em on mobile

### Spacing System
Use consistent spacing multiples:
- **Micro**: 0.5em (8px)
- **Small**: 1em (16px)
- **Medium**: 1.5em (24px)
- **Large**: 2em (32px)
- **XLarge**: 3em (48px)

### Border Radius
- **Small Elements**: 4px (buttons, code blocks)
- **Cards**: 8px (recipe cards, content boxes)
- **Large Cards**: 12px (featured recipes, hero sections)

## Component Styles

### Recipe Cards (Post List)
- **Background**: White with soft shadow
- **Border**: 1px solid `#e8e6e1`
- **Border Radius**: 12px
- **Shadow**: `0 4px 15px rgba(90, 125, 90, 0.1)`
- **Hover Effect**: Lift up 5px with deeper shadow
- **Padding**: 2em

### Ingredient Lists
- **Background**: Cream (`#f8f6f1`)
- **Border Left**: 4px solid Primary Green
- **Padding**: 1.5em 2em
- **Border Radius**: 8px
- **Line Spacing**: 1.6

### Recipe Instructions (Ordered List)
- **Numbered Circles**: Green background, white text
- **Circle Size**: 2em diameter
- **Font Weight**: Bold
- **Step Padding**: 3em left to accommodate circle
- **Step Spacing**: 1.5em between steps

### Tips and Notes (Blockquotes)
- **Background**: Cream (`#f8f6f1`)
- **Border Left**: 4px solid Terracotta
- **Padding**: 1em 1.5em
- **Font Style**: Italic
- **Border Radius**: 4px

### Buttons and CTAs
- **Background**: Primary Green
- **Text**: White, semibold
- **Padding**: 0.8em 2em
- **Border Radius**: 6px
- **Hover Effect**: Darker green + lift up 2px
- **Transition**: 0.3s ease

### Section Headings (H2)
- **Border Bottom**: 3px solid Sage
- **Padding Bottom**: 0.3em
- **Margin Top**: 1.5em
- **Margin Bottom**: 0.75em

## Recipe-Specific Styling

### Recipe Meta Information Box
- **Display**: Grid layout (auto-fit columns)
- **Background**: Linear gradient from Cream to Sage
- **Padding**: 1.5em
- **Border Radius**: 12px
- **Shadow**: Soft green shadow
- **Text Alignment**: Centre

### Nutritional Information Tables
- **Header Background**: Primary Green
- **Header Text**: White
- **Row Hover**: Cream background
- **Border**: Subtle grey borders between rows
- **Border Radius**: 8px (rounded table)
- **Shadow**: Soft shadow around table

## Header and Navigation

### Site Header
- **Background**: White
- **Top Border**: 5px solid Primary Green
- **Bottom Border**: 1px solid border colour
- **Shadow**: Subtle shadow for depth

### Site Title
- **Font Size**: 1.8em
- **Font Weight**: 800 (extra bold)
- **Colour**: Primary Green Dark
- **Hover**: Primary Green (lighter)

### Navigation Links
- **Colour**: Text Secondary
- **Font Weight**: 500 (medium)
- **Hover**: Primary Green
- **Spacing**: Adequate padding between links

## Footer

### Site Footer
- **Background**: Primary Green Dark
- **Text**: Cream colour
- **Top Border**: 4px solid Primary Green
- **Link Colour**: Sage
- **Link Hover**: Cream

## Image Guidelines

### Image Selection
- **Style**: Natural, bright, appetising food photography
- **Colour Palette**: Should complement the site colours (greens, earth tones)
- **Composition**: Clean, uncluttered, well-lit
- **Quality**: High resolution, at least 1200px wide for featured images

### Image Treatment
- **Border Radius**: 8px for content images
- **Shadow**: Optional soft shadow for depth
- **Alt Text**: Always include descriptive alt text for accessibility

### Image Placement
- **Featured Images**: Full width within content area
- **Gallery**: Grid layout with consistent spacing
- **Thumbnails**: Square crop, 300x300px minimum

## Responsive Design

### Breakpoints
- **Desktop**: > 800px
- **Tablet**: 600px - 800px
- **Mobile**: < 600px

### Mobile Optimisations
- **Font Size**: Reduce base to 16px
- **Padding**: Reduce wrapper padding to 1.5em → 1em
- **Headings**: Scale down proportionally
- **Recipe Meta Grid**: 2 columns on tablet, 1 column on mobile
- **Navigation**: Hamburger menu (handled by Minima theme)
- **Recipe Steps**: Smaller numbered circles (1.8em)

## Accessibility Standards

### Colour Contrast
- **WCAG AA Compliance**: Minimum 4.5:1 for normal text
- **WCAG AAA Preferred**: 7:1 for normal text when possible
- **Primary Green on White**: Passes AA for body text
- **White on Primary Green**: Passes AAA for buttons/CTAs

### Focus States
- **Outline**: 3px solid Primary Green Light
- **Offset**: 2px
- **Visible**: Always visible on keyboard navigation

### Alt Text
- **Required**: All images must have descriptive alt text
- **Decorative Images**: Use empty alt="" for purely decorative images

### Semantic HTML
- **Headings**: Proper hierarchy (H1 → H2 → H3)
- **Lists**: Use proper ul/ol elements
- **Links**: Descriptive link text (avoid "click here")
- **Tables**: Proper th elements for headers

## Animation and Transitions

### Transition Timing
- **Fast**: 0.2s - Colour changes, simple hovers
- **Medium**: 0.3s - Card lifts, button effects
- **Slow**: 0.5s - Complex animations

### Easing Functions
- **Default**: ease - Most transitions
- **Buttons**: ease-out - Smooth deceleration
- **Cards**: ease - Balanced feel

### Hover Effects
- **Cards**: Lift 5px + shadow increase
- **Buttons**: Darken + lift 2px
- **Links**: Colour change + underline

## Print Styles

### Print Optimisations (for recipes)
- **Hide**: Header, footer, navigation
- **Remove**: Shadows, borders, background colours
- **Simplify**: Links show as plain text
- **Optimise**: Black text on white for ink efficiency

## Content Formatting Guidelines

### Paragraph Structure
- **Length**: 2-4 sentences per paragraph
- **Spacing**: 1.5em between paragraphs
- **Line Length**: Max 900px (optimal readability)

### Lists
- **Ingredient Lists**: Unordered (bullets) with cream background
- **Instructions**: Ordered (numbers) with circular badges
- **Spacing**: 0.5em between items

### Emphasis
- **Bold**: Use sparingly for key terms
- **Italic**: Use for quotes, tips, notes
- **Colour**: Use accent colours for special callouts

## Implementation Notes for Content Creators

### When Creating New Posts
1. Use the defined colour palette - no custom colours
2. Follow heading hierarchy (H1 → H2 → H3)
3. Use standard Markdown formatting (the CSS handles styling)
4. Include proper frontmatter with categories and tags
5. Write descriptive alt text for all images

### Recipe Posts
1. Use H2 for major sections (Ingredients, Instructions, etc.)
2. Use H3 for subsections (For the Sauce, For the Topping, etc.)
3. Use unordered lists for ingredients
4. Use ordered lists for instructions
5. Use blockquotes for tips, notes, or serving suggestions

### Don't Override
- Don't add inline styles
- Don't use custom fonts
- Don't use colours outside the defined palette
- Don't break the responsive design with fixed widths

## File References

### CSS Location
- **Main Stylesheet**: `/assets/css/style.scss`
- **Imports**: Minima theme as base, then custom overrides

### Updating Styles
When updating styles:
1. Edit `/assets/css/style.scss`
2. Follow existing variable naming conventions
3. Use CSS custom properties (variables) for colours
4. Test on mobile, tablet, and desktop
5. Verify accessibility (contrast, focus states)

## Examples of Good Styling

### Recipe Card
```markdown
## Ingredients

### For the Base
- 400g chickpeas, drained
- 2 tablespoons tahini
- 1 clove garlic

## Instructions

1. Drain and rinse the chickpeas thoroughly.
2. Add all ingredients to a food processor.
3. Blend until smooth and creamy.

> **Top Tip**: Add ice cubes while blending for extra creaminess!
```

This will automatically style with:
- Green bordered ingredient box on cream background
- Numbered circular badges for steps
- Terracotta-bordered tip box

## Future Enhancements

Consider these potential additions:
- Recipe rating system (stars)
- Print-specific recipe card format
- Dark mode variant
- Recipe category icons
- Seasonal colour variations

## Questions or Issues?

When unsure about styling:
1. Check this document first
2. Review existing posts for examples
3. Use browser inspector to see computed styles
4. Test on multiple devices
5. Validate with accessibility tools

## Compliance

All agents creating content should:
- ✅ Use the defined colour palette
- ✅ Follow typography standards
- ✅ Implement responsive design
- ✅ Meet accessibility requirements
- ✅ Test on multiple screen sizes
- ✅ Include proper semantic HTML
