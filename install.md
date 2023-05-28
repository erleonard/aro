---
title: Install
layout: home
nav_order: 2
---

# Installation

## Install the Azure CLI
The Azure CLI team maintains a script to run all installation commands in one step. This script is downloaded via curl and piped directly to bash to install the CLI.

*If you wish to inspect the contents of the script yourself before executing, simply download the script first using curl and inspect it in your favorite text editor.*

```console
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
```
[Reference](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt#option-1-install-with-one-command){: .btn .btn-blue }

## Install the OpenShift CLI
Install the OpenShift CLI (oc) on your local machine. The oc CLI is used to manage OpenShift resources from the command line.

```console
cd ~
wget https://mirror.openshift.com/pub/openshift-v4/clients/ocp/latest/openshift-client-linux.tar.gz

mkdir openshift
tar -zxvf openshift-client-linux.tar.gz -C openshift
echo 'export PATH=$PATH:~/openshift' >> ~/.bashrc && source ~/.bashrc
```
[Reference](https://learn.microsoft.com/en-us/azure/openshift/tutorial-connect-cluster#install-the-openshift-cli){: .btn .btn-blue }