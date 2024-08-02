# Terraform
Notes and templates for terraform

# Workspaces notes for Terraform
```shell
terraform workspace list
terraform workspace new develop <subcommand> [options] [args]
terraform apply -var-file="develop.tfvars"
terraform workspace select staging
terraform apply -var-file="testing.tfvars"
