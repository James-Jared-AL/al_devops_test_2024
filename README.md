# **DevOps Technical Assessment - Amber Labs**

Welcome to the technical assessment for the DevOps Engineer position at Amber Labs. This assessment is designed to evaluate your proficiency in managing and deploying infrastructure using AWS and Terraform. Please follow the instructions carefully and submit your work as described below.

## **Prerequisites**

Before you begin, ensure you have the following:

- A local development environment capable of running Terraform.
- AWS CLI installed and configured with appropriate access.
- A GitHub account to fork and clone the repository.

## **Getting Started**

1. **Fork the Repository**: Click the 'Fork' button at the top right of this page to create a copy of this repository under your GitHub profile.
2. **Clone Your Forked Repository**:
    
    ```bash
    git clone https://github.com/your-username/repository-name.git
    cd repository-name
    
    ```
    
3. **Create a New Branch**:
    
    ```bash
    git checkout -b feature/your-name-terraform
    
    ```
    

## **Assessment Scenario**

You are acting as a DevOps engineer within Amber Labs, tasked by a client to set up infrastructure for launching a new website.

### **Requirements**

- **Web Server**: Deploy a simple website using Nginx on an EC2 instance.
- **Networking**:
    - Create a Virtual Private Cloud (VPC) to host the infrastructure securely.
    - Set up an Internet Gateway to enable external access to the website.
    - Implement a Security Group to control both inbound and outbound traffic.
- **Storage**: Provision two S3 buckets intended for logging data.

### **Best Practices**

- Write Terraform code in a modular fashion.
- Tag all resources with:
    - Project: "Scenario"
    - Team: "Infrastructure"
    - Application: "Webserver"
- Ensure your code is well-structured and documented.

## **Submission Instructions**

1. **Commit Your Changes**:
    
    ```bash
    git add .
    git commit -m "Complete DevOps assessment tasks"
    
    ```
    
2. **Push Your Branch**:
    
    ```bash
    git push origin feature/your-name-terraform
    
    ```
    
3. **Create a Pull Request**:
    - Navigate to the 'Pull Requests' tab in the original repository.
    - Click 'New Pull Request'.
    - Set 'base' to the main branch of the original repository and 'compare' to your feature branch.
    - Fill in the details and create the pull request.

## **Follow-Up Questions**

Please prepare answers to the following questions, which may be discussed during your interview:

1. Describe the CI/CD process for creating and deploying the Docker image using GitHub Actions, including how the Terraform configurations are applied.
2. How would you implement a serverless function using AWS Lambda to automatically copy files from one S3 bucket to another upon file arrival?
3. Discuss strategies for securing files in the S3 buckets, including IAM policies, bucket policies, and encryption options.
4. If we were to containerize the website instead of using EC2, what hosting options could we consider?

Thank you for participating in our assessment. We look forward to reviewing your submission and discussing your approach and solutions during the follow-up interview.
