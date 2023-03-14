# Differences between tools
Terraform and CloudFormation are provisioning tools. they provision the infrastructure (servers, databases, security appliances, load balancers etc.)
Ansible, SaltStack, Chef, Puppet - configuraiton management tools

Configuration management tools are used to install and manage the software on existing servers.

Terraform can do some degree of configuration management, but its focus is provisioning.

## Two approaches to writing infrastructure as code (IaC)

### Declarative (functional) (ex. Terraform)
Describes an intended goal rather than the steps needed to reach that goal.
### Imperative (procedural)
These tools specify step by step how to achieve the desired end state.

## Ansible (RedHat)
Simplifies the provision, configuration and management of applications in the IT infrastructure.
Hybrid between th declarative and imperative approaches.

# Getting Started
## Install Terraform
https://developer.hashicorp.com/terraform/downloads
### Windows
Download the 64bit version and extract the zip.
Add the terraform binary folder to the PATH.
