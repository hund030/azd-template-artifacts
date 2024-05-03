The following checklist must be complete before a template is published.

# Repository Management

- [ ] Standards compliant [README.md](https://github.com/Azure-Samples/azd-template-artifacts/blob/main/README.md) as the one in the example, is in place
- [ ] [License](https://github.com/Azure-Samples/azd-template-artifacts/blob/main/LICENSE.md) is in place. Make sure you choose the [correct license](https://www.microsoft.com/en-us/legal/intellectualproperty/open-source)
- [ ] [Security guidelines](https://github.com/Azure-Samples/azd-template-artifacts/blob/main/SECURITY.md) are in place
- [ ] [Contribution guidelines](https://github.com/Azure-Samples/azd-template-artifacts/blob/main/CONTRIBUTING.md) are in place
- [ ] [Code of conduct](https://github.com/Azure-Samples/azd-template-artifacts/blob/main/.github/CODE_OF_CONDUCT.md) is in place
- [ ] [Issue template](.github/ISSUE_TEMPLATE.md) is in place
- [ ] Language, model, and relevant technology topic labels are added, including `azd-templates` and `ai-azd-templates` (The latter is being created)
- [ ] Repo description is in place, describing the use case and technologies used in the solution

## Source code structure and conventions

- [ ] GitHub Actions (This refers to .github/workflows/azure-dev.yml or custom workflow to run on a GitHub runner) is in place
- [ ] DevContainer (/.devcontainer folder where applicable) configuration is in place
- [ ] Infrastructure as code is in place (`/infra` folder where applicable, manifest files or code generators in the case of `Aspire` and similar )
- [ ] Azure services configuration (/azure.yml file) is in place
- [ ] Minimum coverage tests are in place

## Functional requirements

- [ ] `azd up` successfully provisions and deploys a functional app
- [ ] GitHub Actions run tasks without errors
- [ ] DevContainer has been tested locally and runs
- [ ] Codespaces run [locally and in browser]
- [ ] All tests pass

In the absence of e2e tests, 

- [ ] The application has been manually tested to work as per the requirement

## Security requirements

- [ ] Microsoft Managed Identity is implemented

When a service selected doesn't support Managed Identity, the corresponding issue must have been reported and the security considerations section in the readme, should clearly explain the alternatives.

- Azure Key Vault is a preferred alternative

### The following items are not strictly enforced but may prevent the template from being added to the gallery. 

Project code follows standard structure, [per language](https://github.com/Azure-Samples/azd-template-artifacts/tree/main/docs/structure-samples). Please check one.

- [ ] Yes, follows standards
- [ ] No, doesn't follow standards

Code follows recommended style guide

- [ ] Yes, follows style guide
- [ ] No, doesn't follow style guide
