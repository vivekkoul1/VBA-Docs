---
title: ToggleButton.HoverForeTint property (Access)
keywords: vbaac10.chm14617
f1_keywords:
- vbaac10.chm14617
ms.prod: access
api_name:
- Access.ToggleButton.HoverForeTint
ms.assetid: 81b67e89-3ae9-941f-4830-fcdbf02afd9e
ms.date: 03/05/2019
ms.localizationpriority: medium
---


# ToggleButton.HoverForeTint property (Access)

Gets or sets the tint applied to the theme color in the **HoverForeColor** property of the specified object. Read/write **Single**.


## Syntax

_expression_.**HoverForeTint**

_expression_ A variable that represents a **[ToggleButton](Access.ToggleButton.md)** object.


## Remarks

The **HoverForeTint** property contains a numeric expression that can be used to lighten the theme color in the **HoverForeColor** property. The default value of the **HoverForeTint** property is 100, which is neutral, and does not change the theme color. 

To lighten the color, first determine the percentage by which to lighten from 1 to 100, and then subtract that value as a whole number from 100 and use the remainder. For example, to lighten the theme color tint by 75%, subtract 75 from 100 and use the remainder, which is 25.

This property is not surfaced in the property sheet.


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]