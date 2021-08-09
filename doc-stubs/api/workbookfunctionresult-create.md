---
title: "Create workbookFunctionResult"
description: "Create a new workbookFunctionResult object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create workbookFunctionResult
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [workbookFunctionResult](../resources/workbookfunctionresult.md) object.

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
POST ** Collection URI for Microsoft.ExcelServices.workbookFunctionResult not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [workbookFunctionResult](../resources/workbookfunctionresult.md) object.

The following table shows the properties that are required when you create the [workbookFunctionResult](../resources/workbookfunctionresult.md).

|Property|Type|Description|
|:---|:---|:---|
|error|String|**TODO: Add Description**|
|value|[Microsoft.ExcelServices.Json](../resources/json.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [workbookFunctionResult](../resources/workbookfunctionresult.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_workbookfunctionresult_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for Microsoft.ExcelServices.workbookFunctionResult not found
Content-Type: application/json
Content-length: 157

{
  "@odata.type": "#Microsoft.ExcelServices.workbookFunctionResult",
  "error": "String",
  "value": {
    "@odata.type": "microsoft.graph.Json"
  }
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.ExcelServices.workbookFunctionResult"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.ExcelServices.workbookFunctionResult",
  "error": "String",
  "value": {
    "@odata.type": "microsoft.graph.Json"
  }
}
```

