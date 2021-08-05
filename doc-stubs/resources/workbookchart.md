---
title: "workbookChart resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# workbookChart resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List workbookCharts](../api/workbookchart-list.md)|[workbookChart](../resources/workbookchart.md) collection|Get a list of the [workbookChart](../resources/workbookchart.md) objects and their properties.|
|[Create workbookChart](../api/workbookchart-create.md)|[workbookChart](../resources/workbookchart.md)|Create a new [workbookChart](../resources/workbookchart.md) object.|
|[Get workbookChart](../api/workbookchart-get.md)|[workbookChart](../resources/workbookchart.md)|Read the properties and relationships of a [workbookChart](../resources/workbookchart.md) object.|
|[Update workbookChart](../api/workbookchart-update.md)|[workbookChart](../resources/workbookchart.md)|Update the properties of a [workbookChart](../resources/workbookchart.md) object.|
|[Delete workbookChart](../api/workbookchart-delete.md)|None|Deletes a [workbookChart](../resources/workbookchart.md) object.|
|[List series](../api/workbookchart-list-series.md)|[workbookChartSeries](../resources/workbookchartseries.md) collection|Get the workbookChartSeries resources from the series navigation property.|
|[Create workbookChartSeries](../api/workbookchart-post-series.md)|[workbookChartSeries](../resources/workbookchartseries.md)|Create a new workbookChartSeries object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|height|Double|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|left|Double|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|top|Double|**TODO: Add Description**|
|width|Double|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|axes|[workbookChartAxes](../resources/workbookchartaxes.md)|**TODO: Add Description**|
|dataLabels|[workbookChartDataLabels](../resources/workbookchartdatalabels.md)|**TODO: Add Description**|
|format|[workbookChartAreaFormat](../resources/workbookchartareaformat.md)|**TODO: Add Description**|
|legend|[workbookChartLegend](../resources/workbookchartlegend.md)|**TODO: Add Description**|
|series|[workbookChartSeries](../resources/workbookchartseries.md) collection|**TODO: Add Description**|
|title|[workbookChartTitle](../resources/workbookcharttitle.md)|**TODO: Add Description**|
|worksheet|[workbookWorksheet](../resources/workbookworksheet.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.workbookChart",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.workbookChart",
  "height": "Double",
  "id": "String (identifier)",
  "left": "Double",
  "name": "String",
  "top": "Double",
  "width": "Double"
}
```

