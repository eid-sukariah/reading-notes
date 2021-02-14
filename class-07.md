## Domain Modeling: Domain modeling is the process of creating a conceptual model in code for a specific problem
A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.
Property|	Data|	  Type|
----------------------------
epicRating|	1 to 10|	Number|
hasAnimals|	true or false|	Boolean|

## table:
The `<table>` element is used to create a table
The `<tr>` stands for table row
The `<td>` stands for table data.
The `<th>` stands for table heading.
The **colspan** attribute can be
- used on a `<th> or <td>` element and indicates how many columns that cell should run across
- The **rowspan** attribute can be used on a `<th> or <td>` element to indicate how many rows a cell should span down the table.
- for long table: use `<thead> <tbody> <tfoot>`s help *people* who use screen readers and *also allow you* to style these sections in a different manner than the rest of the table