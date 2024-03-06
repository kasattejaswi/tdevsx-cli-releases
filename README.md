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

Once downloaded, move under a specific folder at any location. Copy this location as you need it for next step.

> This CLI maybe considered as virus from windows and apple based systems. Reason is, this CLI executes multiple commands related to exercises on shell to validate the solutions due to which anti viruses may show them as false positives. In case you face such issue, please whitelist this CLI in your anti-virus software.

## Step 2: Setup path
Copy the path of the location where you have downloaded the CLI binary. Different operating systems have different ways to set a path. You can follow below guides to setup path:

| OS | Guide |
| ------ | ------ |
| Windows | [Guide](https://www.computerhope.com/issues/ch000549.htm) |
| MacOS | [Guide](https://www.cyberciti.biz/faq/appleosx-bash-unix-change-set-path-environment-variable/) |
| Linux | [Guide](https://opensource.com/article/17/6/set-path-linux) |

## Step 3: Test CLI installation

If you are using Linux or Macos, run below command to modify CLI permissions:
```bash
chmod +x /path/to/tdevsx
```

If you are using MacOS, run below command before testing CLI to allow execution:
```bash
xattr -d com.apple.quarantine /path/to/tdevsx
```

To test the CLI, open a new terminal on you system and run below command:
```bash
tdevsx version
```
It should produce a version successfully.


