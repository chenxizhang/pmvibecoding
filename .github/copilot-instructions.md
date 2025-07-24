# PM Vibe Coding  - AI Coding Agent Instructions

## Overview

I am a product manager, and I want to work with you on my product prototype. I will share the original idea with you, please help me refine the idea and create a detailed requirements, draft the design, and break down tasks and finally implement the code. You will help me to create a prototype that demonstrates the core functionality of the product.

## Prequisites

- If current branch is `main`, you need to clarify with the user if they want to create a new branch for the implementation. if so, generate a new branch name based on the task description, create the branch, and switch to it.

## Communication Guidelines
- Always respond in English
- Always respond professionally and collaboratively

## Code Generation Guidelines
- **🚨 CRITICAL: ALWAYS FOLLOW FILE-SPECIFIC CODING INSTRUCTIONS 🚨**
  - Located in `.github/instructions/` directory
  - MANDATORY before creating or modifying ANY file
  - Use `read_file` tool to get instructions if not in context
- Always place code in the `src/` directory
- Always implement the app as web application, using purely web technologies such as HTML, CSS, and Javascript, unless the user specifies otherwise
- Use the browser's local storage for data persistence, never consider server side code unless specified otherwise
- Use comments to explain complex logic
- Present specifications for review before translation to code
- Focus on rapid prototyping over production-ready code
- Prioritize functionality demonstration over optimization

## Coding Instructions Compliance
- **BEFORE creating or editing any file**, always check if there are specific coding instructions for that file type
- **HTML files**: Must include the required meta description tag as specified in `html.instructions.md`
- **All file types**: Follow any pattern-specific rules defined in the corresponding instruction files
- **If instructions exist but aren't provided in context**: Use the `read_file` tool to acquire the instruction file before making changes
- **Non-negotiable**: Coding instructions take precedence over general guidelines unless they contradict system messages

## 🚨 STRICT COMPLIANCE RULES 🚨

### What to NEVER do unless explicitly requested:
- ❌ Never create files beyond what the user specifically asks for
- ❌ Never update README.md
- ❌ Never perform git operations (add, commit, push, etc.)
- ❌ Never create launcher scripts, batch files, or server scripts
- ❌ Never install extensions or packages
- ❌ Never use python/node to run HTML servers
- ❌ Never use VS Code Simple Browser
- ❌ Never open external browsers automatically

### Required Behavior:
- ✅ ONLY create files that directly fulfill the user's request
- ✅ ONLY perform actions explicitly requested by the user
- ✅ ASK before adding "helpful" extras or conveniences
- ✅ Use VS Code preview (`Ctrl+Shift+V` or `george-alisson.html-preview-vscode`)
- ✅ Stop and confirm if unsure about scope

### Pre-Action Validation:
Before taking ANY action, ask:
1. "Did the user specifically request this file/action?"
2. "Is this required to fulfill their exact request?"
3. "Am I adding extras they didn't ask for?"

If answer to #3 is YES → DON'T do it.

## 🎯 MANDATORY CHECKLIST
- [ ] User explicitly requested this action
- [ ] This is essential to their core request
- [ ] I've read relevant coding instructions
- [ ] Following their preferred workflow