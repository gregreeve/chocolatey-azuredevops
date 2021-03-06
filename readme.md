# Chocolatey Azure DevOps Tasks

This extension brings support for [Chocolatey](https://chocolatey.org/) to Azure DevOps.

## Table of Contents

1. [What is Chocolatey?](#what-is-chocolatey)
1. [Tasks](#tasks)
1. [Resources](#resources)
1. [Documentation](#documentation)
1. [Thanks](#thanks)
1. [Contributing](#contributing)
1. [Releases](#releases)

## What is Chocolatey?

Chocolatey is a Package Manager for Windows, which allows the automation of all your software needs.

For more information about [Chocolatey](https://chocolatey.org/), please see the Chocolatey Website or the Chocolatey [source code repository](https://github.com/chocolatey/choco).


## Tasks

This extension contains only a single Task, which is capable of executing the following Chocolatey Commands:

**NOTE:** This Azure DevOps Task assumes that Chocolatey is already installed on the Build Agent that is running the build.  If Chocolatey is not located on the Build Agent, an error will be thrown, and the task will fail.

* apikey
* config
* custom
* feature
* install
* pack
* push
* source
* upgrade

## Resources

Short YouTube videos of each of the releases of this extension can be found in this [playlist](https://www.youtube.com/playlist?list=PL84yg23i9GBhGahFf5-41vOJhn3D-6EUU).

## Documentation

You can find the documentation that is available for this project [here](https://chocolatey-community.github.io/chocolatey-azuredevops/).

## Thanks

The Chocolatey Azure DevOps Extension is modelled on the NuGet Extension, and many of the ideas in terms of how it functions, is based on how it works.

## Contributing

If you would like to see any other tasks or features added for this Azure DevOps Extension, feel free to raise an [issue](https://github.com/chocolatey-community/chocolatey-azuredevops/issues), and if possible, a follow up pull request.

You can also join in the Gitter Chat [![Join the chat at https://gitter.im/chocolatey-community/community](https://badges.gitter.im/chocolatey-community/community.svg)](https://gitter.im/chocolatey-community/community)

## Releases

To find out what was released in each version of this extension, check out the [releases](https://github.com/chocolatey-community/chocolatey-azuredevops/releases) page.
