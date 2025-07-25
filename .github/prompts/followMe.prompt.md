---
mode: agent
model: Claude Sonnet 4
tools: ['changes', 'codebase', 'editFiles', 'extensions', 'fetch', 'findTestFiles', 'githubRepo', 'new', 'openSimpleBrowser', 'problems', 'runCommands', 'runNotebooks', 'runTasks', 'runTests', 'search', 'searchResults', 'terminalLastCommand', 'terminalSelection', 'testFailure', 'usages', 'vscodeAPI']
---

Follow the requirements below to create a modern, responsive task management application using HTML, CSS, and JavaScript.

## Technical Requirements
- Implement as a single-page web application using vanilla JavaScript with ES6+ features
- Ensure responsive design for mobile and desktop viewports
- Store data persistently in browser localStorage with proper error handling
- Follow semantic HTML structure and accessibility guidelines
- Use modern CSS features including Grid and Flexbox layouts

## Core Functionality
- Task CRUD operations: Create, read, update, and delete tasks with validation
- Task properties: title, description, priority level (High, Medium, Low), category, completion status, creation date
- Priority system with visual color coding (Red for High, Orange for Medium, Green for Low)
- Category system supporting: Personal, Work, Shopping, Health, Learning
- Filtering capabilities: All tasks, Pending only, Completed only with smooth transitions
- Real-time search functionality across task titles and descriptions
- Statistics dashboard displaying total tasks, completed count, and pending count with live updates

## User Interface Design
- Modern glassmorphism design with gradient backgrounds and backdrop filters
- Responsive grid layout adapting seamlessly to different screen sizes
- Smooth CSS transitions and hover effects for enhanced interactivity
- Custom-styled form controls and checkboxes with consistent design language
- Intuitive iconography for actions and categories
- Professional color palette with consistent theming throughout the application

## Advanced Features
- Data export functionality to JSON format with proper file naming
- Bulk actions for managing multiple tasks efficiently
- Intelligent sorting algorithm: incomplete tasks first, then by priority level
- Celebration animations upon task completion to enhance user satisfaction
- Toast notification system for user feedback on actions
- Keyboard shortcuts: Enter to submit forms, Escape to close modals

## User Experience Enhancements
- Pre-populated sample tasks for immediate demonstration of functionality
- Empty state messaging with clear guidance for new users
- Smart date formatting using relative time display (Today, Yesterday, X days ago)
- Modal-based editing interface with focus management
- Smooth micro-interactions and appropriate loading states

## Implementation Guidelines
- Use semantic HTML5 elements for better accessibility and SEO
- Implement proper error handling for localStorage operations and API calls
- Ensure graceful degradation if JavaScript is disabled
- Follow progressive enhancement principles
- Include proper ARIA labels and keyboard navigation support
- Optimize for performance with efficient DOM manipulation