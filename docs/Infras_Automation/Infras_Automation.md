## Learn Infrastructure Automation

We no longer create servers manually. Infrastructure automation tools have become an essential aspect of every organization. Also, all modern infrastructure deployments follow the immutable infrastructure model.

As per a report from Red Hat, many organizations are investing in their automation initiatives. Check out this data:

![image](https://github.com/ben-le/DevOps_Trainings/assets/34547999/44b3526f-ab6f-4118-99df-c41e9b8f9237)


From provisioning servers to application configuration and deployment, everything should be automated. You can learn any of the following DevOps toolsets that fit your needs:

### For Dev Environment
1. Vagrant
2. Docker Desktop
3. Minikube (Kubernetes)
4. Minishift (Kubernetes)
5. Kind (Kubernetes)

### For Infrastructure Provisioning
1. Terraform (preferable)
2. CloudFormation for AWS
3. CLIs (of respective cloud provider)
4. Pulumi

### For Configuration Management
1. Ansible (preferable)
2. Chef
3. Puppet
4. SaltStack

### VM Image/Container Management
1. HashiCorp Packer
2. Docker

### Tips on Learning Automation Tools

1. **Learn the Basics**: Start with a blog, official documentation, or a course—whichever you feel comfortable with.
2. **Hands-on Practice**: If you want to write an Ansible playbook for Nginx, first configure Nginx manually and understand how the components and configs work. Then start writing the playbook.
3. **Test-Driven Development**: Ensure you learn test-driven infrastructure development. There are testing tools for every automation tool (e.g., Ansible-test, Terratest).
4. **Use Community Modules**: Community modules are a great reference for learning. You can learn complex logic from community modules, but ensure you know what each block of code does.

### Resources:
- [Udacity Cloud DevOps Engineer Nanodegree](https://www.udacity.com/course/cloud-dev-ops-nanodegree--nd9991)
- [Learn DevOps: Infrastructure Automation With Terraform](https://www.udemy.com/course/learn-devops-infrastructure-automation-with-terraform/?couponCode=ST16MT70224)
- [Ansible for the Absolute Beginner – Hands-On – DevOps](https://www.udemy.com/course/learn-ansible/?couponCode=ST16MT70224)

