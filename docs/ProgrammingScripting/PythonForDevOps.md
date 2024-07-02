## Python For DevOps: Guide for DevOps Engineers

### Python for DevOps

In this blog, I will discuss why you need Python for DevOps and its real-world use cases. Also, I have added the resources and roadmap to learn Python for a DevOps engineer.

Programming is becoming an essential skill for DevOps engineers. It doesn’t mean DevOps engineers have to develop full-fledged applications like developers. The development use case is different for DevOps engineers.

In my DevOps engineers guide, I have written about the importance of programming & Scripting for Devops engineers.

### Python For DevOps

When it comes to DevOps, Python is the preferred programming language for automation.

The latest Python Developers Survey conducted by JetBrains shows that 38% of Python usage is reported for DevOps, Automation, and System Administration.

![Python for DevOps Survey](link-to-survey-image)

Now let’s look at Python’s different use cases for DevOps.

1. **CI/CD, Infrastructure provisioning & Configuration Management**
   - Many open-source tools are available for infrastructure provisioning, configuration management, continuous integration, continuous deployment, etc. However, there are scenarios where the native tooling functionality might not be sufficient to implement the required functionality. Here is where languages like Python come in to picture. For example,
     - Making an API call to get a secret token while deploying.
     - Reading a CSV file to get specific data during application deployments.
     - In Ansible, you can create custom modules using Python when no module is available for the implementation you are looking for.

2. **DevOps Platform Tooling**
   - In most organizations, as part of platform engineering efforts, central DevOps platform teams develop the in-house platform and tooling for internal teams. While developing these platforms, DevOps engineers need to work with programming languages and scripting languages to build utilities and scripts for platform automation requirements.

3. **Cloud Automation**
   - Boto3 is an excellent example of Python usage for Cloud Automation. It is an extensively used python module for AWS cloud-related automation and scripts. As a DevOps engineer, you might also have to develop lambda functions in Python for infrastructure-related tasks.

4. **Monitoring & Alerting**
   - Even though every organization has monitoring tools, there are use cases where you need a customized solution for monitoring and alerting. You can use the relevant Python SDKs or custom modules to implement the solution in such cases.
     - For example, a custom autoscaler based on alerts where a webhook listens to incoming alerts to take scaling decisions. You can automate the whole autoscaling process using a simple Python Flask application.

5. **MLOPS**
   - Another area where Python is extensively used is MLOPS (Machine Learning Operations). When DevOps engineers work with ML application development teams, most workflows require Python. For example, Airflow tool is a standard ML & data engineering pipeline tool. In most cases, DevOps engineers are responsible for creating these pipelines in collaboration with ML and Data engineers. However, there are complex use cases where the involvement of data engineers is required.

### Python Learning Roadmap For DevOps Engineers

If you are starting your DevOps engineer journey and want to learn Python, the question you might have is, how much Python is required for DevOps?

Here is a Python learning roadmap for DevOps Engineers with the relevant resources.

- Python environment setup
- Basic syntax
- Variables
- Python Data Types
- Conditionals
- Loops
- Regular expressions.
- Methods
- Modules
- Exception handling
- Utilizing Python cloud SDKs (Boto3)

Once you learn the above concepts, you can start with hands-on Python scripting on the real-world use cases listed in the next section.

If you are looking for a guided way to learn Python from scratch., I recommend the following free Python resources.

- [Learn Python 3 from Scratch](link-to-learn-python-course)
- [Introduction to Python Programming](link-to-intro-python-course)
- [Python for Beginners – Full Course](link-to-python-beginners-course)

### Important Python Modules for DevOps Automation

There are a lot of Python modules for various use cases. However, when it comes to DevOps, there are Python devops libraries that you will have to use repeatedly for automation tasks.

Here is the list.

- os module
- platform
- subprocess
- sys
- psutil
- re (Regular Expression)
- scapy
- Requests and urllib3
- logging
- getpass
- boto3
- paramiko
- JSON
- PyYAML
- pandas: One of the best data science frameworks. However, it is very useful for DevOps automation tasks dealing with CSV files.
- smtplib

### Real World Python Automation Use Cases For DevOps

Now let’s take a look at some of the real-world use cases of Python scripting in DevOps. I have added the use cases under different categories.

#### Generic Python DevOps Use Cases

- Python Script to query databases
- Python script to execute a shell script and shell commands.
- Querying Splunk logs for specific alerting
- Python script to create Kafka Topics
- Python script to take backups.
- Python script for Kubernetes init containers to fetch secrets from the vault or other secrets management solutions.
- Python script to fetch IPs of live servers in an autoscaling group.
- Python AWS Lambda function to stop running instances on weekends.
- Python script for ETL jobs.
- Find SSL expiry date using python
- Develop custom CLI applications using Python
- CRUD operations using Python for databases.
- Custom scripts while using configuration management tools.

#### Cloud-Specific Python Use Cases

When working on cloud environments, you might need custom automation scripts as part of Infrastructure as code implementations. Let’s take a look at some real-world cloud-specific Python use cases.

- Provision AWS resources using Python AWS CDK.
- Use Boto3 modules to manage AWS services.
- Python Boto3 program to manage AWS ec2 instances.
- Python Boto3 program to manage AWS S3 Storage.
- Python Boto3 program to retrieve secrets from parameter store and secrets manager.

#### Kubernetes-Specific Python Use Cases

Many devops engineers had this question of how to leverage Python knowledge with Kubernetes.

Following are the tasks you can do with Python for while learning Kubernetes

- Start by creating Python programs to interact with Kubernetes APIs using various authentication mechanisms. (Token, Certificates, etc)
- Try running custom Python scripts with init containers to modify a file that a container requires during runtime.
- Write a custom webhook using Python Flask API for Kubernetes Validating and Mutating Admission controllers.
- Consider writing a Kubernetes operator in Python using the Kopf framework. An example use case for a custom Kubernetes operator could be to automate the backup of etcd to Amazon S3. You can use the kopf python framework.

### Python For DevOps GitHub Repo

I have created a GitHub repository where DevOps-related Python scripts and programs will be added for learning and implementation. The repo primarily focuses on generic Python scripts, boto3, OS-related Python scripts, and more. It is an open-source repo that will accept community contributions.

Repo: [Python for DevOps Scripts](https://github.com/techiescamp/python-for-devops)

Or you can clone the repo.

```bash
git clone https://github.com/techiescamp/python-for-devops

