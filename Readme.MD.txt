# Task 3: Infrastructure as Code (IaC) with Terraform

## Objective

Provision a local Docker container using Terraform.

## Tools Used

- Terraform
- Docker
- Nginx
- GitHub

## What I Did

1. Created a Terraform configuration file (`main.tf`).
2. Configured the Docker provider.
3. Created an Nginx Docker image using Terraform.
4. Created an Nginx Docker container using Terraform.
5. Ran `terraform init`.
6. Ran `terraform plan`.
7. Ran `terraform apply`.
8. Verified the Nginx container using a web browser.
9. Checked Terraform state using `terraform state list`.
10. Destroyed the resources using `terraform destroy`.

## Terraform Commands

```text
terraform init
terraform plan
terraform apply
terraform state list
terraform destroy