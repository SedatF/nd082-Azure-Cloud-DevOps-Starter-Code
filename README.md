# Azure Infrastructure Operations Project: Deploying a scalable IaaS web server in Azure

## Introduction

Infrastructure as code gives us a huge advantage in defining, deploying, updating and destroying our infrastructure. Therefore, we will use packer to create virtual machine images (in JSON format) to create an image containing our application for repeatable deployments.

## Getting Started

1. Clone this repository
2. Create your infrastructure as code
3. Create your tagging-policy in Azure
4. Create your resource group in Azure

## Dependencies

1. Create an [Azure Account](https://portal.azure.com) 
2. Install the [Azure command line interface](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
3. Install [Packer](https://www.packer.io/downloads)
4. Install [Terraform](https://www.terraform.io/downloads.html)


## Instructions

Deploy the scalable web server in Azure we need: 

1. Deploy the packer image
2. Deploy the infrastructure with Terraform template

### :pushpin: Deploy the Packer Image

Packer is a server templating software. It will deploy virtual machines images. 

> In main.tf: The az availability set, platform_fault_domain_count = 2 has default value 5, so we need to specify it to 2.
Run the following commands to deploy the infrastructure.

## Output

If you succeeded in deploying the resources, it will looks like below


