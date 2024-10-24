# Azure Fundamentals Labs (AZ-900)

## Repository Overview
Welcome to the **Azure-Fundamentals-Labs** repository! This repository is dedicated to documenting all the hands-on labs and challenges completed as part of my preparation for the **Microsoft Azure Fundamentals (AZ-900)** certification. Each lab demonstrates specific Azure concepts and implementations.

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
1. **[Configure Resource Lock](labs/resource-lock/README.md)**
   - **Description**: This lab involved configuring a resource lock to prevent accidental deletion or modification of critical resources.
   - **Key Concepts**: Resource locks (Read-only, Delete protection), Azure Management.

2. **[Azure Load Balancer Setup](labs/Azure-load-balancer/README.md)**
   - **Description**: In this lab, I configured a standard Azure Load Balancer, created backend pools, health probes, and set up a load balancing rule.
   - **Key Concepts**: Load balancing, backend pools, health probes.

3. **[Azure Resource Manager Template Export and Virtual Machine Deployment](labs/manage-azure-resource-deployment-arm-template/README.md)**
   - **Description**: This lab involved exporting an Azure Resource Manager (ARM) template for a storage account and deploying a virtual machine (VM) using a custom ARM template.
   - **Key Steps**:
     - Exported ARM template for storage account `sa45125549`.
     - Deployed a Windows VM with the name `MyVM` using the template from the GitHub repository.
     - Configured necessary parameters including resource group, admin username, password, and VM size.
   - **Resources**:
     - [Simple Windows VM Template](https://github.com/LODSContent/ChallengeLabs_ArmResources/tree/master/ARMTemplates/101-vm-simple-windows)

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
