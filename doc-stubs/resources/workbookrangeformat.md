---
title: "workbookRangeFormat resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# workbookRangeFormat resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List workbookRangeFormats](../api/workbookrangeformat-list.md)|[workbookRangeFormat](../resources/workbookrangeformat.md) collection|Get a list of the [workbookRangeFormat](../resources/workbookrangeformat.md) objects and their properties.|
|[Create workbookRangeFormat](../api/workbookrangeformat-create.md)|[workbookRangeFormat](../resources/workbookrangeformat.md)|Create a new [workbookRangeFormat](../resources/workbookrangeformat.md) object.|
|[Get workbookRangeFormat](../api/workbookrangeformat-get.md)|[workbookRangeFormat](../resources/workbookrangeformat.md)|Read the properties and relationships of a [workbookRangeFormat](../resources/workbookrangeformat.md) object.|
|[Update workbookRangeFormat](../api/workbookrangeformat-update.md)|[workbookRangeFormat](../resources/workbookrangeformat.md)|Update the properties of a [workbookRangeFormat](../resources/workbookrangeformat.md) object.|
|[Delete workbookRangeFormat](../api/workbookrangeformat-delete.md)|None|Deletes a [workbookRangeFormat](../resources/workbookrangeformat.md) object.|
|[List borders](../api/workbookrangeformat-list-borders.md)|[workbookRangeBorder](../resources/workbookrangeborder.md) collection|Get the workbookRangeBorder resources from the borders navigation property.|
|[Create workbookRangeBorder](../api/workbookrangeformat-post-borders.md)|[workbookRangeBorder](../resources/workbookrangeborder.md)|Create a new workbookRangeBorder object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|columnWidth|Double|**TODO: Add Description**|
|horizontalAlignment|String|**TODO: Add Description**|
|rowHeight|Double|**TODO: Add Description**|
|verticalAlignment|String|**TODO: Add Description**|
|wrapText|Boolean|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|borders|[workbookRangeBorder](../resources/workbookrangeborder.md) collection|**TODO: Add Description**|
|fill|[workbookRangeFill](../resources/workbookrangefill.md)|**TODO: Add Description**|
|font|[workbookRangeFont](../resources/workbookrangefont.md)|**TODO: Add Description**|
|protection|[workbookFormatProtection](../resources/workbookformatprotection.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.workbookRangeFormat",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.workbookRangeFormat",
  "columnWidth": "Double",
  "horizontalAlignment": "String",
  "rowHeight": "Double",
  "verticalAlignment": "String",
  "wrapText": "Boolean"
}
```

