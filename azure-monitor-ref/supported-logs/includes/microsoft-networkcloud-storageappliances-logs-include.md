---
ms.service: azure-monitor
ms.topic: include
ms.date: 04/01/2024
ms.author: edbaynash
author: EdB-MSFT
ms.custom: Microsoft.NetworkCloud/storageAppliances, naam

# NOTE:  This content is automatically generated using API calls to Azure. Any edits made on these files will be overwritten in the next run of the script. 

---
  
  
|Category|Category display name| Log table| [Supports basic log plan](/azure/azure-monitor/logs/basic-logs-configure?tabs=portal-1#compare-the-basic-and-analytics-log-data-plans)|[Supports ingestion-time transformation](/azure/azure-monitor/essentials/data-collection-transformations)| Example queries |Costs to export|
|---|---|---|---|---|---|---|
|`StorageApplianceAlert` |Storage Appliance alerts ||No|No||Yes |
|`StorageApplianceAudit` |Storage Appliance audits |[NCSStorageLogs](/azure/azure-monitor/reference/tables/ncsstoragelogs)<p>Log events from Nexus storage appliance providing insight into data access and system performance.|Yes|No||Yes |
|`StorageApplianceLogs` |Storage Appliance logs ||No|No||Yes |