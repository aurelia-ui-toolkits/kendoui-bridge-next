# kendoui-bridge-next

### Introduction

We are planning the next bridge based on the more aurelia friendly KendoUI SDK, roughly defined as a product of the collaboration between Telerik's and Aurelia-UI-Toolkits team. This initial work is focused on identifying the list of missing API points and additional support added (by Telerik's team) to aid with the two-way binding, templating and other improvements for the implementation of the Aurelia bridge.

This repository should be viewed as the container of all issues we plan to identify and properly document - to be used as the "input" for Telerik's team as well as subsequent design discusssions. The created set of documents (in the form of issues or the [associated wiki](https://github.com/aurelia-ui-toolkits/kendoui-bridge-next/wiki) articles), will later be used as the technical documentation for Aurelia-UI-Toolkit team for the future Aurelia-KendoUI-Bridge 2.0 

### Organization

A ___sequential list of issues___ is hardly the best structure to present complex information in the best readable form. So, we are proposing to use the associated project and its **["kanban" board view](https://github.com/aurelia-ui-toolkits/kendoui-bridge-next/projects/2)** as the principal method used to understand this proposal and make subsequent actions needed to implement it (see Image 1 below):

<p align=center>
  <img src="https://user-images.githubusercontent.com/2712405/29029122-8f509126-7b54-11e7-96b4-31db0d93720d.png"></img>
 <br><br>
 Image 1
</p>

This image suggests that the first task in the (currently only) project **[Definition and management of issues](https://github.com/aurelia-ui-toolkits/kendoui-bridge-next/projects/2)** (***red marker 1***) is the task **[Definition of the process used to collect all issues](https://github.com/aurelia-ui-toolkits/kendoui-bridge-next/issues/1)** (***red marker 2***)

Note that this first task is shown in the **In progress** column to indicate that the **Telerik team should start there** :smile:. Also note that is labelled as **`Definition`** to indicate that it contains the "metadata" - it is not a part of the information that lists all issues, but rather documents how to create such information.

This introduction, as stated in the paragraph above continues with the **[definition of the process used to collect all issues](https://github.com/aurelia-ui-toolkits/kendoui-bridge-next/issues/1)**. We should reach the agreement on its definition and subsequent use, before anything else - and it should be done via comments to this first task.

### Summary

We are proposing to use the GitHub based project **[Definition and management of issues](https://github.com/aurelia-ui-toolkits/kendoui-bridge-next/projects/2)** as the primary interface for all subsequent tasks that are grouped in four ***ordered*** categories **`Backlog`**, **`In progress`**, **`Done`** and **`Ready for implementation`**:

<p align=center>
  <img src="https://user-images.githubusercontent.com/2712405/29054014-6c90661c-7bc1-11e7-8640-4cd029721dae.png"></img>
 <br><br>
</p>

This process will flow as follows:

1. Aurelia-UI-Toolkits team will continue filling the **`Backlog`** category until we run out of entries.
2. Telerik team will move entries (one by one) to **`In progress category`** and star the discussion on that issues until it gets resolved by fiat from both teams. At that time it is labelled as resolved and moved to the **`Done`** category
3. Once all of the items reside in the **`Done`** category, we will move all issues from that category to the **`Backlog`** category of the **[Implementation](https://github.com/aurelia-ui-toolkits/kendoui-bridge-next/projects/3)** project.







