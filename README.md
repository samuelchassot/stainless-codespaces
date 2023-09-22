# Stainless-codespaces

This repository is a template for creating a [Stainless](https://stainless-steel.github.io/) project in a GitHub Codespace.

To use this template, fork it and then create a new codespace from it. To do so:

- go to github.com
- on the top right corner, click on your profile picture
- go to "Your codespaces"
- click on "New codespace"
- select this repository in the "Repository" dropdown
- select the configuration you want to use from the "Dev container configuration" dropdown
  - the "Stainless Dockerfile" configuration will use the provided Dockerfile to build the container, installing the latest version of Stainless in the process. This might take some time
  - the "Stainless Docker Image" configuration will use the provided Docker image, which already contains Stainless. This is faster, but you cannot update the Dockerfile to customise the image.
- select the machine type you need in the "Machine type" dropdown
- click on "Create codespace"
- wait for the codespace to be created
- you can now access your codespace by either:
  - working in the browser, in the tab that just opened
  - opening VS Code on your computer and connecting to the codespace from there, by clicking on the botton left corner button, selecting "Connect to a codespace", and selecting the codespace that was just created.