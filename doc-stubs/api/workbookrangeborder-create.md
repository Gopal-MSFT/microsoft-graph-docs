---
title: "Create workbookRangeBorder"
description: "Create a new workbookRangeBorder object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create workbookRangeBorder
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [workbookRangeBorder](../resources/workbookrangeborder.md) object.

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
POST /workbookRange/format/borders
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [workbookRangeBorder](../resources/workbookrangeborder.md) object.

The following table shows the properties that are required when you create the [workbookRangeBorder](../resources/workbookrangeborder.md).

|Property|Type|Description|
|:---|:---|:---|
|color|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|sideIndex|String|**TODO: Add Description**|
|style|String|**TODO: Add Description**|
|weight|String|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [workbookRangeBorder](../resources/workbookrangeborder.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_workbookrangeborder_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/workbookRange/format/borders
Content-Type: application/json
Content-length: 162

{
  "@odata.type": "#Microsoft.ExcelServices.workbookRangeBorder",
  "color": "String",
  "sideIndex": "String",
  "style": "String",
  "weight": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.ExcelServices.workbookRangeBorder"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.ExcelServices.workbookRangeBorder",
  "color": "String",
  "id": "f1665dc6-5dc6-f166-c65d-66f1c65d66f1",
  "sideIndex": "String",
  "style": "String",
  "weight": "String"
}
```

