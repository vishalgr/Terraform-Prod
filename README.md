terraform-aws-infra/
│── modules/
│   ├── vpc/
│   │   ├── main.tf          # Main configuration for VPC
│   │   ├── variables.tf     # Input variables for VPC module
│   │   ├── outputs.tf       # Outputs from VPC module
│   │   ├── providers.tf     # Provider configuration for VPC module
│   │   ├── README.md        # Documentation for VPC module
│   ├── ec2/
│   │   ├── main.tf          # Main configuration for EC2
│   │   ├── variables.tf     # Input variables for EC2 module
│   │   ├── outputs.tf       # Outputs from EC2 module
│   │   ├── providers.tf     # Provider configuration for EC2 module
│   │   ├── README.md        # Documentation for EC2 module
│   ├── rds/
│   │   ├── main.tf          # Main configuration for RDS
│   │   ├── variables.tf     # Input variables for RDS module
│   │   ├── outputs.tf       # Outputs from RDS module
│   │   ├── providers.tf     # Provider configuration for RDS module
│   │   ├── README.md        # Documentation for RDS module
│   ├── s3/
│   │   ├── main.tf          # Main configuration for S3
│   │   ├── variables.tf     # Input variables for S3 module
│   │   ├── outputs.tf       # Outputs from S3 module
│   │   ├── providers.tf     # Provider configuration for S3 module
│   │   ├── README.md        # Documentation for S3 module
│   ├── alb/
│   │   ├── main.tf          # Main configuration for ALB
│   │   ├── variables.tf     # Input variables for ALB module
│   │   ├── outputs.tf       # Outputs from ALB module
│   │   ├── providers.tf     # Provider configuration for ALB module
│   │   ├── README.md        # Documentation for ALB module
│
│── environments/
│   ├── dev/
│   │   ├── main.tf          # Main configuration for development environment
│   │   ├── backend.tf       # Backend configuration for state management in dev
│   │   ├── variables.tf     # Input variables for dev environment
│   │   ├── outputs.tf       # Outputs from dev environment
│   ├── staging/
│   │   ├── main.tf          # Main configuration for staging environment
│   │   ├── backend.tf       # Backend configuration for state management in staging
│   │   ├── variables.tf     # Input variables for staging environment
│   │   ├── outputs.tf       # Outputs from staging environment
│   ├── production/
│   │   ├── main.tf          # Main configuration for production environment
│   │   ├── backend.tf       # Backend configuration for state management in production
│   │   ├── variables.tf     # Input variables for production environment
│   │   ├── outputs.tf       # Outputs from production environment 
│ 
│── global/
│   ├── providers.tf         # Global provider configurations 
│   ├── versions.tf          # Terraform version constraints 
│   ├── variables.tf         # Global input variables 
│   ├── outputs.tf           # Global outputs 
| 
|   ├─ scripts/              # Utility scripts 
|   ├─ init.sh               # Script to initialize the infrastructure 
|   ├─ destroy.sh            # Script to destroy the infrastructure 
| 
|   ├─ .gitignore            # Git ignore file 
|   ├─ README.md             # Project documentation 
|   ├─ terraform.tfvars      # Terraform variable definitions 
|   ├─ versions.tf           # Terraform version constraints 
|   └─ terragrunt.hcl        # Terragrunt configuration (if using Terragrunt) 
