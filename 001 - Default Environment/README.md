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
