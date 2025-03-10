---
title: "educationAssignmentIndividualRecipient resource type"
description: "Used inside the assignment.assignTo property. When set to individual recipient list, selected students in the class will "
ms.localizationpriority: medium
author: "dipakboyed"
ms.subservice: "education"
doc_type: resourcePageType
ms.date: 07/23/2024
---

# educationAssignmentIndividualRecipient resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Used inside the [assignment.assignTo](educationassignment.md) property. When set to individual recipient list, selected students in the class receive a submission object when the assignment is published.

This resource is a subclass of [educationAssignmentRecipient](educationassignmentrecipient.md).

## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|recipients|String collection|A collection of ids of the recipients.|

## Relationships

None.

## JSON representation

The following JSON representation shows the resource type.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.educationAssignmentIndividualRecipient"
}-->

```json
{
  "recipients": ["String"]
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "educationAssignmentIndividualRecipient resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->


