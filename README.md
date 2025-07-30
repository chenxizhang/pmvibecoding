# PM Vibe Coding Repository

This repository is designed specifically for Product Managers to practice **vibe coding** in Visual Studio Code - a rapid prototyping and validation approach that helps PMs quickly turn ideas into tangible prototypes.

## What is Vibe Coding?

Vibe coding is a methodology that enables Product Managers to quickly prototype and validate ideas through rapid development cycles. This template comes pre-configured with custom chat modes, essential extensions, and MCP servers to help you get started immediately.

## Quick Start

Ready to start prototyping? Follow these simple steps

1. **Ensure Required Extensions**: Make sure you have all the necessary VS Code extensions installed (they should be pre-configured in this template), if you want use figma MCP server, you need to follow the guidance from [Figma Dev Mode MCP Server Guide](https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Dev-Mode-MCP-Server).
2. **Open Copilot Chat**: Press `Ctrl+Shift+I` to open the GitHub Copilot Chat interface
3. You can use the template in several ways below. Pleease note that the agent will prefer to create a new branch for each prototype you build, so that you can maintain your work and keep things organized. 
   - **SurpriseMe mode**: You have a crazy idea, and want to see how it could be immediately. You don't want to think too much details, and won't answer too many questions from the agent. Please type `/surpriseMe ` in the chat, follow the very simple idea you have in mind, the agent will generate a prototype for you very quickly. As mentioned, don't be surprised if the prototype is not what you expected, it is just a starting point for you to iterate. The agent just do it in a crazy way, since you don't provide too many details.
   - **FollowMe mode**: You have a more lear idea, and have written down the spec as a prompt so that the agent can follow your instructions. Please type `/followMe ` in the chat and press `Enter`. The agent will follow your instructions to generate a prototype for you. The sample prompt you can find in `.gitHub/prompts/followMe.prompt.md`. You can also modify the prompt to fit your needs.
   - **Figma to code**: You have a Figma design, and want to convert it to code. You can use the `/figmaToCode` command in the chat, put your figma link there and press `Enter`. The agent will help you convert the design into a prototype. In this case, you need to make sure you have the Figma Dev Mode MCP Server running, and the link is accessible by the agent.
   - **PM Prototyping mode**: This is a more formal and complex mode you can work with the agent together to brainstorm and prototype your idea. The agent will help you to clarify your idea, generate the spec, design for your confirm, and then break down the tasks to implement the prototype. You can switch to `PM prototyping` mode (on the bottom left corner of the chat interface) to start talking with the agent. 
4. Preview the generated prototype in VSCode directly without any server support. The code will be generated in the `src` folder, and you can open the `index.html` file to see the result, usually you can press the `Ctrl+Shift+V` to preview the HTML file in VSCode directly.
5. Save your work. Once you get done and verify the prototype, please checkin the code to the repository so that you can keep track of your progress and share it with others. 
6. Once you get done, I'd prefer you back to the `main` branch, just talk with the agent by typing `back to main branch` or something similar, the agent will help you to switch back to the `main` branch. Remember, everytime you want to create a new prototype, you start from the `main` branch, and agent will create a new branch for the prototype you want to build. This approach will help you to keep your work organized and avoid conflicts with other prototypes you create in the future. If you want to customize the template, please do it in the `main` branch (don't forget to save your customization and checkin the code), and next time you create a new prototype, the agent will use the updated template to generate the code for you. 

Happy vibe coding and good luck! 🚀

## Learning from AI

Before you checkin your code, you might want to learn something from the AI agent. I'd highly recommend you to use the `/educateMe` command in the chat, which will help you to understand the changes made by the agent, the rationale behind the decisions, and the technical choices made during the prototyping process. This will not only help you to learn from the agent's expertise but also apply it to your future projects.

## Contact

If you have any questions or feedback, feel free to reach out to Ares Chen.

