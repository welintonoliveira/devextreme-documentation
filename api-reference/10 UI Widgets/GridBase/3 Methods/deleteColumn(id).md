---
##### shortDescription
Removes a specific column from the widget.

##### param(id): Number|String
The name, index, data field, or caption of the column.

---
This method removes the first column found by either of the below:

* **Name**        
The [unique name](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/columns/name.md '{basewidgetpath}/Configuration/columns/#name') of the column.

* **Column Index**        
The index of the column in the [columns](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/columns '{basewidgetpath}/Configuration/columns/') array.

* **Data Field**        
The name of the [data source field](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/columns/dataField.md '{basewidgetpath}/Configuration/columns/#dataField') assigned to the column.

* **Caption**        
The text displayed in the column header.

#####See Also#####
#include common-link-callmethods
- [addColumn(columnOptions)](/api-reference/10%20UI%20Widgets/dxDataGrid/3%20Methods/addColumn(columnOptions).md '{basewidgetpath}/Methods/#addColumncolumnOptions')
- [deleteRow(rowIndex)](/api-reference/10%20UI%20Widgets/GridBase/3%20Methods/deleteRow(rowIndex).md '{basewidgetpath}/Methods/#deleteRowrowIndex')