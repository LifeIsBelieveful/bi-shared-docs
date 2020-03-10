---
title: "ModelingFlags Element (ASSL) | Microsoft Docs"
ms.date: 07/25/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: assl
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# ModelingFlags Element (ASSL)

  Contains the collection of [ModelingFlag](../objects/modelingflag-element-assl.md) elements for a column in a [MiningStructure](../objects/miningstructure-element-assl.md) or a [MiningModel](../objects/miningmodel-element-assl.md).  
  
## Syntax  
  
```xml  
  
<MiningModelColumn> <!-- or ScalarMiningStructureColumn -->  
   ...  
   <ModelingFlags>  
      <ModelingFlag xsi:type="MiningModelingFlag">...</ModelingFlag>  
   </ModelingFlags>  
   ...  
</MiningModelColumn>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|None|  
|Default value|None|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[MiningModelColumn](../data-type/miningmodelcolumn-data-type-assl.md), [ScalarMiningStructureColumn](../data-type/scalarminingstructurecolumn-data-type-assl.md)|  
|Child elements|[ModelingFlag](../objects/modelingflag-element-assl.md)|  
  
## Remarks  
 The corresponding element in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.MiningModelingFlags>.  