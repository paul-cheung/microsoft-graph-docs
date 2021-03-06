---
title: "officeConfigurationGroupAssignmentTarget resource type"
description: "Office client configuration AAD group assignment target."
localization_priority: Normal
author: "tfitzmac"
ms.prod: "Intune"
---

# officeConfigurationGroupAssignmentTarget resource type

> **Important:** APIs under the /beta version in Microsoft Graph are subject to change. Use of these APIs in production applications is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Office client configuration AAD group assignment target.

Inherits from [officeConfigurationAssignmentTarget](../resources/intune-cirrus-officeconfigurationassignmenttarget.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|groupId|String|The Id of the AAD group we are targeting the device configuration to.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.officeConfigurationGroupAssignmentTarget"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.officeConfigurationGroupAssignmentTarget",
  "groupId": "String"
}
```



