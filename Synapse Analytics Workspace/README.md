# Synapse Analytics Repository Template

This repository template provides a structured approach for managing your Azure Synapse Analytics workspace using Git and Azure DevOps for Continuous Integration and Continuous Deployment (CI/CD). The following example outlines what you can expect when setting up your repository.

## Purpose

This `README.md` serves as an example to guide you in setting up the root folder for your Synapse Analytics Git repository. It outlines the expected structure and provides basic instructions for integrating CI/CD processes.

## Example Repository Structure

Here is an example of how you might organize your Synapse Analytics repository:

Root
├── Synapse Analytics Workspace
│ ├── datasets
│ ├── linkedServices
│ ├── notebooks
│ ├── pipelines
│ ├── sparkJobDefinitions
│ ├── sqlScript
│ ├── triggers
│ └── workspace.json

### Synapse Analytics Workspace

This directory contains all the Synapse workspace artifacts:

- `datasets`: Definitions of datasets used in your workspace.
- `linkedServices`: Configuration of linked services.
- `notebooks`: Jupyter notebooks for data analysis.
- `pipelines`: Data pipelines definitions.
- `sparkJobDefinitions`: Definitions for Spark jobs.
- `sqlScript`: SQL scripts used in your workspace.
- `triggers`: Trigger configurations.
- `workspace.json`: Main configuration file for the Synapse workspace.

### 1. Link Synapse Workspace to a Git Repository

1. Navigate to your Synapse workspace in the Azure portal.
2. Select 'Manage' and then 'Git Configuration'.
3. Configure the Git settings by linking your Azure DevOps or GitHub repository.

### 2. Set Up CI/CD in Azure DevOps

See the [blog]().
