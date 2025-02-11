This repository is a monorepo managed with NX, specifically designed for React and React Native applications. NX helps streamline project management, code sharing, and consistent tooling across projects.

## Instructions on using this template
Node.js: Make sure you have Node.js installed (version 12.x or later).

### Setting Up the NX Monorepo

#### 1. Creating a New NX Workspace

To create a new NX workspace, run the following command in your terminal and follow the prompts:
`npx create-nx-workspace@latest`

#### Workspace Name:
Provide a name for your workspace.

#### Preset Selection:
Choose React if you're primarily working with React or React Native if it’s a React Native-focused workspace. NX will set up a workspace optimized for these frameworks.

This will initialize your NX workspace with a minimal structure, ready to add React and/or React Native projects.

#### 2. Installing Dependencies

After setting up, install the workspace dependencies:
`npm install`

#### 3. Running Applications

Run a React App:

`nx serve <your-app-name>`

Run a React Native App:

`nx run-android <your-app-name>`

`nx run-ios <your-app-name>`

NX offers a wide range of useful commands, and if you find it challenging to remember them all, you can use the NX Console extension for easy access and management.
