# Extension Template

This is a template to start development of a new extension.

It is mandatory to use [npm](https://www.npmjs.com/) as a package manager.

Magento version - 2.4.3  
ScandiPWA version - 6.0.2

Extension template is located in [./pwa/packages](./pwa/packages) directory.

## VSCode


### Workspace

Open this project as workspace.

**File > Open Workspace from File...** then select `PWA.code-workspace` file and click **Open**.

Or, from terminal execute:

```bash
code ./PWA.code-workspace
```

### Extensions

Make sure to install all extensions that editor will ask you install.

Recommended extensions are located in [./.vscode/extensions.json](./.vscode/extensions.json) file.

## Magento installation

To install Magento we are using [Create Magento App]() project.

Run the following commands to install and run your Magento:
```bash
# install cma dependencies
npm ci

# star the application
npm run start
```

## ScandiPWA installation

To install ScandiPWA run the following commands:
```bash
# go to scandipwa directory
cd ./pwa

# install dependencies
npm ci
```

To run ScandiPWA in development mode run the following command:
```bash
BUILD_MODE=magento npm run start
```
