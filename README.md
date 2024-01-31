# Salesforce Metadata Analaysis
This repository contains several Jupyter notebooks that will generate lists of metadata related to record-based automations, or database triggers, including Flows, Workflow Rules and Apex triggers.

## Prerequisites
1. Jupyter running locally, either by downloading the [official Jupyter software](https://docs.jupyter.org/en/latest/install.html) or and IDE, such as [VS Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter).

1. Salesforce source code downloaded locally. If you don't already have a project with source code locally, the easiest way to get the source code is to use the [Org Browser feature of the Salesforce extensions for VS Code](https://developer.salesforce.com/tools/vscode/en/sf-dev-env/org-browser) to connect to an org and sync the metadata locally.

## Running the Notebooks
Each of the notebooks includes variable called "directory_path" that needs to be updated to the path for the relevant metadata on your local machine.

Note that the flows-list notebook has two directory variables.