# 002 - Security Recommendations
A variety of stacks to assist with setting up security

## Stacks
### inspector.template
#### AWS Inspector - Automated Security Assessment
To implement a basic structure for AWS Inspector including:
* Resource group containing tags for instances to be inspected
* Assessment target referencing the resource group to be used for inspection
* Assessment template uses the assessment target and performs a variety of security tests defined in parameters

#### TODO
* Automate inspections - cannot be done with Inspector CloudFormation
* SNS Topics to alert of findings - cannot be done with Inspector CloudFormation
