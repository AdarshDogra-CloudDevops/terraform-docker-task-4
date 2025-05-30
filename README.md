# Task 4: Infrastructure as Code (IaC) with Terraform

## Objective
Provision a local Docker container using Terraform.

## Tools Used
- Terraform
- Docker

## Steps Performed
1. Configured `main.tf` with `kreuzwerker/docker` provider.
2. Ran `terraform init`, `plan`, and `apply` to provision container.
3. Verified container using `docker ps` and `terraform state list`.
4. Cleaned up with `terraform destroy`.

## Commands Used
```bash
terraform init
terraform plan
terraform apply
docker ps
terraform state list
terraform destroy
