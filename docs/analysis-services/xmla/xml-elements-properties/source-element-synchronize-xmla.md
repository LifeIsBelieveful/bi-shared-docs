---
title: "Source Element (Synchronize) (XMLA) | Microsoft Docs"
ms.date: 07/24/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: xmla
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# Source Element (Synchronize) (XMLA)

  Represents a source database from which to synchronize a target database during a [Synchronize](../xml-elements-commands/synchronize-element-xmla.md) command.  
  
## Syntax  
  
```xml  
  
<Synchronize>  
   <Source>  
      <Object>...</Object>  
      <ConnectionString>...</ConnectionString>  
   </Source>  
</Synchronize>  
```  
  
## Element characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|None|  
|Default value|None|  
|Cardinality|1-1: Required element that occurs once and only once.|  
  
## Element relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[Synchronize](../xml-elements-commands/synchronize-element-xmla.md)|  
|Child elements|[ConnectionString](../xml-elements-properties/connectionstring-element-xmla.md), [Object](../xml-elements-properties/object-element-xmla.md)|  
  
## Remarks  
 The **Synchronize** command uses the **Source** element to establish a connection to and identify a database on an instance of Analysis Services with which to synchronize the target database.  
