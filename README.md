# ABAP-XLSX-composer
Build simple XLSX file from template XLSX file with SAP ABAP. 

No need in Excel app, template can be prepared with any app, that can make XLSX files. 

You can build, show, send XLSX file by email using simple XLSX template, where you can set any format options at any used cell.

Library build as ABAP classes, base on parsing patterns in XML XLSX file.  All you need is to prepare template: fill some cells as placeholders for your data, include formatting. As result you have ready-to-use XLSX report for ABAP. 

There are some restrictions:
 - no merges allowed in table cells in teplate. If you need you can merge table cell in processing
 - no formulas allowed.

See simple example, that build, open and send by email XLSX file, filled with some differently typed fileds of internal table and  replaced placeholders.
