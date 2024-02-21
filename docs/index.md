# NexuShell Documentation

![NexuShell logo](https://cdn.jsdelivr.net/gh/steviecoaster/NexuShell@develop/logo/nexushell.svg)

You've found the online documentation for [NexuShell](https://github.com/steviecoaster/NexuShell)!

NexuShell is a PowerShell module for the [Sonatype Nexus Repository Server](https://www.sonatype.com/products/repository-oss) API. Each function inside of the module links back to its corresponding page here on the docs site.

## What is Sonatype Nexus

Sonatype Nexus is a Repository Server that exists in two flavors. Open Source (Sonatype Nexus OSS), and Pro (Sonatype Nexus Pro). The open-source version of Sonatype Nexus is extremely feature rich, providing you _almost_ all of the functionality of the Pro edition. It only lacks things like Azure Blob Storage availability for use in Blob Stores, High Availability, and Blob Store migrations, and a Support contract.

## Functionality

- Manage Repositories 🚧 WIP, partially implemented
- Manage Assets
- Manage Components
- Manage Content Selectors
- Manage Anonymous Access
- Manage Licensing
- Manage Email configuration
- Manage Blob Stores
- Manage Routing Rules
- Manage Cleanup Policies
- Manage Scripts
- Manage Roles
- Manage Privileges
- Manage Users
- Manage Tasks
- Manage Tags
- Search Nexus 🚧 Coming Soon!
- Collect Support information

## Building

To build this project from source, follow these steps:

1. Clone this repo and run `.\build.ps1 -Build` from the cloned folder
2. Import the module with `Import-Module .\Output\NexuShell\NexuShell.psd1` from the cloned folder
3. Discover the available commands with `Get-Command -Module NexuShell`
4. Explore the available commands with `Get-Help`
5. Start having fun!

Once I have complete API coverage I'll publish this to the Gallery, and from there you'll be able to do `Install-Module NexuShell`, `Update-Module NexuShell` etc

## Installation

You can install this module a couple of ways:

- PowerShell Gallery: `Install-Module NexuShell -Force`
- Chocolatey: `choco install nexushell -y -s https://community.chocolatey.org/api/v2`
- 
## Contributing

This is an Open Source project. If you spot a bug, or a feature that is missing file an [issue](https://github.com/steviecoaster/NexuShell/issues/new)! You're also welcome to file a Pull Request with your changes. When filing issues please ensure to include as much information as possible to make troubleshooting easier. Things like Operating System, PowerShell Version, Nexus Version, and any error output you receive while running a command are extremely helpful.

Also, this is an open repository in which you encounter folks from many walks of life. Language is hard, but please try to keep conversations civil and inclusive. Foul language and extreme anger in comments will not be tolerated.