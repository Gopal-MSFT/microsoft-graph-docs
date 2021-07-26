---
title: "Get simulation"
description: "Read the properties and relationships of a simulation object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get simulation
Namespace: microsoft.graph



Read the properties and relationships of a [simulation](../resources/simulation.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /security/attackSimulation/simulations/{simulationId}
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [simulation](../resources/simulation.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_simulation"
}
-->
``` http
GET https://graph.microsoft.com/v1.0/security/attackSimulation/simulations/{simulationId}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.simulation"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.graph.simulation",
    "id": "f1b13829-3829-f1b1-2938-b1f12938b1f1",
    "displayName": "String",
    "description": "String",
    "attackType": "String",
    "attackTechnique": "String",
    "status": "String",
    "createdDateTime": "String (timestamp)",
    "createdBy": {
      "@odata.type": "microsoft.graph.emailIdentity"
    },
    "lastModifiedDateTime": "String (timestamp)",
    "lastModifiedBy": {
      "@odata.type": "microsoft.graph.emailIdentity"
    },
    "launchDateTime": "String (timestamp)",
    "completionDateTime": "String (timestamp)",
    "includeAllAccountTargets": "Boolean",
    "enableRegionTimezoneDelivery": "Boolean",
    "mode": "String",
    "isAutomated": "Boolean",
    "cleanupArtifacts": "Boolean",
    "payloadSource": "String",
    "payloadDeliveryPlatform": "String",
    "trainingAssignmentPreference": "String",
    "trainingContentPreference": "String",
    "trainingDueDateTime": "String (timestamp)",
    "report": {
      "@odata.type": "microsoft.graph.simulationReport"
    }
  }
}
```

