---
title: Windows.BeforeWindowClosed Event (Visio)
keywords: vis_sdr.chm11719075
f1_keywords:
- vis_sdr.chm11719075
ms.prod: visio
api_name:
- Visio.Windows.BeforeWindowClosed
ms.assetid: fb2f9b9e-a3ae-8d6e-00a1-9553629afd9f
ms.date: 06/08/2017
---


# Windows.BeforeWindowClosed Event (Visio)

Occurs before a window is closed.


## Syntax

Private Sub  _expression_ _**BeforeWindowClosed**( **_ByVal Window As [IVWINDOW]_** )

 _expression_ A variable that represents a **Windows** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Window_|Required| **[IVWINDOW]**|The window that is going to be closed.|

## Remarks

If you're using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **Event** objects, use the **Add** or **AddAdvise** method. To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. To create an **Event** object that receives notification, use the **AddAdvise** method. To find an event code for the event you want to create, see[Event codes](http://msdn.microsoft.com/library/de8f5c7a-421d-ebcf-22b6-4310a202ef64%28Office.15%29.aspx).


