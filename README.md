# 3-tier-ha-architecture-on-aws-using-terraform
Terraform code to create highly available 3 tier architecture on aws 

## Usage
1. Clone this repo to your AWS CLI shell.
2. Perform the following terraform sequence to deploy the resources

```shell

terraform init
# This should be run at the beginning of every project and after any changes to the provider dependencies

terraform validate
# This command checks the syntax and configuration of your Terraform files. It ensures that your code is valid and follows the correct structure.  Run this early and often to catch errors before they become more difficult to fix.

terraform fmt
# Optional but recommended - This command formats your Terraform code to adhere to a consistent style.

tflint
# Optional but recommended - linting tool for static analysis of Terraform code, They can help you catch problems that Terraform validate might miss

terraform plan
# This is the most important command.  It creates an execution plan on what will be changed

terraform apply
# This command applies the changes outlined in the execution plan

```
