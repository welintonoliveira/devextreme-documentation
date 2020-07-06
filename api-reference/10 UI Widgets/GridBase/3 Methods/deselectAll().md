---
##### shortDescription
Clears the selection of all rows on all pages or the currently rendered page only.

##### return: Promise
A Promise of the jQuery.Deferred object resolved after the selection is cleared.

---
Depending on the value of the [selectAllMode](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/selection/selectAllMode.md '{basewidgetpath}/Configuration/selection/#selectAllMode') option, this method clears selection of all rows on all pages or on the currently rendered pages only. The selection is cleared of only those rows that meet filtering conditions if a filter is applied. To clear selection regardless of the **selectAllMode** option's value or applied filters, call the [clearSelection()](/api-reference/10%20UI%20Widgets/GridBase/3%20Methods/clearSelection().md '{basewidgetpath}/Methods/#clearSelection') method.

#####See Also#####
#include common-link-callmethods