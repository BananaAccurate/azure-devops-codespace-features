# Codespace Features

This is a repository of [devcontainer features](https://containers.dev/implementors/features/)
to assist teams in adopting Codespaces. Here is a list of the features in this repository:

> This repository is intended to be kept private for internal use only.

| Feature | Description |
| ------- | ----------- |
| [artifacts-helper](src/artifacts-helper)   | Install Azure Artifacts credential helper configured for Codespace authentication |
| [devtool](src/devtool) | Installs DevTool (Microsoft-internal only) |
| [docfx](src/docfx)   | Install docfx to support editing and testing documentation |
| [external-repository](src/external-repository)   | Handles all the details of working with an external git repository in Codespaces |
| [microsoft-git](src/microsoft-git) | Install microsoft/git with Scalar and GVFS support |
| [go](src/go) | Install go (with support for Mariner) |

## How to make the GitHub repository private

To make this repository private, follow these steps in the GitHub web UI:

1. Open the repository on GitHub.
2. Click the **Settings** tab near the top of the repository page.
3. In the left sidebar, click **General**.
4. Scroll all the way down to **Danger Zone**.
5. Find **Change repository visibility** and click it.
6. Choose **Make private**.
7. Follow the confirmation prompt. GitHub may ask you to type the repository name before it will continue.

If you do not see the **Settings** tab or the **Change repository visibility** option, you probably do not have admin permission for the repository.

## Contributing

This repository is intended for private, internal collaboration. Coordinate access and contribution
expectations directly with the repository owners.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
