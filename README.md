# terraform-training

Exploring Terraform tutorials

https://developer.hashicorp.com/terraform

#### Init repo
- `terraform init`
#### Format main.tf
- `terraform fmt`
#### Validate syntax of main.tf
- `terraform validate`
#### Apply changes
- `terraform apply`
    - Debug mode: `TF_LOG=debug terraform apply`
#### Show terraform managed resources
- `terraform show`
#### Destroy resources
- `terraform destroy`
#### Override variables (requires variables declared in variables.tf)
- `terraform apply -var "instance_name=YetAnotherName`
#### Output informations about the instances (requires information in output.tf)
- `terraform output`