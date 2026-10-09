# Lab 01: Create Azure Storage Account

## 🏢 Scenario
You are the network administrator for your company. You are configuring Azure to help manage your network. You are synchronizing on-premise files to the cloud. The next step is to create an Azure Storage Account with a File Share to sync the files to.

## 🎯 Objectives
In this lab, your task is to complete the following:

1. **Create a Storage Account** with these specific configurations:
   * **Subscription:** `CorpNet Production`
   * **Resource group:** `CorpNetCloud`
   * **Storage account name:** `corpnetstorageaccount` (Case-sensitive)
   * **Region:** `(US) West US2`
   * **Redundancy:** `Geo-redundant storage (GRS)`

2. **Create a File Share** named `corpnetfileshare` inside the newly created storage account.
   
## 🛠️ Step-by-Step Instructions

### Step 1: Create the Storage Account
1. Log into the **Azure Portal**.
2. Under *Azure Services*, select **Storage accounts**.
3. Click **+ Create** in the top menu bar.
4. Fill out the configuration details exactly as specified in the objectives above.
5. Review and click **Create** to deploy the resource.

### Step 2: Create the File Share
1. When the storage account deployment is complete, select **Go to resource**.
2. In the left navigation pane under *Data storage*, select **File shares**.
3. Click **+ File share** at the top.
4. Name the share `corpnetfileshare` and complete the creation process.
