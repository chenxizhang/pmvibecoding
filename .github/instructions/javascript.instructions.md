---
applyTo: "**/*.js"
---

# JavaScript Coding Instructions

## Required Practices

1. **Use strict mode** - Always start files with `'use strict';`
2. **Error handling** - Wrap risky operations in try-catch blocks
3. **Local storage access** - Always check if localStorage is available before using
4. **Event listeners** - Remove event listeners when no longer needed to prevent memory leaks
5. **Comments** - Add JSDoc comments for complex functions

## Code Structure

```javascript
'use strict';

/**
 * Function description
 * @param {type} param - Parameter description
 * @returns {type} Return description
 */
function exampleFunction(param) {
    try {
        // Implementation
    } catch (error) {
        console.error('Error in exampleFunction:', error);
    }
}
```

## Mandatory Elements

- All JavaScript files must include error handling for critical operations
- Use const/let instead of var
- Include proper function documentation for complex logic
- Handle edge cases gracefully
