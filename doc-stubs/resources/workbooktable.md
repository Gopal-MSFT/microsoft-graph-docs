---
title: "workbookTable resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# workbookTable resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List workbookTables](../api/workbooktable-list.md)|[workbookTable](../resources/workbooktable.md) collection|Get a list of the [workbookTable](../resources/workbooktable.md) objects and their properties.|
|[Create workbookTable](../api/workbooktable-create.md)|[workbookTable](../resources/workbooktable.md)|Create a new [workbookTable](../resources/workbooktable.md) object.|
|[Get workbookTable](../api/workbooktable-get.md)|[workbookTable](../resources/workbooktable.md)|Read the properties and relationships of a [workbookTable](../resources/workbooktable.md) object.|
|[Update workbookTable](../api/workbooktable-update.md)|[workbookTable](../resources/workbooktable.md)|Update the properties of a [workbookTable](../resources/workbooktable.md) object.|
|[Delete workbookTable](../api/workbooktable-delete.md)|None|Deletes a [workbookTable](../resources/workbooktable.md) object.|
|[List columns](../api/workbooktable-list-columns.md)|[workbookTableColumn](../resources/workbooktablecolumn.md) collection|Get the workbookTableColumn resources from the columns navigation property.|
|[Create workbookTableColumn](../api/workbooktable-post-columns.md)|[workbookTableColumn](../resources/workbooktablecolumn.md)|Create a new workbookTableColumn object.|
|[List rows](../api/workbooktable-list-rows.md)|[workbookTableRow](../resources/workbooktablerow.md) collection|Get the workbookTableRow resources from the rows navigation property.|
|[Create workbookTableRow](../api/workbooktable-post-rows.md)|[workbookTableRow](../resources/workbooktablerow.md)|Create a new workbookTableRow object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|highlightFirstColumn|Boolean|**TODO: Add Description**|
|highlightLastColumn|Boolean|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|legacyId|String|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|showBandedColumns|Boolean|**TODO: Add Description**|
|showBandedRows|Boolean|**TODO: Add Description**|
|showFilterButton|Boolean|**TODO: Add Description**|
|showHeaders|Boolean|**TODO: Add Description**|
|showTotals|Boolean|**TODO: Add Description**|
|style|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|columns|[workbookTableColumn](../resources/workbooktablecolumn.md) collection|**TODO: Add Description**|
|rows|[workbookTableRow](../resources/workbooktablerow.md) collection|**TODO: Add Description**|
|sort|[workbookTableSort](../resources/workbooktablesort.md)|**TODO: Add Description**|
|worksheet|[workbookWorksheet](../resources/workbookworksheet.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.workbookTable",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.workbookTable",
  "highlightFirstColumn": "Boolean",
  "highlightLastColumn": "Boolean",
  "id": "String (identifier)",
  "legacyId": "String",
  "name": "String",
  "showBandedColumns": "Boolean",
  "showBandedRows": "Boolean",
  "showFilterButton": "Boolean",
  "showHeaders": "Boolean",
  "showTotals": "Boolean",
  "style": "String"
}
```

