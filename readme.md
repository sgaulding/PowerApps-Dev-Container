# PowerApps Dev Container

This project provides a development environment for building PowerApps using VS Code and Docker containers. With this setup, you can develop, test, and deploy PowerApps in a consistent and isolated environment, without having to set up PowerApps tools and dependencies on your local machine.

## Requirements

- Visual Studio Code
- Docker Desktop

## Getting Started

1. Clone the repository.
1. Open the project folder in VS Code.
1. Start the dev container by running the "Remote-Containers: Reopen in Container" command from the Command Palette (Ctrl+Shift+P).
1. Install any required VS Code extensions by opening the Extensions view (Ctrl+Shift+X) and searching for the extension name. Required extensions for this project are listed in the .vscode/extensions.json file.
1. Start the PowerApps CLI by running the "pac" command in the terminal.
1. Use the PowerApps CLI to create, build, and deploy PowerApps.

## Project Structure

This project includes the following files and folders:

- `.devcontainer`: Contains the configuration for the development container, including the Dockerfile and dev container settings.
- `.vscode`: Contains VS Code settings, including launch configurations and extensions.
- `src`: Contains the source code for the PowerApps project.

## Contributing

Contributions are welcome! If you find a bug or want to add a feature, please create an issue or a pull request on GitHub.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
