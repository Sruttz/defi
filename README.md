# DEFI-network(STR)

This project provides an overview about the creation of avalanche subnet and deploying the contract to that subnet along with interacting with it.

## Description

In my project, there's a smart contract that I deployed to the subnet that i created and deployed on the local network. The smart contract contains basic functionalities which uses an interface IERC20 which we will be deploying and interacting with in my loom video.

 ## Getting Started

 ## Installation

### Compatibility

The tool has been tested on Linux and Mac. Windows is currently not supported.

### Instructions

To download a binary for the latest release, run:

```sh
curl -sSfL https://raw.githubusercontent.com/ava-labs/avalanche-cli/main/scripts/install.sh | sh -s
```

The binary will be installed inside the `~/bin` directory.

To add the binary to your path, run

```sh
export PATH=~/bin:$PATH
```

To add it to your path permanently, add an export command to your shell initialization script (ex: .bashrc).

### Quickstart

After installing, launch your own custom subnet:

```bash
avalanche subnet create <subnetName>
avalanche subnet deploy <subnetName>
```

Shut down your local deployment with:

```bash
avalanche network stop
```

Restart your local deployment (from where you left off) with:

```bash
avalanche network start
```

After connecting the network to metamask , you can get test tokens by importing an account with the private key provided wehn deployed. 

Then , you can change the environment on remix to injected provider and connect your metamsk 
 
 
 ## Authors
 
 Sruthika S
 
 [@sruthikaaas@gmail.com]
 
 ## License
 
 This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
