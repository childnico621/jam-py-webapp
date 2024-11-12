# JAM-Py Web Application with Infrastructure as Code (IaC) using Terraform


This repository demonstrates how to deploy a JAM-Py web application with Infrastructure as Code (IaC) using Terraform. The main goal is to provide a practical example for the community to learn how to use Terraform to build and manage cloud infrastructure.

## Terraform - Infrastructure as Code (IaC)

This project includes a practical example of using Terraform to set up and manage cloud infrastructure. Terraform is an Infrastructure as Code (IaC) tool that allows you to define, deploy, and manage infrastructure across multiple providers in a declarative way.

### Prerequisites
- [Terraform](https://www.terraform.io/downloads.html) installed on your system.
- A [Cloud Provider Account](link to provider documentation) (e.g., AWS, Azure).

### Configuration
1. Clone this repository:
   ```bash
   git clone https://github.com/childnico621/jam-py-webapp
   cd jam-py-webapp/terraform
   ```

### File Structure

- **main.tf**: Defines the primary infrastructure resources, including virtual machines, networking, and storage
- **variables.tf**: Contains the customizable variables for the deployment, allowing you to adjust settings such as region, instance size, and more.
- **outputs.tf**: Specifies the output values that Terraform will display after the deployment is complete, helping you retrieve essential information like IP addresses or URLs.


### Deployment Steps
Follow these steps to initialize, plan, and apply the Terraform configuration:
```bash
terraform init
terraform plan
terraform apply
```

### Destroying the Infrastructure
When you no longer need the infrastructure, you can destroy it with the following command:
```bash
terraform destroy
```
