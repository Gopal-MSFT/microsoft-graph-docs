---
title: "attackSimulationTrainingUserCoverage resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# attackSimulationTrainingUserCoverage resource type

Namespace: microsoft.graph



**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|attackSimulationUser|[attackSimulationUser](../resources/attacksimulationuser.md)|**TODO: Add Description**|
|userTrainings|[userTrainingStatusInfo](../resources/usertrainingstatusinfo.md) collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.attackSimulationTrainingUserCoverage"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.attackSimulationTrainingUserCoverage",
  "userTrainings": [
    {
      "@odata.type": "microsoft.graph.userTrainingStatusInfo"
    }
  ],
  "attackSimulationUser": {
    "@odata.type": "microsoft.graph.attackSimulationUser"
  }
}
```

