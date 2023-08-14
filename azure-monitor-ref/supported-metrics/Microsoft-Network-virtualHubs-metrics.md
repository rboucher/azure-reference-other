---
title: Supported metrics - Microsoft.Network/virtualHubs
description: Reference for Microsoft.Network/virtualHubs metrics in Azure Monitor.
ms.topic: reference
ms.service: azure-monitor
ms.author: edbaynash
author: EdB-MSFT
ms.date: 07/12/2023
---
# Supported metrics for Microsoft.Network/virtualHubs  
<!-- Data source : naam-->


The following table lists the metrics available for the Microsoft.Network/virtualHubs resource type.

  

**Table headings**
  
**Metric** - Metric display name follows by a description of the metric. The displayname appears in the Azure portal.  
**Name** - The name of the metric as referred to in the REST API.  
**Unit** - The default units used for the metric.  
**Aggregation** - The default aggregation type for this metric. Valid values: Average, Minimum, Maximum, Total, Count.  
**Dimensions** - Dimensions available. For more information, see (link to dimensions information).  
**DS Export**- Whether the metric is exportable to Azure Monitor Logs via Diagnostic Settings.  You can access all metrics via the REST API.  
  
  
|Metric|Name|Unit|Aggregation|Dimensions|DS Export|
|---|---|---|---|---|---|
|Bgp Peer Status<p><p>1 - Connected, 0 - Not connected |`BgpPeerStatus` |Count |Maximum |routeserviceinstance, bgppeerip, bgppeertype |No|
|Count Of Routes Advertised To Peer<p><p>Total number of routes advertised to peer |`CountOfRoutesAdvertisedToPeer` |Count |Maximum |routeserviceinstance, bgppeerip, bgppeertype |No|
|Count Of Routes Learned From Peer<p><p>Total number of routes learned from peer |`CountOfRoutesLearnedFromPeer` |Count |Maximum |routeserviceinstance, bgppeerip, bgppeertype |No|
|Data Processed by the Virtual Hub Router<p><p>Data Processed by the Virtual Hub Router |`VirtualHubDataProcessed` |Bytes |Total |No Dimensions |No|


<!--Gen Date:  Wed Jul 12 2023 17:59:09 GMT+0300 (Israel Daylight Time)-->