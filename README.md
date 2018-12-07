### Description

A project related to how to configure a terraform `random_pet` provider

### Prerequisites

- Terraform installation : [Installation process ](https://learn.hashicorp.com/terraform/getting-started/install.html)

### The repo is having following file

- main.tf : Terraform configuration file

### How to use the repo

- Clone this repo to your local machines : `git clone git@github.com:galindonkov/terraform-random-pet.git`

- Change to the currently added directory : `cd terraform-random-pet/`

- Execute `terraform init` to get terraform initialized

- Execute `terraform plan` to generate and show an execution plan based on the configured `main.tf` file

- You are now ready to proceed with the execution itself by `terraform apply` and get you new infrastructure.

  > NOTE: The command will require an execution confirmation either with `yes` or `no`.                  
   
- After you finish, you can destroy your currect infrastructure by `terraform destroy`
