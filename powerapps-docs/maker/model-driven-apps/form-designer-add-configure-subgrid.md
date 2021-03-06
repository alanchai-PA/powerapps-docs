---
title: "Add and configure a sub-grid component on a form | MicrosoftDocs"
description: Learn how to add a sub-grid on a model-driven app form
ms.custom: ""
ms.date: 08/26/2019
ms.reviewer: ""
ms.service: powerapps
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
  - "PowerApps"
author: "Aneesmsft"
ms.author: "matp"
manager: "kvivek"
tags: 
  - "Power Apps maker portal impact"
search.audienceType: 
  - maker
search.app: 
  - "PowerApps"
  - D365CE
---



<!-- note from editor: I recommend removing the hyphen from "sub-grid" based on the style guide entry for sub: https://styleguides.azurewebsites.net/Styleguide/Read?id=2700&topicid=28872. I didn't change it here because I don't know how wide an impact that might have. -->


# Add and configure a sub-grid component on a form  
A form that displays the details of a row can use a sub-grid component to display a list of related or unrelated rows in a tabular format. Makers can add and configure a sub-grid component using the form designer.

## Add a sub-grid component
You add a sub-grid component the same way as you add any other component. More information: [Add, configure, move, or delete components on a form](add-move-configure-or-delete-components-on-form.md)

## Configure a sub-grid component
These are the properties available to configure when using a sub-grid component on a form using the form designer.


|Area   |Name  |Description  |
|---------|---------|---------|
| **Display options** | **Label** | The localizable label for the sub-grid visible to users. <br /><br />This property is required.|
| **Display options** |  **Name** |  The unique name for the sub-grid that is used when referencing it in scripts. The name can contain only alphanumeric characters and underscores. <br /><br />This property is required. |
| **Display options** | **Hide on phone** |  The sub-grid can be hidden to render a condensed version of the form on phone screens. |
| **Display options** | **Show related rows** |  When selected, the sub-grid displays only rows related to the current row that is displayed on the form. <br /><br />The **Table** drop-down list is also filtered to only list tables that are related to the current table. |
| **Display options** | **Table** |  The table whose rows you want to display in the sub-grid. <br /><br />When **Show related rows** is selected, the list of tables is filtered to show only tables that are related to the current table. In addition to the table name, the name of the lookup column is also displayed in parentheses. |
| **Display options** | **Default view** |  The view of the table selected in the **Table** property that will be used to get and display the list of rows in the sub-grid. |
| **Display options** | **Allow users to change view** |  When selected, app users can change from the **Default view** to another view of the table selected in the **Table** property. |
| **Display options** | **Show all views** |  When selected, app users can change from the **Default view** to all other views of the table selected in the **Table** property. <br /><br />This property is only available when **Allow users to change view** is selected. |
| **Display options** | **Selected views** |  A list of views of the table selected in the **Table** property that app users can change from the **Default view**. <br /><br />This property is only available when **Allow users to change view** is selected and **Show all views** is cleared. |

## See also
[Overview of the model-driven form designer](form-designer-overview.md)  
[Create, edit, or configure forms using the form designer](create-and-edit-forms.md)  
[Add, configure, move, or delete columns on a form](add-move-or-delete-fields-on-form.md)  
[Add, configure, move, or delete components on a form](add-move-configure-or-delete-components-on-form.md)  
[Add, configure, move, or delete sections on a form](add-move-or-delete-sections-on-form.md)  
[Add, configure, move, or delete tabs on a form](add-move-or-delete-tabs-on-form.md)  
[Configure header properties in the form designer](form-designer-header-properties.md)  
[Add and configure a quick view component on a form](form-designer-add-configure-quickview.md)  
[Configure a lookup component on a form](form-designer-add-configure-lookup.md)  
[Using the tree view in the form designer](using-tree-view-on-form.md)  
[Create and edit columns](../common-data-service/create-edit-field-portal.md)  
