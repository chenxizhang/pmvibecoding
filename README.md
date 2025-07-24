# PM Vibe Coding Repository

This repository is designed specifically for Product Managers to practice **vibe coding** in Visual Studio Code - a rapid prototyping and validation approach that helps PMs quickly turn ideas into tangible prototypes.

## What is Vibe Coding?

Vibe coding is a methodology that enables Product Managers to quickly prototype and validate ideas through rapid development cycles. This template comes pre-configured with custom chat modes, essential extensions, and MCP servers to help you get started immediately.

## Quick Start

Ready to start prototyping? Follow these simple steps

1. **Ensure Required Extensions**: Make sure you have all the necessary VS Code extensions installed (they should be pre-configured in this template), if you want use figma MCP server, you need to follow the guidance from [Figma Dev Mode MCP Server Guide](https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Dev-Mode-MCP-Server).
2. **Open Copilot Chat**: Press `Ctrl+Shift+I` to open the GitHub Copilot Chat interface
3. You can use the template in several ways below
   - **SurpriseMe mode**: You have a crazy idea, and want to see how it could be immediately. You don't want to think too much details, and won't answer too many questions from the agent. Please type `/surpriseMe ` in the chat, follow the very simple idea you have in mind, the agent will generate a prototype for you very quickly. As mentioned, don't be surprised if the prototype is not what you expected, it is just a starting point for you to iterate. The agent just do it in a crazy way, since you don't provide too many details.
   - **FollowMe mode**: You have a more lear idea, and have written down the spec as a prompt so that the agent can follow your instructions. Please type `/simpletodoapp ` in the chat and press `Enter`. The agent will follow your instructions to generate a prototype for you. The sample prompt you can find in `.gitHub/prompts/simpletodoapp.prompt.md`. You can also modify the prompt to fit your needs.
   - **Figma to code**: You have a Figma design, and want to convert it to code. You can use the `/figmaToCode` command in the chat, put your figma link there and press `Enter`. The agent will help you convert the design into a prototype. In this case, you need to make sure you have the Figma Dev Mode MCP Server running, and the link is accessible by the agent.
   - **PM Prototyping mode**: This is a more formal and complex mode you can work with the agent together to brainstorm and prototype your idea. The agent will help you to clarify your idea, generate the spec, design for your confirm, and then break down the tasks to implement the prototype. You can switch to `PM prototyping` mode (on the bottom left corner of the chat interface) to start talking with the agent. 
4. Preview the generated prototype in VSCode directly without any server support. The code will be generated in the `src` folder, and you can open the `index.html` file to see the result, usually you can press the `Ctrl+Shift+V` to preview the HTML file in VSCode directly.
5. Save your work. Once you get done and verify the prototype, please checkin the code to the repository so that you can keep track of your progress and share it with others. You can also create a new branch for each prototype you create to keep things organized. 

Happy vibe coding and good luck! 🚀


## Advance usage

I know you might have questions about how to use the template multiple times, for example, you want to try different ideas or different modes. Here are some tips:

1. Each time you want to try a new scenario, you can simply remove the `src` folder and then start your new advanture.
2. If you want to save all the prototypes you have created, you can create a new branch for each prototype. For example, if you want to create a prototype for a simple todo app, you can create a new branch called `simple-todo-app` and then start your work there. Once you are done, you can merge it back to the main branch or keep it as a separate branch for future reference. Please help yourself on how to use git commands to create branches and manage your code.

## Contact

If you have any questions or feedback, feel free to reach out to Ares Chen.

