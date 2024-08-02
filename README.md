# tf
Notes about terraform

# Workspaces notes for Terraform
terraform workspace list
terraform workspace new develop <subcommand> [options] [args]
terraform apply -var-file="develop.tfvars"
terraform workspace select staging
terraform apply -var-file="testing.tfvars"
