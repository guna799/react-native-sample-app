# Sample React Native App

This repo is for testing `react-native-version` GitHub action.

## Workflow

Checkout the workflow in `.github/workflows/versioning.yml`.

Before using `react-native-version` action, you need to run the following actions:

- `actions/checkout@v3` - To checkout latest code from your repository.
- `actions/setup-node@v3` - To setup node version (whatever you are using).
- `npm install -g yarn` - Install yarn using npm (skip this step, if you are using npm).
- `yarn ci` - Install node_modules
- `nabeel-shakeel/react-native-version@main` - Using react-native-version for version bump and GitHub release
