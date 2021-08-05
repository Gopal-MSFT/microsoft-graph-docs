---
title: "Create workbookOperation"
description: "Create a new workbookOperation object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create workbookOperation
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new workbookOperation object.

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
POST /driveItem/workbook/operations
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [workbookOperation](../resources/workbookoperation.md) object.

The following table shows the properties that are required when you create the [workbookOperation](../resources/workbookoperation.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|status|workbookOperationStatus|**TODO: Add Description**. Possible values are: `notStarted`, `running`, `succeeded`, `failed`.|
|resourceLocation|String|**TODO: Add Description**|
|statusCode|Int32|**TODO: Add Description**|
|error|[Microsoft.ExcelServices.workbookOperationError](../resources/workbookoperationerror.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [workbookOperation](../resources/workbookoperation.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_workbookoperation_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/driveItem/workbook/operations
Content-Type: application/json
Content-length: 232

{
  "@odata.type": "#Microsoft.ExcelServices.workbookOperation",
  "status": "String",
  "resourceLocation": "String",
  "statusCode": "Integer",
  "error": {
    "@odata.type": "microsoft.graph.workbookOperationError"
  }
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.ExcelServices.workbookOperation"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.ExcelServices.workbookOperation",
  "id": "6a8d9738-9738-6a8d-3897-8d6a38978d6a",
  "status": "String",
  "resourceLocation": "String",
  "statusCode": "Integer",
  "error": {
    "@odata.type": "microsoft.graph.workbookOperationError"
  }
}
```

