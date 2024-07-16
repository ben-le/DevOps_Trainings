## Step-by-Step Guide to Learning Terraform

### 1. Understand the Basics of Infrastructure as Code (IaC)
Before diving into Terraform, it's essential to understand the concept of IaC, which allows you to manage and provision infrastructure through code instead of manual processes.

### 2. Install Terraform
- #### On macOS:
  brew install terraform

- #### on Linux:
  sudo apt-get update && sudo apt-get install -y gnupg software-properties-common curl
  curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
  sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
  sudo apt-get update && sudo apt-get install terraform

