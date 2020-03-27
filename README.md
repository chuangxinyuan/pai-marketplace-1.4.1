# openpaimarketplace

![Webportal Plugin CI](https://github.com/microsoft/openpaimarketplace/workflows/Webportal%20Plugin%20CI/badge.svg?branch=master)
![Rest Server CI](https://github.com/microsoft/openpaimarketplace/workflows/Rest%20Server%20CI/badge.svg?branch=master)

A marketplace which stores examples and job templates of openpai. Users could use openpaimarketplace to share their jobs or run-and-learn others' sharing job.

## Components

There are two components of openpaimarketplace, [rest server](./rest_server/README.md) and [webportal plugin](./webportal_plugin/README.md), which are responsible for backend service and frontend usage seperately. Please could check the two folders for more detail.

## Get started

- [start rest server](./rest_server/README.md)

- [start webportal plugin](./webportal_plugin/README.md)

- configure in pai webportal

  When deploy pai webportal, configure marketplace webportal plugin in advance, then the marketplace could be used through pai webportal. For more detail, please refer to [webportal configuration doc](https://github.com/microsoft/pai/blob/master/docs/webportal/PLUGINS.md)

## Code style check of webportal

This project use eslint with standard config as linter and prettier as code formatter.

Pleae refer to eslint config file and prettier config file for details. Make sure to run yarn lint command every time before you push your code, and resolve all the errors and warnings. Otherwise it will break the CI check when you submit your pull request.

If you use modern editors like VS Code. It is highly recommends to install eslint and prettier extensions.

    How to do code format with prettier? You could use cli like prettier --write 'src/**/*.js' 'src/**/*.jsx' or use prettier extension in vscode.

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit <https://cla.opensource.microsoft.com>.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
