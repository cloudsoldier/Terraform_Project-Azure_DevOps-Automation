# Learn Terraform_Project ON Azure_DevOps-Automation

- What we will learn




- **Setting up Terraform development environment**

Here’s your text formatted in Markdown:


- **We will install:**
   - **Visual Studio Code**
   - **Azure CLI**
   - **Terraform**
   - **Initialize DevOps environment with Terraform provider to work with Azure Cloud**
   - **Using Azure, Service Principal, and Managed Identity**



  
     <img width="704" alt="image" src="https://github.com/user-attachments/assets/963e161b-e182-439b-87ca-c77ce409c557" />

Here’s your revised content formatted in Markdown:


**Lab Implementation Overview:**

We will implement a **multi-tier real infrastructure scenario** using **Terraform**.  

The lab will be divided into smaller, manageable parts, and each part will be deployed step by step:

- **Remote State Storage** and **Key Vault** for Secret Management
- 
  <img width="325" alt="image" src="https://github.com/user-attachments/assets/d3f1fb70-4fc0-4b14-b4cb-abe8a8f757eb" />

- **Jumpbox Environment**

  <img width="325" alt="image" src="https://github.com/user-attachments/assets/434818ff-a437-4001-bf11-8260547058eb" />

- **Backend Environment**

   <img width="325" alt="image" src="https://github.com/user-attachments/assets/c4a10416-f5be-4815-b96b-52fa8b7049f7" />
   
- **Frontend Environment**

  <img width="325" alt="image" src="https://github.com/user-attachments/assets/b187a753-3bac-44ef-8755-17ef558a0d44" />

  
- **Network Peering** to connect all environments seamlessly using **Terraform**  


# Implementing Lab in Multiple Ways

- Deploying code using Az-CLI session and saving state file on the local filesystem.
- Parameterizing the lab using input and output variables.
- Modularizing the code and deploying the lab using a local module.
- Using Terraform registry module for the lab.
- Reusing the code and deploying multiple environments using workspaces and directories method.
- Deploying the lab using a service principal account.
- Deploying the lab again using Key Vault for secrets.
- Implementing remote state storage on Azure Blob Storage.

Apart from that, you will learn about:
- Dependency graph
- Implicit and explicit dependency

  __________________________________

  # Planned Lab Modifications and Integrations

- I will modify the lab to work with Azure DevOps and Azure Cloud.
- I will integrate the lab with GitHub.
- I will create a service connection between Azure DevOps and GitHub.
- I will set up a service connection between Azure DevOps and Azure Cloud using a Service Principal (SP) account.
- I will create a pipeline in Azure DevOps to deploy the code on Azure Cloud.

  
<img width="897" alt="image" src="https://github.com/user-attachments/assets/7cded6c3-0e51-466b-ab0f-be6d2d855129" />



# Planned Tasks After Setting Up the DevOps Environment

- I will complete tasks again using Azure DevOps:
  - Using a Service Principal account through Azure DevOps.
  - Setting up a Service Connection through Azure DevOps.
  - Utilizing local and Terraform registry modules to deploy the lab using Azure Pipelines.
  
- I will implement secret management in 5 different ways:
  - Using Key Vault for secrets as a data source.
  - Using Key Vault for secrets, authorized via a Service Connection through Azure DevOps.
  - Using environmental variables in three different ways to implement the code.

- I will deploy multiple environments using workspaces and directories in Azure Pipelines.

- I will create a complete CI/CD pipeline with triggers and approvals.


 - Get familiarized with these abbreviations.

   <img width="791" alt="image" src="https://github.com/user-attachments/assets/08ef6cd0-1f0d-41ff-bc49-a8135bcc1132" />

<img width="734" alt="image" src="https://github.com/user-attachments/assets/a470ab57-7171-4b9d-8160-c89559e316be" />
   


