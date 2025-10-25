## Provision a Local Docker Container Using Terraform[IAC] 
## Tools and Technologies
- Docker
- Terraform
- Github
- Terminal

## Steps
1. Create a Project Folder
   - example: Iac-Task
2. Write the Terraform Configuration
   - Create a main.tf and define waht resoucres you need 
## Commands to use After Writing main.tf File
- terraform init [ for initialization]
- terraform plan [its like a dry run before applying the code,its like it shows what resouces are going to create]
- terraform apply [it will create the resources what you defined in the main.tf file]
- terraform destroy [Delete all resources created by Terraform]
- terraform state :
Terraform state is a file which keeps track of your infrastructure's current state.
It is utilized to monitor resources, identify changes, and accurately plan updates.
State enables Terraform to safely manage, update, or destroy resources.

## Author
Abhishek Dindawar


