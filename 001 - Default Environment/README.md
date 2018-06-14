# 001 - Default Environment
Creating a basic default environment

## Stacks
### cfarrend.solution
The parent stack, contains all necessary parameters that are passed onto child stacks and initiates the creation of the child stacks
### cfarrend-network
Creates the following:
* VPC with IGW attachment
* Subnets
  * 3 AZ private
  * 3 AZ public
* Route Tables
  * Public with public subnet associations + IGW
  * Private with private subnet associations
* Network Access Control Lists
  * Public NACL with public subnet associations
  * Private NACL with private subnet associations
