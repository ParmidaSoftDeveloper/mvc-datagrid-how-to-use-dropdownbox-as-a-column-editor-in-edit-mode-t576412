<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128583421/17.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T576412)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [OrdersController.cs](./CS/T548916/Controllers/OrdersController.cs) (VB: [OrdersController.vb](./VB/T548916/Controllers/OrdersController.vb))
* [DxDropDownBox.cshtml](./CS/T548916/Views/Home/DxDropDownBox.cshtml)
* [Index.cshtml](./CS/T548916/Views/Home/Index.cshtml)
<!-- default file list end -->
# MVC DataGrid - How to use DropDownBox as a column editor in edit mode
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/t576412/)**
<!-- run online end -->


<p>This example illustrates how to define <a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDropDownBox/">dxDropDownBox</a> with an embedded <a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/">dxDataGrid</a> for editing data in MVC via an <a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/columns/#editCellTemplate">EditCellTemplate</a>. Run the example and check the State column to see this approach in action.<br><br>For a client-side solution, please refer to the <a href="https://www.devexpress.com/Support/Center/p/T548916">dxDataGrid - How to use dxDropDownBox as a column editor in edit mode</a> example.<br><br>Click the "Show Implementation Details" link to see step-by-step instructions.</p>


<h3>Description</h3>

<p>Perform the following steps to complete this task:&nbsp;</p>
<p>1.&nbsp;Use&nbsp;<a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/columns/#editCellTemplate">EditCellTemplate</a>&nbsp;to define MVC DropDownBox for a required column.<br>2.&nbsp;&nbsp;Implement the&nbsp;<a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDropDownBox/Configuration/#contentTemplate">Template</a>&nbsp;function to define MVC DataGrid&nbsp;and handle its&nbsp;<a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onSelectionChanged">selectionChanged</a>&nbsp;event to pass selected keys to DropDownBox. In addition, handle the&nbsp;<a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDropDownBox/Configuration/#onValueChanged">dxDropDownBox.valueChanged</a>&nbsp;event&nbsp;to adjust the DataGrid selection<br>3. Use&nbsp;<a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/columns/#cellTemplate">CellTemplate</a>&nbsp;to covert an array of selected keys to a human-readable text.<br><br>For more information about MVC templates, please review the&nbsp;<a href="https://docs.devexpress.com/DevExtremeAspNetMvc/400702/get-started/configure-a-project#create-a-new-project-from-templates">Implementing Templates</a>&nbsp;help topic.</p>

<br/>


