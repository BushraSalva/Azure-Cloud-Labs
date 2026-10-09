# LAB 01 :Azure File Storage Deployment Lab

## 🏢 Scenario

As a Network Administrator, I configured Microsoft Azure to sync local on-premises files to the cloud. This setup establishes a highly available cloud storage account with an active file share backend to handle enterprise data synchronization.

## 🎯 Lab Objectives & Configurations

The primary objective was to deploy a dedicated storage solution matching these strict corporate guidelines:
| Configuration Parameter | Assigned Value |
| :--- | :--- |
| **Azure Subscription** | CorpNet Production |
| **Resource Group** | CorpNetCloud |
| **Storage Account Name** | corpnetstorageaccount *(Case-sensitive)* |
| **Deployment Region** | (US) West US2 |
| **Redundancy Tier** | Geo-redundant storage (GRS) |
| **File Share Name** | corpnetfileshare |

## 🏗️ Technical Execution Process

### Step 1: Provisioning the Storage Account

1. Log into the **Azure Portal** and select **Storage accounts** from the primary services menu.
2. Click the **+ Create** action button.
3. Fill out the configuration fields exactly as detailed in the matrix above.
4. Review the final deployment specifications and click **Create**
   
### Step 2: Creating the File Share

1. Wait for the deployment to finish, then select **Go to resource**.
2. Navigate to the left menu pane, locate the *Data storage* tier, and select **File shares**.
3. Click the **+ File share** option at the top.
4. Input the name `corpnetfileshare`, keep the default performance tiers, and select **Create**.

## 📸 Proof of Completion
Below is the verification screenshot confirming successful resource creation inside the simulator environment:
[![Lab Completion Screenshot](lab1-1.11png and 1.15png)](https://raw.githubusercontent.com/BushraSalva/Azure-Cloud-Labs/refs/heads/main/1.11.PNG)
   

