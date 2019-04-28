![React Workspaces Playground Screenshots](https://i.imgur.com/viD4fzR.png)

## Features

- ⚛️ Create React App 3 (React 16.8)
- 📖 Storybook 5
- 🐱 Yarn Workspaces
- 🐉 Lerna 3
- 👨‍🔬 Tests: Eslint & Jest
- ✨ Host Multiple, CRA Apps, Component Libraries & Storybooks in one Monorepo
- 🔥 Hot Reloading of all Apps, Components & Storybooks

## Setup

### Pre-Requisites

- Yarn 1.13.0
- Node 11.14.0

### Installation

```bash
git clone git@github.com:react-workspaces/cra-workspaces-playground
cd cra-workspaces-playground
yarn
```

## Usage

### Starting The React App

```bash
cd packages/apps/app-one
yarn start
```

### Starting The Storybook

```bash
cd packages/storybook
yarn storybook
```

### Linting & Testing

```bash
cd <workspace-root>
yarn test
```

### Creating a New CRA App

Use Create React App's `--scripts-version` to create a new React App with Yarn Workspaces support.

```bash
create-react-app --scripts-version @react-workspaces/react-scripts my-app
```
