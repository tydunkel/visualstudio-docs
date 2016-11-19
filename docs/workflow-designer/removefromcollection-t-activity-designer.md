---
title: "RemoveFromCollection&lt;T&gt; Activity Designer | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: 
  - "System.Activities.Statements.RemoveFromCollection`1.UI"
ms.assetid: 6617ba26-c8bc-4aed-b746-112bf490d288
caps.latest.revision: 6
author: "ErikRe"
ms.author: "erikre"
manager: "erikre"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# RemoveFromCollection&lt;T&gt; Activity Designer
The **RemoveFromCollection\<T>** activity designer is used to create and configure a <xref:System.Activities.Statements.RemoveFromCollection%601> activity.  
  
## The RemoveFromCollection<T\> Activity  
 The <xref:System.Activities.Statements.RemoveFromCollection%601> activity removes a specified item from a particular collection.  
  
### Using the RemoveFromCollection\<T> Activity Designer  
 The **RemoveFromCollection\<T>** activity designer can be found in the **Collection** category of the **Toolbox**, which is accessed by clicking the **Toolbox** tab on [!INCLUDE[wfd2](../workflow-designer/includes/wfd2_md.md)] (Alternatively, select **Toolbar** from the **View** menu, or CTRL+ALT+X.)  
  
 The **RemoveFromCollection\<T>** activity designer can be dragged from the **Toolbox** and dropped on to the [!INCLUDE[wfd2](../workflow-designer/includes/wfd2_md.md)] surface wherever activities are usually placed, such as inside a <xref:System.Activities.Statements.Sequence>. This creates a <xref:System.Activities.Statements.RemoveFromCollection%601> activity with a default <xref:System.Activities.Activity.DisplayName%2A> of RemoveFromCollection<Int32\>. The <xref:System.Activities.Activity.DisplayName%2A> value can be edited in the header of the **RemoveFromCollection<T\>** activity designer or in the **DisplayName** box of the property grid. The other properties must be edited on the property grid.  
  
### The RemoveFromCollection<T\> Properties  
 The following table shows the <xref:System.Activities.Statements.RemoveFromCollection%601> properties and describes how they are used in the designer.  
  
|Property Name|Required|Usage|  
|-------------------|--------------|-----------|  
|<xref:System.Activities.Activity.DisplayName%2A>|False|The optional friendly name of the <xref:System.Activities.Statements.RemoveFromCollection%601> activity. The default is the RemoveFromCollection<Int32\>.<br /><br /> Although the <xref:System.Activities.Activity.DisplayName%2A> is not strictly required, it is a best practice to use one.|  
|<xref:System.Activities.Statements.RemoveFromCollection%601.Item%2A>|True|The item to add to the **Collection\<T>**. This item is of type *T*, which is of type *TypeArgument*. To specify the item, type in a Visual Basic expression in the property grid.|  
|<xref:System.Activities.Statements.RemoveFromCollection%601.Collection%2A>|True|The collection to which the item should be added. This collection is of type **ICollection<TypeArgument\>.** To specify the collection, type in a Visual Basic expression in the property grid.|  
|*TypeArgument*|True|The type T of the items contained in the <xref:System.Collections.Generic.ICollection%601>. By default, this *TypeArgument* type is set to **Int32**. To change the type, change the value of the *TypeArgument* in the combo box in the property grid.|  
|<xref:System.Activities.Activity%601.Result%2A>|False|A value that indicates whether the specified item was removed from the collection. To specify a variable to bind to the result, type in a variable in the property grid|  
  
## See Also  
 [Collection](../workflow-designer/collection-activity-designers.md)   
 [AddToCollection\<T>](../workflow-designer/addtocollection-t-activity-designer.md)   
 [ClearCollection\<T>](../workflow-designer/clearcollection-t-activity-designer.md)   
 [ExistsInCollection\<T>](../workflow-designer/existsincollection-t-activity-designer.md)