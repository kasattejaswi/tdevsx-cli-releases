# tdevsx-cli-releases

This repository contains the public releases of tdevsx cli including plugins and main cli.

# Directory structure

At root, there is a main CLI with version information available. This CLI will be published for different operating systems and architectures.

Under plugins, the plugins for different exercises will be published. These plugins will be pulled automatically based on operating system and system architecture by the main CLI. Update checks are automated and will be checked by main CLI on every execution. If a plugin with new version is available, it will be auto downloaded in user's home directory.

# Installation steps
