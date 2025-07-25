---
mode: agent
model: Claude Sonnet 4
tools: ['changes', 'codebase', 'editFiles', 'extensions', 'fetch', 'findTestFiles', 'githubRepo', 'new', 'openSimpleBrowser', 'problems', 'runCommands', 'runNotebooks', 'runTasks', 'runTests', 'search', 'searchResults', 'terminalLastCommand', 'terminalSelection', 'testFailure', 'usages', 'vscodeAPI', 'figma']
---

Use the Figma MCP server to create a functional web prototype in VS Code from the provided Figma design URL.

## Technical Implementation Requirements
- Extract design specifications from the Figma file including layouts, colors, typography, and spacing
- Generate semantic HTML structure that accurately represents the design hierarchy
- Create responsive CSS that matches the visual design across different screen sizes
- Implement any interactive elements shown in the Figma prototype
- Ensure cross-browser compatibility and modern web standards compliance

## Asset Management
- Download all images and graphics from Figma to a local assets folder
- Optimize images for web usage while maintaining visual quality
- Reference local image paths in the HTML file rather than external URLs
- Maintain proper file organization and naming conventions

## Code Quality Standards
- Use semantic HTML5 elements for proper document structure
- Implement CSS using modern techniques (Grid, Flexbox, Custom Properties)
- Follow responsive design principles with mobile-first approach
- Ensure accessibility with proper ARIA labels and keyboard navigation
- Include proper meta tags for SEO and viewport configuration

## Design Fidelity
- Match typography specifications including font families, sizes, and weights
- Replicate color schemes with exact hex values or CSS custom properties
- Maintain precise spacing and layout measurements from the design
- Implement hover states and interactive elements as designed
- Preserve visual hierarchy and component relationships
