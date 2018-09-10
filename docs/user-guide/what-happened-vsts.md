---
title: Visual Studio Team Services is now Azure DevOps Services
description: Visual Studio Team Services is now Azure DevOps Services. What's Azure DevOps?
ms.prod: devops
ms.topic: article
ms.technology: devops-whitepapers
ms.manager: douge
ms.date: 09/10/2018
ms.author: douge
author: erickson-doug
monikerRange: '>= vsts'
---

# Visual Studio Team Services is now Azure DevOps Services

On September 10th, 2018, Microsoft renamed Visual Studio Team Services (VSTS) to "Azure DevOps Services". For more information about this change, see [this blog post](https://aka.ms/azurevsts).

VSTS features are now separate services:

| VSTS feature name    | Azure DevOps service name | Description |
|----------------------|----------------------|-------------|
| Build & release      | Azure Pipelines      | CI/CD that works with any language, platform, and cloud. |
| Code                 | Azure Repos          | Unlimited cloud-hosted private Git and TFVC repos for your project. |
| Work                 | Azure Boards         | Work tracking with Kanban boards, backlogs, team dashboards, and custom reporting. |
| Test                 | Azure Test Plans     | All-in-one planned and exploratory testing solution. |
| Packages (extension) | Azure Artifacts      | Maven, npm, and NuGet package feeds from public and private sources. |


Currently, you can acquire only **Azure Pipelines** as a separate service. In the future, you'll be able to acquire each service separately or all together as **Azure DevOps Services**. If you are already a VSTS subscriber, you have access to all of the services now.  

> [!NOTE]   
> You can [disable select services from the user interface](../organizations/settings/set-services.md).

Follow the [Azure DevOps release notes](/vsts/release-notes/index) to get news on the latest updates!

## Can I still use visualstudio.com?

Yes. We've moved to the new `dev.azure.com` domain name as the primary URL for new organizations. (Specifically, `https://dev.azure.com/{your organization}/{your project}`.) If you'd like to change your URL to be based on `dev.azure.com` as the primary, an organization administrator can change this from the organization settings page.

We will continue to post news about this transition on the [Microsoft DevOps blog](https://blogs.msdn.microsoft.com/devops/) and in the [Azure DevOps release notes](https://docs.microsoft.com/en-us/vsts/release-notes/index).

## Can I still use the old interface?

You can still use the previous user interface by choosing your profile icon and selecting **Preview features** from the drop-down menu.

> [!div class="mx-imgBorder"]  
> ![Open Preview Features](../project/navigation/_img/manage-features/choose-preview-features-vert.png)

Then, toggle the **New Navigation** option to **Off**.

> [!div class="mx-imgBorder"] 
> ![Turning off the new navigation UI](_img/turn-off-new-nav.png)

Turning off New Navigation will also change the Azure DevOps Services names to the corresponding old VSTS feature names, such as **Work** instead of **Boards**.

To return to the Azure DevOps service-oriented UI, choose your profile icon, select **Preview features**, and re-enable **New Navigation**.

## What about Team Foundation Server (TFS)?

As of September 10, 2018, [Team Foundation Server](/tfs/index) (TFS) is unchanged and fully-supported as our on-premises Agile workflow and DevOps product. The latest version is TFS 2018; the latest servicing update is **Team Foundation Server 2018 Update 3**, which released on **August 28, 2018**.