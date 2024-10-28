# Azure Fundamentals Labs (AZ-900)

## Repository Overview
Welcome to the **Azure-Fundamentals-Labs** repository! This repository is dedicated to documenting all the hands-on labs and challenges completed as part of my preparation for the **Microsoft Azure Fundamentals (AZ-900)** certification. Each lab demonstrates specific Azure concepts and implementations.

### Sandbox Labs
I utilize the Sandbox Labs provided with my course to conduct these hands-on experiments. Access to these labs allows me to follow along easily. The instructions for these labs are included, ensuring that while I document the essential concepts and my findings, specific information from the labs is not retained after completion. This ensures a streamlined learning experience.

## Structure
All the labs are organized in the **`labs`** folder, with each folder containing:
- A detailed explanation of the lab.
- Steps followed during implementation.
- Screenshots showing successful setup or configurations.

## How to Navigate
- **`labs/`**: This folder contains all the Azure labs.
  - Each lab is placed in its respective folder with a `README.md` that outlines the purpose and steps of the lab.
  - Screenshots or diagrams that visually represent the setup and completion are included for reference.

## Labs Completed
1. **[Configure Resource Lock](labs/01.resource-lock/README.md)**
   - **Description**: This lab involved configuring a resource lock to prevent accidental deletion or modification of critical resources.
   - **Key Concepts**: Resource locks (Read-only, Delete protection), Azure Management.

2. **[Azure Load Balancer Setup](labs/02.Azure-load-balancer/README.md)**
   - **Description**: In this lab, I configured a standard Azure Load Balancer, created backend pools, health probes, and set up a load balancing rule.
   - **Key Concepts**: Load balancing, backend pools, health probes.

3. **[Azure Resource Manager Template Export and Virtual Machine Deployment](labs/03.manage-azure-resource-deployment-arm-template/README.md)**
   - **Description**: This lab involved exporting an Azure Resource Manager (ARM) template for a storage account and deploying a virtual machine (VM) using a custom ARM template.
   - **Key Steps**:
     - Exported ARM template for storage account `sa45125549`.
     - Deployed a Windows VM with the name `MyVM` using the template from the GitHub repository.
     - Configured necessary parameters including resource group, admin username, password, and VM size.
   - **Resources**:
     - [Simple Windows VM Template](https://github.com/LODSContent/ChallengeLabs_ArmResources/tree/master/ARMTemplates/101-vm-simple-windows)

4. **[Manage Azure Resource Groups](labs/04.Manage-Azure-Resource-Groups/README.md)**
   - **Description**: This lab involved managing Azure resource groups by creating a storage account, exploring its properties, and reviewing available management options.
   - **Key Steps**:
     - Created an Azure storage account named `mystorage45168672` in the `RG2-lod45168672` resource group.
     - Reviewed storage account settings and available management options in the Azure portal.

5. **[Run Commands by Using Azure Cloud Shell](labs/05.run-commands-azure-cloud-shell/README.md)**
   - **Description**: This lab involved configuring Azure Cloud Shell and deploying virtual networks using both Azure PowerShell cmdlets and Azure CLI commands.
   - **Key Concepts**: Azure Cloud Shell, PowerShell, Azure CLI, Virtual Networks.

## Azure Labs and Concepts Covered
This repository will cover various labs related to the core concepts of Microsoft Azure Fundamentals, including:
- Azure Compute (VMs, Load Balancers)
- Networking (VNet, Subnets, Peering)
- Storage (Blob, File, Table)
- Azure Security (IAM, Policies)
- Monitoring and Analytics

Stay tuned as I continuously update this repository with more labs!

## Resources
- [Microsoft Learn: Azure Fundamentals](https://learn.microsoft.com/en-us/certifications/exams/az-900/)
- [Official AZ-900 Exam Page](https://learn.microsoft.com/en-us/certifications/exams/az-900/)
