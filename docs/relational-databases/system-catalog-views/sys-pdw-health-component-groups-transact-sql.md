---
description: "See a reference for the system catalog view sys.pdw_health_component_groups (Transact-SQL) for Analytics Platform System."
title: "sys.pdw_health_component_groups (Transact-SQL) | Microsoft Docs"
ms.date: "05/12/2022"
ms.prod: sql
ms.reviewer: ""
ms.technology: system-objects
ms.topic: reference
dev_langs: 
  - "TSQL"
ms.assetid: 5ba27432-7a29-4420-b73d-def621c0b3ac
author: ronortloff
ms.author: rortloff
monikerRange: ">= aps-pdw-2016"
ms.custom: kr2b-contr-experiment
---
# sys.pdw_health_component_groups (Transact-SQL)
[!INCLUDE [pdw](../../includes/applies-to-version/pdw.md)]

This view stores information about logical groupings of components and devices.

|Column Name|Data Type|Description|Range|
|-----------------|---------------|-----------------|-----------|
|group_id|**int**|Unique identifier for components and devices.<br />Key for this view.|NOT NULL|
|group_name|**nvarchar(255)**|Logical group name for the components and devices.|NOT NULL|

## See Also  
 [Azure Synapse Analytics and Parallel Data Warehouse Catalog Views](../../relational-databases/system-catalog-views/sql-data-warehouse-and-parallel-data-warehouse-catalog-views.md)  
  
  
