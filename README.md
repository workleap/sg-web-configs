# sg-web-configs
Common configurations for building web apps at ShareGate

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](./LICENSE.md) 
[![CI](https://github.com/gsoft-inc/sg-web-configs/actions/workflows/ci.yml/badge.svg)](https://github.com/gsoft-inc/sg-web-configs/actions/workflows/ci.yml)

## Usage 
  
This repo is managed as a monorepo that is composed of many npm packages, where each package has its own README and documentation describing usage.

### Packages

| Name | NPM |
| --- | --- | 
| [browserslist-config](packages/browserslist-config/README.md) | [![npm version](https://badge.fury.io/js/%40sharegate%2Fbrowserslist-config.svg)](https://badge.fury.io/js/%40sharegate%2Fbrowserslist-config) | 
| [eslint-config](packages/eslint-config/README.md)| [![npm version](https://badge.fury.io/js/%40sharegate%2Feslint-config.svg)](https://badge.fury.io/js/%40sharegate%2Feslint-config) |
| [postcss-plugin](packages/postcss-plugin/README.md) | [![npm version](https://badge.fury.io/js/%40sharegate%2Fpostcss-plugin.svg)](https://badge.fury.io/js/%40sharegate%2Fpostcss-plugin) |
| [stylelint-plugin](packages/stylelint-plugin/README.md) | [![npm version](https://badge.fury.io/js/%40sharegate%2Fstylelint-plugin.svg)](https://badge.fury.io/js/%40sharegate%2Fstylelint-plugin) |
| [typescript-configs](packages/typescript-config/README.md) | [![npm version](https://badge.fury.io/js/%40sharegate%2Ftypescript-config.svg)](https://badge.fury.io/js/%40sharegate%2Ftypescript-config) |

## Contributing

### Make changes locally

1. Fork the repository.

- Using GitHub Desktop:

  - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
  - Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)!

- Using the command line:

  - [Fork the repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository) so that you can make your changes without affecting the original project until you're ready to merge them.

- GitHub Codespaces:
  - [Fork, edit, and preview](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces/creating-a-codespace) using [GitHub Codespaces](https://github.com/features/codespaces) without having to install and run the project locally.

2. Install or update to **Node.js v16**.

4. Create a working branch and start with your changes!

### Commit your update

Commit the changes once you are happy with them.

### Pull Request

When you're finished with the changes, create a pull request, also known as a PR.

- Run `npm run changeset` and follow the steps to generate a changeset file (that needs to be committed with your PR).
- Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.

Once you submit your PR, a GSoft team member will review your proposal. We may ask questions or request for additional information.

- We may ask for changes to be made before a PR can be merged, either using suggested changes or pull request comments. You can apply suggested changes directly through the UI. You can make any other changes in your fork, then commit them to your branch.
- As you update your PR and apply changes, mark each conversation as resolved.
- If you run into any merge issues, checkout this git tutorial to help you resolve merge conflicts and other issues.

## License

Copyright © 2023, GSoft inc. This code is licensed under the Apache License, Version 2.0. You may obtain a copy of this license at https://github.com/gsoft-inc/gsoft-license/blob/master/LICENSE.
