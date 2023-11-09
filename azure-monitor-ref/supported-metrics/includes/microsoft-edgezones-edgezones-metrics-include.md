---
ms.service: azure-monitor
ms.topic: include
ms.date: 10/18/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: microsoft.edgezones/edgezones, naam
---
<!--
NOTE:  This content is automatically generated using API calls to Azure. 
Any edits made on these files will be overwritten in the next run of the script. 
There is no benefit in editing these files directly.  
-->
  
  
|Metric|Name in REST API|Unit|Aggregation|Dimensions|Time Grains|DS Export|
|---|---|---|---|---|---|---|
|**Disk IOPS**<p><p>The total IOPS generated by Managed Disks in Azure Edge Zone Enterprise site. |`DiskStorageIOPSUsage` |CountPerSecond |Average |\<none\>|PT1M |No|
|**Disk Usage Percentage**<p><p>The utilization of the Managed Disk capacity in Azure Edge Zone Enterprise site. |`DiskStorageUsedSizeUsage` |Percent |Average |\<none\>|PT1H |Yes|
|**Region Site Connectivity**<p><p>The status of an Edge Zone Enterprise link connection to its Azure region |`RegionSiteConnectivity` |Count |Average, Maximum, Minimum |\<none\>|PT1M |Yes|
|**Total Disk Capacity**<p><p>The total capacity of Managed Disk in Azure Edge Zone Enterprise site. |`TotalDiskStorageSizeCapacity` |Bytes |Average |\<none\>|PT1H |Yes|
|**Total VCore Capacity**<p><p>The total capacity of the General-Purpose Compute vcore in Edge Zone Enterprise site.  |`TotalVcoreCapacity` |Count |Average |\<none\>|PT1M |Yes|
|**Vcore Usage Percentage**<p><p>The utilization of the General-Purpose Compute vcores in Edge Zone Enterprise site  |`VcoresUsage` |Percent |Average |\<none\>|PT1M |Yes|