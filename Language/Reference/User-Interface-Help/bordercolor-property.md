---
title: BorderColor property
keywords: fm20.chm5225009
f1_keywords:
- fm20.chm5225009
ms.prod: office
api_name:
- Office.BorderColor
ms.assetid: f5718e93-55fa-e3c6-5359-c9ccc7c7a76c
ms.date: 11/15/2018
ms.localizationpriority: medium
---


# BorderColor property

Specifies the color of an object's border.

## Syntax

_object_.**BorderColor** [= _Long_ ]

The **BorderColor** property syntax has these parts:

|Part|Description|
|:-----|:-----|
| _object_|Required. A valid object.|
| _Long_|Optional. A value or constant that determines the border color of an object.|

## Settings

Use any integer that represents a valid color. You can also specify a color by using the [RGB](../../Glossary/glossary-vba.md#rgb) function with red, green, and blue color components. The value of each color component is an integer that ranges from zero to 255. For example, you can specify teal blue as the integer value 4966415 or as RGB color component values 15, 200, 75.

## Remarks

To use the **BorderColor** property, the **BorderStyle** property must be set to a value other than **fmBorderStyleNone**.

**BorderStyle** uses **BorderColor** to define the border colors. The **SpecialEffect** property uses [system colors](../../Glossary/glossary-vba.md#system-colors) exclusively to define its border colors. For Windows operating systems, system color settings are part of the **Control Panel** and are found in the **Appearance** tab of the **Display** folder. In Windows NT 4.0 or later, system color settings are stored in the **Color** folder of the **Control Panel**.

## See also

- [Microsoft Forms examples](examples-microsoft-forms.md)
- [Microsoft Forms reference](reference-microsoft-forms.md)
- [Microsoft Forms concepts](concepts-microsoft-forms.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]