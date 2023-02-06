# What we do in the shadows (of devops)
A demo repository that demonstrates how to automate both your software defined infrastructure/services and application deployments

Teams that create/manage the automation of Software Defined Infrastructure and Application Deployments go by many names:
- Site Reliability Engineers
- Cloud Platform Engineers/Developers
- DevOps Engineers

A rose by any other name, is still automated shell scripts.  Often tasks done in the shadows of most organizations.

We'll attempt to compose some baseline considerations/samples as a starting point for your software defined environment. We will also curate a number of optional labs that build upon the baseline environment.


## Phase 1 (0-6 Months)

Todo:
- Content around Bicep/Azure CLI and potentially Terraform
    - How to use Declarative and Procedural tools to:
        - provision infrastrucutre in a given Provider/Platform/Substrate
        - deploy appliactions to infrastructure

## Phase 2 (+6 Months)
- Describe the common required components for each type of Application
    - Undifferntiated heavy lifting/Non-Functional Requirements
- Converge on one stack of opinionated tooling
- Show what the potential escape hatches are for exemptions/exceptions (team X wants to use a diffeernt CI tool)

### Undifferentiated heavy lifting/Non-Functional Requirements
- Source control
    - GitHub
    - Azure DevOps Repos
- CI Tooling
    - GitHub Actions
    - Azure DevOps Pipelines
- Package/Artifact Management
    - Software Package Repositories [NPM, Nuget, Ruby Gems, Maven etc.] 
    - Container Registry
- Code Analysis/Scanning


## Phase 3 (+6 Months)
- Extend from public "multi-cloud" back to on-prem "hybrid-cloud"