# XLSX-composer-
Build simple XLSX file from template XLSX file with SAP ABAP
Library build as ABAP classes, base on parsing patterns in XML XLSX file. You can build, show, send XLSX file by email using simple XLSX template, where you can set any format options at any used cell. You need to fill some cells as placeholders for your data. 
There are some restrictions:
 - no merges allowed in table cells in teplate. If you need you can merge table cell in processing
 - no formulas allowed.

I place simple example, that build, open and send by email XLSX file, filled with some differently typed fileds of internal table and  replaced placeholders.
