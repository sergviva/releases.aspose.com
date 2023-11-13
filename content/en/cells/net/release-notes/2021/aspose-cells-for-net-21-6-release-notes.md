---
id: "aspose-cells-for-net-21-6-release-notes"
slug: "aspose-cells-for-net-21-6-release-notes"
linktitle: "Aspose.Cells for .NET 21.6 Release Notes"
title: "Aspose.Cells for .NET 21.6 Release Notes"
weight: 7
description: "Aspose.Cells for .Net 21.6 Release Notes – the latest enhancements, new features, and fixes."
type: "repository"
layout: "release"
family_listing_page_title: "Aspose.Cells for .NET 21.6 Release Notes"
keywords: "Aspose.Cells for .Net 21.6 Release Notes, Aspose.Cells for .Net 21.6 updates and fixes"
---

{{% alert color="primary" %}}

This page contains release notes for [Aspose.Cells for .NET 21.6](https://www.nuget.org/packages/Aspose.Cells/21.6.0).

{{% /alert %}}

|**Key**|**Summary**|**Category**|
| :- | :- | :- |
|CELLSNET-48104|Get value of SlicerCacheItem in the collection Slicer.SlicerCache.SlicerCacheItems|New Feature|
|CELLSNET-48121|Support custom style of Slicer in Xlsb|New Feature|
|CELLSNET-48053|Set user defined formulas as array-formulas and at the same time provide values as calculated results for those formulas|New Feature|
|CELLSNET-43532|Ability to embedded  the fonts with ANSI encoding|New Feature|
|CELLSNET-48042|Retrieved formatted cell values are wrong in Excel worksheet|Enhancement|
|CELLSNET-48078|Deep copy of Workbook after calculation with CreateCalcChain setting|Enhancement|
|CELLSNET-48079|How to check if a worksheet is empty |Enhancement|
|CELLSNET-48135|Issue with protected  workbook (with a password) generated by Aspose.Cells |Enhancement|
|CELLSNET-48050|cpu hang on open workbook |Performance|
|CELLSNET-48063|Tme cost when call the api Cells.GetRowRawHeightPoint|Performance|
|CELLSNET-48046|The text offset of the shape is incorrect(arrow:quad).|Bug|
|CELLSNET-48064|The text arrangement of the default font in the text box is not correct|Bug|
|CELLSNET-48088|The overlapping part of the curve is cut off.|Bug|
|CELLSNET-48089|The left and right curves are reduced|Bug|
|CELLSNET-48060|Error using RemoveUnusedStyles function with custom styles|Bug|
|CELLSNET-48080|PivotTable can't use "值" or "Values" as column name when creating PivotTable|Bug|
|CELLSNET-48085|Hidden column heading is rendered |Bug|
|CELLSNET-48105|Textbox placement is changed while converting Excel to HTML|Bug|
|CELLSNET-48048|Exception when saving XLSX with comments to PDF format |Bug|
|CELLSNET-48082|Adding rows more than 30 using ImportCustomObjects generates corrupted file|Bug|
|CELLSNET-48086|Named range not properly created in 21.5 but worked in 21.4|Bug|
|CELLSNET-48118|Support to refresh dynamic array formulas according to the updated spilled range|Bug|
|CELLSNET-48081|Image is not shown in GridWeb|Bug|
|CELLSNET-48117|Add GridCell.GetValidation() for GridDesktop|Bug|
|CELLSNET-47627|Issues when accessing/modifying X-axis of an Excel chart using Aspose.Cells|Bug|
|CELLSNET-48041|Extracted chart is distorted in chart to image/PDF rendering |Bug|
|CELLSNET-48049|Different axis spacing when converting from xlsx workbook to emf|Bug|
|CELLSNET-48101|Chinse characters display as Rectagle Linux Docker|Bug|
|CELLSNET-48061|PowerQueries disappearing after query replacement|Bug|
|CELLSNET-48065|Re-saved file with a specific named range value causes Excel corrupted|Bug|
|CELLSNET-48067|SetChartDataRange did not recognize merged cells|Bug|
|CELLSNET-48072|Read empty chart will get a wrong chart type|Bug|
|CELLSNET-48133|Error raised by MS Excel while opening the output XLSX file|Bug|
|CELLSNET-48045|An Exception is thrown when converting svg to image|Exception|
|CELLSNET-48062|Exception raised while converting XLS to XLSX|Exception|
|CELLSNET-48074|Value cannot be null  when opening Apple numbers file|Exception|
|


## **Public API and Backwards Incompatible Changes**

The following is a list of any changes made to the public API such as added, renamed, removed or deprecated members as well as any non-backward compatible change made to Aspose.Cells for .NET. If you have concerns about any change listed, please raise it on the Aspose.Cells support forum.

### **Changes the behavior of Cell.IsErrorValue property.**

In old versions, this property only applies to formula cells. To make it consistent with other properties, from 21.6 we check non-formula cells too and if its value is error value, we also return true. User may check Cell.IsFormula property first if he only needs to check error value for formula cells.

### **Changes the behavior of Cell.Value property.**

In old versions, this property always returns DateTime object if the cell is formatted as date time and its value is numeric. From 21.6, this property returns the numeric value itself if it exceeds the maximum valid DateTime value. With this change the returned object is consistent with what shown in the formula bar of ms excel.

### **Adds Cell.IsNumericValue property.**

Provides convenient and efficient way for user to check whether one cell's value is numeric value(int, double, datetime).

### **Adds overloaded methods of Cell.SetSharedFormula()/SetArrayFormula()/SetDynamicArrayFormula().**

Support to set array formulas and shared formulas with predefined values.

### **Adds enum PdfFontEncoding.**

Represents pdf embedded font encoding.

### **Adds PdfSaveOptions.FontEncoding property.**

Gets or sets embedded font encoding in pdf.

### **Adds SlicerCacheItem.Value property.**

Returns the label text for the slicer item. Read-only.

### **Adds GlobalizationSettings.GetProtectionNameOfPivotTable() method.**

Gets the protection name in the PivotTable.

### **Adds FileFormatUtil.FileFormatToSaveFormat method.**

Converts file format to save format.
