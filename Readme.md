# How to show custom tooltips in SpreadsheetControl

This example demonstrates how to implement custom tooltips for SpreadsheetControl cells using the [ToolTipController](https://docs.devexpress.com/WindowsForms/DevExpress.Utils.ToolTipController) component. 
Add this component to the form, assign ToolTipController to the [SpreadsheetControl.ToolTipController](https://docs.devexpress.com/WindowsForms/DevExpress.XtraSpreadsheet.SpreadsheetControl.ToolTipController) property and handle the [ToolTipController.GetActiveObjectInfo](https://docs.devexpress.com/WindowsForms/DevExpress.Utils.ToolTipController.GetActiveObjectInfo) event to build the tooltip.

Use the [SpreadsheetControl.GetCellFromPoint](https://docs.devexpress.com/WindowsForms/DevExpress.XtraSpreadsheet.SpreadsheetControl.GetCellFromPoint(System.Drawing.PointF)) method to obtain a cell over which the mouse hovers and show cell data in the tooltip.