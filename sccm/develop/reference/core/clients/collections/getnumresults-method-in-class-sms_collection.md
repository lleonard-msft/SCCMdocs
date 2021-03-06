---
title: "GetNumResults Method | Microsoft Docs"
ms.custom: ""
ms.date: "09/20/2016"
ms.prod: "configuration-manager"
ms.reviewer: ""
ms.suite: ""
ms.technology:
  - "configmgr-other"
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to:
  - "System Center Configuration Manager (current branch)"
ms.assetid: 90490d60-3bd4-44bf-a536-a7947d66ed32searchScope: - ConfigMgr SDK
caps.latest.revision: 7
author: "shill-ms"
ms.author: "v-suhill"
manager: "mbaldwin"
---
# GetNumResults Method in Class SMS_Collection
The `GetNumResults` Windows Management Instrumentation (WMI) class method, in System Center Configuration Manager, gets a count of all members in a collection, not including subcollections.  

 The following syntax is simplified from Managed Object Format (MOF) code and defines the method.  

## Syntax  

```  
SInt32 GetNumResults(  
     ref:SMS_Collection Collection,  
     UInt32 Result  
);  
```  

#### Parameters  
 `Collection`  
 Data type: `ref:SMS_Collection`  

 Qualifiers: [in]  

 Collection ID or object path of the collection. The collection ID is the value of the `CollectionID` property of [SMS_Collection Server WMI Class](../../../../../develop/reference/core/clients/collections/sms_collection-server-wmi-class.md).  

 `Result`  
 Data type: `UInt32`  

 Qualifiers: [out]  

 Number of collection members.  

## Return Values  
 An  `SInt32` data type that is 0 to indicate success or non-zero to indicate failure.  

 For more information about handling returned errors, see [About Configuration Manager Errors](../../../../../develop/core/understand/about-configuration-manager-errors.md).  

## Requirements  

## Runtime Requirements  
 For more information, see [Configuration Manager Server Runtime Requirements](../../../../../develop/core/reqs/server-runtime-requirements.md).  

## Development Requirements  
 For more information, see [Configuration Manager Server Development Requirements](../../../../../develop/core/reqs/server-development-requirements.md).  

## See Also  
 [SMS_Collection Server WMI Class](../../../../../develop/reference/core/clients/collections/sms_collection-server-wmi-class.md)   
 [SMS_Site Server WMI Class](../../../../../develop/reference/core/servers/configure/sms_site-server-wmi-class.md)
