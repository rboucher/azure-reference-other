---
title: "STDEVP (Azure Stream Analytics) | Microsoft Docs"
description: "Returns the statistical standard deviation for the population for all values in a group. Null values are ignored."
applies_to: 
  - "Azure"
services: stream-analytics
author: mamccrea


ms.service: stream-analytics
ms.topic: reference
ms.assetid: 6d8c33cc-5087-43e9-b4de-e7e120dbb1a7
caps.latest.revision: 5
ms.workload: data-services
ms.date: 04/22/2016
ms.author: mamccrea
---
# STDEVP (Azure Stream Analytics)
  Returns the statistical standard deviation for the population for all values in a group. Null values are ignored.  
  
 ## Syntax  
  
```SQL   
STDEVP (expression )  
```  
  
## Arguments  
 **expression**  
  
 Is an expression of the exact numeric or approximate numeric data type category. STDEVP can be used with bigint and float columns. Aggregate functions and sub queries are not permitted.  
  
## Return Types  
 float  
  
## Examples  
  
```SQL  
SELECT System.Timestamp() AS OutTime, TollId, STDEVP (Toll)   
FROM Input  
GROUP BY TollId, TumblingWindow(minute,3)  
  
```  
  
  
