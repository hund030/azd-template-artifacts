# This is the template README for what is expected in submitted templates.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](placeholder)
[![Open in Dev Containers](https://img.shields.io/static/v1?style=for-the-badge&label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](placeholder)

# Project Name
 
(Longer Description, as compared to the GitHub "about" section of the project)
(make sure to highlight the use case!)
Sample application code is included in this project. You can use or modify this app code or you can rip it out and include your own.
 
 
## Features
 
This project framework provides the following features:
 
* Feature 1
* Feature 2
* ...
 
### Architecture Diagram

Include a diagram describing the application

### Demo Video (optional)

(Embed demo video here)
 
## Getting Started

You have a few options for getting started with this template
The quickest way to get started is GitHub Codespaces, since it will setup all the tools for you, but you can also [set it up locally](#local-environment).

### GitHub Codespaces

You can run this template virtually by using GitHub Codespaces. The button will open a web-based VS Code instance in your browser:

1. Open the template (this may take several minutes)
    [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](placeholder)
2. Open a terminal window
3. [any other steps needed for your template]
4. Run `azd up`

### VS Code Dev Containers

A related option is VS Code Dev Containers, which will open the project in your local VS Code using the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers):

1. Start Docker Desktop (install it if not already installed)
2. Open the project:
    [![Open in Dev Containers](https://img.shields.io/static/v1?style=for-the-badge&label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](placeholder)
3. In the VS Code window that opens, once the project files show up (this may take several minutes), open a terminal window.
4. [any other steps needed for your template]
5. Run `azd up`

### Local Environment

#### Prerequisites
 
(ideally very short, if any)
 
- Install [azd](https://aka.ms/install-azd)
    - Windows: `winget install microsoft.azd`
    - Linux: `curl -fsSL https://aka.ms/install-azd.sh | bash`
    - MacOS: `brew tap azure/azd && brew install azd`
- OS
- Library version
- This model uses [MODEL 1] and [MODEL 2] which may not be available in all Azure regions. Check for [up-to-date region availability](https://learn.microsoft.com/azure/ai-services/openai/concepts/models#standard-deployment-model-availability) and select a region during deployment accordingly
    - We recommend using [SUGGESTED REGION]
- ...

#### Installation

(ideally very short)
 
- npm install [package name]
- mvn install
- ...

#### Quickstart

(Add steps to get up and running quickly)
 
1. Clone the repository and intialize the project: `azd init [name-of-repo]`
2. ...
3. Provision and deploy the project to Azure: `azd up`
4. Set up CI/CD with `azd pipeline config`
5. (Add steps to start up the sample app)

#### Local Development

Describe how to run and develop the app locally

## Costs

You can estimate the cost of this project's architecture with [Azure's pricing calculator](https://azure.microsoft.com/pricing/calculator/)

- [Azure Product] - [plan type] [link to pricing for product](https://azure.microsoft.com/pricing/)

## Security Guidelines

> [!NOTE]
> When implementing this template please specify whether the template uses Managed Identity or Key Vault

This template has either [Managed Identity](https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/overview) or Key Vault built in to eliminate the need for developers to manage these credentials. Applications can use managed identities to obtain Microsoft Entra tokens without having to manage any credentials. Additionally, we have added a [GitHub Action tool](https://github.com/microsoft/security-devops-action) that scans the infrastructure-as-code files and generates a report containing any detected issues. To ensure best practices in your repo we recommend anyone creating solutions based on our templates ensure that the [Github secret scanning](https://docs.github.com/en/code-security/secret-scanning/about-secret-scanning) setting is enabled in your repos.

## Resources

(Any additional resources or related projects)
 
- Link to supporting information
- Link to similar sample
- [Develop Python apps that use Azure AI services](https://learn.microsoft.com/azure/developer/python/azure-ai-for-python-developers)
- ...
