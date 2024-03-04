# tdevsx-cli-releases

This repository contains the public releases of tdevsx cli including plugins and main cli.

# Getting started

Setting up tdevsx CLI is easy and involves three simple steps:

## Step 1: Download relevant binaries
Download relevant binaries based on your system OS and architecture

| OS | AMD64 | ARM64 |
| ------ | ------ | ------ |
| Windows | [Click here](https://github.com/kasattejaswi/tdevsx-cli-releases/raw/main/tdevsx-windows-amd64/tdevsx.exe) | Not Available |
| MacOS | [Click here](https://github.com/kasattejaswi/tdevsx-cli-releases/raw/main/tdevsx-darwin-amd64/tdevsx) | [Click here](https://github.com/kasattejaswi/tdevsx-cli-releases/raw/main/tdevsx-darwin-arm64/tdevsx) |
| Linux | [Click here](https://github.com/kasattejaswi/tdevsx-cli-releases/raw/main/tdevsx-linux-amd64/tdevsx) | [Click here](https://github.com/kasattejaswi/tdevsx-cli-releases/raw/main/tdevsx-linux-arm64/tdevsx) |

Once downloaded, move under a specific folder at any location.

## Step 2: Setup path
Different operating systems have different ways to set a path. Follow below guides for each operating system:

### Setting the PATH Environment Variable in Windows

The PATH is the system variable that your operating system uses to locate needed executables from the command line or Terminal window.

##### Adding a Path

1. Right-click on 'Computer' icon and choose 'Properties'.
2. Click on 'Advanced System Settings'.
3. In the System Properties window, click on the 'Environment Variables' button.

   ![Environment Variables](https://i.imgur.com/SSKmMBt.png)

4. In the Environment Variables window, highlight the 'Path' variable in the 'System variables' section and click the 'Edit' button.

   ![Edit Path](https://i.imgur.com/5q7H0K8.png)

5. In the Edit System Variable window, add your desired path to the end of the 'Variable value', preceded by a semi-colon (`;`). For example, if the value was `C:\Windows\System32`, and you want to add `C:\MyPath`, the new value should be `C:\Windows\System32;C:\MyPath`.

   ![Add Path](https://i.imgur.com/5q7H0K8.png)

6. Click 'OK' to close each window.

#### Verifying the New Path

You can verify that the new path has been added by opening a new command prompt window (old command prompt windows will not have the updated path) and typing:

```cmd
tdevsx
```
