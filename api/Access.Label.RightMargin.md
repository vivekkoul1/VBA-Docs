---
title: Label.RightMargin property (Access)
keywords: vbaac10.chm10237
f1_keywords:
- vbaac10.chm10237
ms.prod: access
api_name:
- Access.Label.RightMargin
ms.assetid: 03a7e1fa-bf05-dc29-be2f-f79f761d870d
ms.date: 02/28/2019
ms.localizationpriority: medium
---


# Label.RightMargin property (Access)

Along with the **TopMargin**, **LeftMargin**, and **BottomMargin** properties, specifies the location of information displayed within a label control. Read/write **Integer**.


## Syntax

_expression_.**RightMargin**

_expression_ A variable that represents a **[Label](Access.Label.md)** object.


## Remarks

A control's displayed information location is measured from the control's left, top, right, or bottom border to the left, top, right, or bottom edge of the displayed information. To use a unit of measurement different from the setting in the regional settings of Windows, specify the unit (for example, cm or in).

In Visual Basic, use a numeric expression to set the value of this property. Values are expressed in [twips](../language/glossary/vbe-glossary.md#twip).

## Example

The following example offsets the caption in the label **EmployeeID_Label** in the **Purchase Orders** form by 100 twips from the right of the label's border.

```vb
With Forms.Item("Purchase Orders").Controls.Item("EmployeeID_Label") 
 .RightMargin = 100 
End With
```


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]