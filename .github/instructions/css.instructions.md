---
applyTo: "**/*.css"
---

# CSS Coding Instructions

## Required Practices

1. **Mobile-first responsive design** - Use min-width media queries
2. **CSS Custom Properties** - Use CSS variables for consistent theming
3. **Accessible colors** - Ensure sufficient contrast ratios
4. **Modern layout** - Prefer flexbox/grid over floats
5. **Performance** - Avoid excessive nesting and overly specific selectors

## Mandatory Elements

```css
/* CSS Custom Properties */
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    /* Add theme variables */
}

/* Mobile-first responsive */
@media (min-width: 768px) {
    /* Tablet styles */
}

@media (min-width: 1024px) {
    /* Desktop styles */
}
```

## Structure Requirements

- Use consistent naming convention (BEM recommended)
- Include focus states for interactive elements
- Ensure text remains readable at 200% zoom
- Use semantic color names in custom properties
