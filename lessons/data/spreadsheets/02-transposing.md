# Transpose
When your dataset's column headers are tough to read because...
- there are lots of them
- they're each pretty long
- they're overlapping

you can swap them vertically so that they appear as a list instead. This is also true for any particular row.

## Syntax
`=TRANSPOSE(A1:Z1)` where `A1` represents the first or leftmost cell and `Z1` represents the last or rightmost cell.

## Example
Transposing puts the data from a horizontal row into a vertical column, following this logic.

|A1|B1|C1|D1|E1|F1|G1|H1|I1|J1|K1|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|

|A1|
|:--:|
|A2|
|A3|
|A4|
|A5|
|A6|
|A7|
|A8|
|A9|
|A10|
|A11|

## Transpose and sample
It's also smart to swap the first few rows in the process so you get an overview of how the data relates to the headers.

- Place your cursor in cell `A1`
- Jump to the last column in the row by pressing <kbd>SHIFT</kbd> <kbd>CMD ⌘</kbd> <kbd>RIGHT ARROW &#9658;</kbd>
- This should be the final column so note the column/cell identifier, i.e. `Z1`
- Create a new blank sheet tab, i.e. `Sheet2`
- We want the header row plus a sampling of the data by also grabbing the first 10 rows (i.e. down to row 11)...
- so in the Sheet2's `A1` cell, enter the `=TRANSPOSE()` formula...
- and call into it the range of data that you want from `Sheet1` by referencing those cells...

`=TRANSPOSE(Sheet1!A1:Sheet2!Z11)`
