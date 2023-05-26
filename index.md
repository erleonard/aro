---
title: Introduction
layout: home
nav_order: 1
---

# Deploying and Integrating Azure Red Hat OpenShift

Azure Red Hat OpenShift (ARO) is a fully managed service of OpenShift on Microsoft Azure. It is jointly developed, operated, and supported by Microsoft and Red Hat. ARO provides a powerful platform for building, deploying, and scaling containerized applications using Kubernetes and other open-source technologies.

This repository is a collections of learning on how to deploy, configure and operationalize Azure Red Hat OpenShift 4.

## Modules

* Deploying Azure Red Hat OpenShift
* Configure Azure Active Directory authentication
* Configure Azure Container Registry
* Configure Azure ARC for Observibility (Azure Monitor)

The lab is available as GitHub pages [here](https://erleonard.github.io/aro-deployment/)

## Getting Started

### Prerequisites

For deploying and configure ARO you will need:

- A GitHub account
- An Azure Subscription
    - You must have sufficient permissions to deploy resources and assign RBAC
    - You must have sufficient permissions to register an application with your Azure AD tenant
- Visual Studio Code **OR** the Azure Cloud Shell

Full installation guidance and options for deploying Azure Red Hat OpenShift can be found in the [Installation]({% link install.md %}) instructions.
