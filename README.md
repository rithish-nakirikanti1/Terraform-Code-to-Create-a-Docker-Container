TASK 3: Provisioning Docker Container using Terraform
Objective:
Use Terraform to provision an NGINX Docker container on the local system.

Tools Used:
- Terraform
- Docker

Steps:
1. Initialized Terraform.
2. Pulled nginx Docker image using Terraform.
3. Created container with exposed port 8080.
4. Verified container is running with `docker ps`.
5. Destroyed the setup using `terraform destroy`.

 Commands Used:
```bash
terraform init
terraform plan
terraform apply
terraform destroy
