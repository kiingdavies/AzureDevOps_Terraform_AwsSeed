# AzureDevOps_Terraform_AwsSeed
Terraform configuration to build an S3 bucket for state storage and a DynamoDB for execution locking. 

### 1. Install the Microsoft DevLab Terraform Add-On Into Azure DevOps

### 2. Create your Local Terraform files for S3, IAM, DynamoDB

### 3. Authenticate your local AWS and apply Terraform

- Dont forget to export aws credentials to environment variables
- export AWS_ACCESS_KEY_ID="AXXXXXXX"
- export AWS_SECRET_ACCESS_KEY="XXXXXXXXXXXXXXXXXXXXXXX"
- export AWS_DEFAULT_REGION="us-east-1"

### 4. Run “terraform init” and then “terraform apply”
### 5. Upload your terraform.tfstate file in the S3 bucket

