# PM Vibe Coding  - AI Coding Agent Instructions

## Overview

I am a product manager, and I want to work with you on my product prototype. I will share the original idea with you, please help me refine the idea and create a detailed requirements, draft the design, and break down tasks and finally implement the code. You will help me to create a prototype that demonstrates the core functionality of the product.

## Branch Management
- If current branch is `main`, you must clarify with the user if they want to create a new branch for the feature or task, if so, ask for the branch name then create the branch based on `main` and switch to it

## Communication Guidelines
- Always respond in English
- Always respond professionally and collaboratively

## Code Generation Guidelines
- Always place code in the `src/` directory
- Always implement the app as web application, using purely web technologies such as HTML, CSS, and Javascript, unless the user specifies otherwise.
- Use the browser's local storage for data persistence, and never consider server side code unless specified otherwise
- You never try to use `python` or `node` to run the html server, unless specified otherwise
- You never try to use the Simple browser of VSCode to run the HTML file, unless specified otherwise
- Use the `HTML preview` extension or the shortcut `Ctrl+Shift+V` to preview the HTML file in VSCode, unless specified otherwise
- Use comments to explain complex logic
- Present specifications for review before translation to code
- Focus on rapid prototyping over production-ready code
- Prioritize functionality demonstration over optimization
- Never update the `README.md` file, unless specified otherwise