---
title: Service Health overview | Microsoft Docs
description: Personalized information about how your Azure apps are affected by current and future Azure service problems and maintenance. 
services: Resource health
documentationcenter: ''
author: rboucher
manager: ''
editor: ''

ms.assetid: 
ms.service: service-health
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: Supportability
ms.date: 07/07/2017
ms.author: robb

---
# Service Health
Service Health provides you with a customizable dashboard which tracks the health of your Azure services in the regions where you use them. In this dashboard, you can track active events like ongoing service issues, upcoming planned maintence, or relevant health advisories. When events become inactive, they get placed in your health history for up to 90 days. Finally, you can use the Service Health dashboard to create and manage service health alerts which proactively notify you when service issues are affecting you.

## Service Health Events
Service Health tracks three types of health events that may impact your resources:
1. **Service issues** - Problems in the Azure services that affect you right now. 
2. **Planned maintenance** - Upcoming maintenance that can affect the availability of your services in the future.  
3. **Health advisories** - Changes in Azure services that require your attention. Examples include when Azure features are deprecated or if you exceed a usage quota.

## Get started with Service Health
To launch your Service Health dashboard, select the Service Health tile on your portal dashboard. If you have previously removed the tile or you're using custom dashboard, search for Service Health service in "More services" (bottom left on your dashboard).
![Get started with Service Health](./media/service-health-overview/azure-service-health-overview-1.png)

## See current issues which impact your services
The **Service issues** view shows any ongoing problems in Azure services that are impacting your resources. You can understand when the issue began, and what services and regions are impacted. You can also read the most recent update to understand what Azure is doing to resolve the issue. 
![Manage service issue](./media/service-health-overview/azure-service-health-overview-2.png)

Choose the **Potential impact** tab to see the specific list of resources you own that might be impacted by the issue. You can download a CSV list of these resources to share with your team.
![Manage service issue - Impact](./media/service-health-overview/azure-service-health-overview-4.png)

## Get links and downloadable explanations 
You can get a link for the issue to use in your problem management system. You can download PDF and sometimes CSV files to share with people who don’t have access to the Azure portal.   
![Manage service issue - Problem management](./media/service-health-overview/azure-service-health-overview-3.png)

## Get support from Microsoft
Contact support if your resource is left in a bad state even after the issue is resolved.  Use the support links on the right of the page.  

## Pin a personalized health map to your dashboard
Filter Service Health to show your business-critical subscriptions, regions, and resource types. Save the filter and pin a personalized health world map to your portal dashboard. 
![Filter personalized health map](./media/service-health-overview/azure-service-health-overview-6a.png)
![Pin a personalized health map](./media/service-health-overview/azure-service-health-overview-6b.png)

## Configure service health alerts
Service Health integrates with Azure Monitor to alert you via emails, text messages, and webhook notifications when your business-critical resources are impacted. Set up an activity log alert for the appropriate service health event. Route that alert to the appropriate people in your organization using Action Groups. For more information, see [Configure Alerts for Service Health](../monitoring-and-diagnostics/monitoring-activity-log-alerts-on-service-notifications.md)

# Next Steps
Set up alerts so you are notified of health issues. For more information, see [Configure Alerts for Service Health](../monitoring-and-diagnostics/monitoring-activity-log-alerts-on-service-notifications.md). 