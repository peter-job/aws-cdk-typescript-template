# Dev Container

Included is a [dev container](https://containers.dev) configuration for creating an ephemeral development environment that should work out of the box.

See the [configuration file](../.devcontainer/devcontainer.json) for more details.

**Pre-requisites:**
- [VS Code](https://code.visualstudio.com)
- [VS Code Extension: Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)

**Tested on:**
- MacOS 15

#### 1. Install dependencies

- [VS Code](https://code.visualstudio.com/download)
- [VS Code Extension: Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)


#### 2. Clone the repo locally and open in VS Code

```bash
cd path/to/your/projects
git clone https://github.com/peter-job/aws-cdk-typescript-template.git
code aws-cdk-typescript-template
```

#### 3. Reopen the project in a dev container

Run the command `Dev Containers: Reopen in Container` from the command palette (Cmd+Shift+P or Ctrl+Shift+P)

This will open a new development environment for VS Code in a container.

If you don't see this option, make sure you have the Dev Containers extension installed.
