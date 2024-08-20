# Azure Structure Setup Guide

This repository provides a comprehensive guide to setting up and managing Azure infrastructure, including creating a Microsoft Entra ID Tenant, Subscription, Resource Groups, and Azure Resources such as Virtual Machines.

## Table of Contents

- [Microsoft Entra ID Tenant](#1-Microsoft-Entra-ID-Tenant)
  - [Create Azure Account](#1-Microsoft-Entra-ID-Tenant/1.1-Create-Azure-Account.md)
  - [Create Entra ID Tenant](1-Microsoft-Entra-ID-Tenant/1.2-Create-Entra-ID-Tenant.md)
- [Subscription](2-Subscription/2.1-Create-Subscription.md)
- [Resource Group](3-Resource-Group/3.1-Create-Resource-Group.md)
- [Azure Resources](4-Azure-Resources)
  - [Create Virtual Machine](4-Azure-Resources/4.1-Create-Virtual-Machine.md)
  - [Accessing Your VM](4-Azure-Resources/4.2-Accessing-Your-VM.md)
  - [Manage Your Resources](4-Azure-Resources/4.3-Manage-Your-Resources.md)
---
## Introduction

This guide will walk you through the steps to set up a basic Azure infrastructure, including creating a Microsoft Entra ID tenant, setting up a subscription, creating resource groups, and deploying and managing Azure resources.

![image](https://github.com/user-attachments/assets/f157bd67-0b40-40bb-a9fe-b0f049415f49)

---
# - Microsoft Entra ID Tenant
## Create an Azure Account

If you don't have an Azure account, follow these steps to create one:

1. Go to the [Azure sign-up page](https://azure.microsoft.com/).
2. Click on "Start free" (or select a different plan if needed).

![image](https://github.com/user-attachments/assets/51ca2c1d-4fb2-4a6d-85ff-d8cfdf910a35)

3. Follow the steps to create a new Microsoft account or use an existing one.
4. After signing up, you'll be directed to the Azure Portal.

   ![image](https://github.com/user-attachments/assets/812d70e1-cd31-49bc-8a37-6c8046fcc6e1)


Once you've created your account, you're ready to set up your Microsoft Entra ID Tenant.

---
## Create a Microsoft Entra ID Tenant

1. In the Azure Portal, search for "Microsoft Entra ID" in the search bar and select it.
2. Select "Manage tenants" from the top pane, then click "Create."

![image](https://github.com/user-attachments/assets/cdd01c0d-f1f2-4872-8c2e-6ea7d9b68300)


![image](https://github.com/user-attachments/assets/930c13ba-05da-4170-a220-589623f274eb)

![image](https://github.com/user-attachments/assets/c9b38398-4f0a-4b08-ba24-b0e0bfca861c)


3. Choose "Microsoft Entra ID" as the directory type.
4. Fill in the details like Organisation name and Initial domain name.

![image](https://github.com/user-attachments/assets/f86c0ae9-22b3-4df3-9c0b-bae6b198ab50)


5. Review the details and click "Create" to complete the tenant creation.

---
# Create a Subscription

A subscription is required to manage and deploy Azure resources. Here's how to create one:

1. In the Azure Portal, search for "Subscriptions" and select it.

![image](https://github.com/user-attachments/assets/5f65513d-8bb9-450e-85ce-fb09073f0175)


2. Click on "Add" to create a new subscription.

![image](https://github.com/user-attachments/assets/f53fbf47-ac09-4fce-87fc-64672eabdb39)


3. Choose the desired subscription offer, like Pay-As-You-Go.
4. Assign the subscription to your Microsoft Entra ID tenant.

Once the subscription is created, you can begin creating resource groups and deploying resources.




