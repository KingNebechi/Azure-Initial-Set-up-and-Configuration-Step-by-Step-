# AZURE STRUCTURE Description

## Microsoft Entra ID Tenant
---
**Purpose:** The top-level container representing your organisation within Azure. It manages users, applications, and security. It is the azure environment

**Components:**
- **Users & Groups:** Defines who can access the resources and their roles.
- **Applications:** Manages apps registered within the tenant for single sign-on and API access.

## Subscription
---
**Purpose:** A logical container that groups and manages your resources and their billing. Each subscription is linked to one tenant but can contain multiple resource groups.

**Components:**
- **Billing:** Manages payment for resources used.
- **Resource Limits:** Defines quotas for the resources you can deploy.

## Resource Group
---
**Purpose:** Organises and manages related resources as a single unit. Resources that share the same lifecycle or serve a common purpose are typically grouped together.

**Components:**
- **Resources:** Any Azure service or resource like virtual machines, storage accounts, databases, etc.
- **Management:** Apply policies, manage costs, and set permissions for the group.

## Azure Resources

**Examples:** Virtual machines, databases, storage accounts, web apps, etc.

**Purpose:** These are the individual services and applications you deploy and manage within a resource group. Each resource is a unit of service provided by Azure.
