---
title: "deviceManagementConfigurationDependentOn resource type"
description: "Not yet documented"
author: "dougeby"
ms.localizationpriority: medium
ms.prod: "intune"
doc_type: resourcePageType
---

# deviceManagementConfigurationDependentOn resource type

Namespace: microsoft.graph

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Not yet documented

## Properties
|Property|Type|Description|
|:---|:---|:---|
|dependentOn|String|Identifier of parent setting/ parent setting option dependent on|
|parentSettingId|String|Identifier of parent setting/ parent setting id dependent on|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.deviceManagementConfigurationDependentOn"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementConfigurationDependentOn",
  "dependentOn": "String",
  "parentSettingId": "String"
}
```



