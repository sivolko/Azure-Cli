# Azure-Cli
This is Azure CLI 101 Documentation | Cheatsheet

## Definition :

The Azure Cli aka Azure command line interface is Microsoft's cross platform command-line experience for managing Azure resources.

## Why do we want it ?

Azure CLI can be used for 
* Day to day operations
* Automation of repetitive tasks
* Scheduling
* Deployments
* Devops
* Learning
* Achieving things that are hard otherwise

## Features: 
* Easy to start with, but ppowerfuul enough to build devops
* Interactive mode
* Multiple output formats
* Querying with JMESPath
* Combines multiple commands in single one
* Flexible with extensions
* Cross plarform works with windows, macOs, Linux
* Works in cloudShell

  ### Commands:

  Let's start with the basic command to list down the all the resource

  1. az -h : for help
  2. az login : to login the azure portal
  3. az group -h : to get help regarding group

  ## [official MS cheatsheet](https://learn.microsoft.com/en-us/cli/azure/reference-index?view=azure-cli-latest)

  ## To create a Resource Group

  az group create --name <WhateverResourceGroupName> --location westindia

  ## Azure Command to Delete Resource Group

  az group delete --resource-group <NameofResourceGroup>


