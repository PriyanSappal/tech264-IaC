# Infrastructure as Code (IaC)

- [Infrastructure as Code (IaC)](#infrastructure-as-code-iac)
  - [What is IaC?](#what-is-iac)
  - [Benefits of IaC](#benefits-of-iac)
  - [When/Where to use IaC](#whenwhere-to-use-iac)
  - [What are the tools available for IaC?](#what-are-the-tools-available-for-iac)
  - [What is Configuration Management (CM)?](#what-is-configuration-management-cm)
  - [What is provisioning of infrastructure? Do CM tools do it?](#what-is-provisioning-of-infrastructure-do-cm-tools-do-it)
  - [What is Ansible and how does it work?](#what-is-ansible-and-how-does-it-work)
    - [Key Features:](#key-features)
  - [Who is using IaC and Ansible in the industry?](#who-is-using-iac-and-ansible-in-the-industry)
- [Steps to install terraform](#steps-to-install-terraform)


## What is IaC?
Infrastructure as Code (IaC) is the process of managing and provisioning computing infrastructure through machine-readable configuration files, rather than through physical hardware configuration or interactive configuration tools. IaC allows for automation of infrastructure management, ensuring consistency and reducing human error.

## Benefits of IaC
- **Automation**: Reduces the need for manual intervention by automating the provisioning and management of infrastructure.
- **Consistency**: Ensures that infrastructure is provisioned in a repeatable and reliable manner.
- **Version Control**: Infrastructure definitions can be stored in version control systems, allowing for easy rollbacks and tracking of changes.
- **Scalability**: Facilitates the quick and efficient scaling of infrastructure based on demand.
- **Cost Efficiency**: Reduces overhead and operational costs by minimizing human error and streamlining processes.

## When/Where to use IaC
- **Cloud environments**: When managing cloud infrastructure like AWS, Azure, or Google Cloud.
- **Large-scale infrastructure**: To efficiently manage and provision many servers or resources.
- **CI/CD pipelines**: When infrastructure needs to be provisioned automatically for continuous integration and deployment processes.
- **DevOps practices**: When teams are practicing DevOps and need to unify development and operations workflows.

## What are the tools available for IaC?
- **Terraform**: A declarative tool that works across multiple cloud providers.
- **AWS CloudFormation**: An IaC tool specific to AWS environments.
- **Azure Resource Manager (ARM)**: The IaC tool for managing resources on Azure.
- **Google Cloud Deployment Manager**: IaC tool for provisioning Google Cloud infrastructure.
- **Pulumi**: Supports various languages for infrastructure definitions.
  
## What is Configuration Management (CM)?
Configuration Management (CM) is the process of systematically handling changes to ensure consistency over time. It involves maintaining system settings, software versions, and configurations to avoid unexpected behavior in infrastructure.

## What is provisioning of infrastructure? Do CM tools do it?
Provisioning of infrastructure refers to the process of setting up necessary computing resources (such as servers, databases, networks, etc.) for an application or system. CM tools like Ansible, Puppet, and Chef can provision infrastructure, but their primary focus is on managing configurations and keeping the infrastructure in a desired state.

## What is Ansible and how does it work?
Ansible is an open-source automation tool used for configuration management, application deployment, and infrastructure provisioning. It works by using a simple language (YAML) to describe tasks, which it then runs over SSH, without the need for an agent to be installed on the remote systems. Ansible uses a 'push' model, where the controlling node pushes the configurations to the target nodes.

### Key Features:
- **Agentless**: No need to install software on target machines.
- **Idempotent**: Ensures that applying the same configuration multiple times will result in the same outcome.
- **Easy-to-learn syntax**: Uses YAML, a human-readable data serialization standard.

## Who is using IaC and Ansible in the industry?
- **Tech companies** like Google, Facebook, and Netflix use IaC to scale their massive infrastructure automatically.
- **Enterprises** like banks, e-commerce platforms, and health-tech companies use Ansible to automate their operations.
- **Startups** also leverage IaC to quickly deploy and manage their cloud infrastructure.

# Steps to install terraform 
1) Go on the terraform website and select the **Windows AMD64**.
2) This will download as a zip you can then extract this and add it to a `C:\my-cmd-line-tools`.
3) Search on the search below **Edit System Environment Variables** and add a PATH env variable with the path to the terraform file. 