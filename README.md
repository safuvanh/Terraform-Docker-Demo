# Terraform-Docker-Nginx Demo

This project demonstrates how to use Terraform to manage Docker containers and images, specifically focusing on deploying an Nginx web server using Docker.

## Prerequisites

Before you begin, ensure you have the following installed:

- Terraform
- Docker
  
## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/safuvanh/Terraform-Docker-Demo.git
    ```

2. Change into the project directory:

    ```bash
    cd Terraform-Docker-Demo
    ```

3. Initialize Terraform:

    ```bash
    terraform init
    ```

4. Apply the Terraform configuration:

    ```bash
    terraform apply
    ```

    Terraform will prompt you to confirm the execution plan. Type `yes` and hit Enter.

5. Once the Terraform apply completes successfully, you should have an Nginx container running locally.


 ![Screenshot (156)](https://github.com/safuvanh/Terraform-Docker-Demo/assets/156053146/45c461b5-060a-494a-ae0c-51cc89c250d1)

 
## Usage

- To make changes to the Docker container configuration, modify the `main.tf` file.
- After making changes, reapply the Terraform configuration:

    ```bash
    terraform apply
    ```

- To destroy the Docker container and cleanup resources:

    ```bash
    terraform destroy
    ```

    Again, Terraform will prompt you to confirm the destruction. Type `yes` and hit Enter.

## Additional Notes

- Ensure you have Docker running on your system before applying Terraform configurations.
- For more information on Terraform, refer to the [Terraform documentation](https://www.terraform.io/docs/index.html).
- For more information on Docker, refer to the [Docker documentation](https://docs.docker.com/).
  

