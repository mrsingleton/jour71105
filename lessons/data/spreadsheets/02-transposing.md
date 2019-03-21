# Transpose
When your dataset's column headers are tough to read because...
a. there are lots of them
b. they're each pretty long
c. they're overlapping

you can swap them vertically so that they appear as a list instead.

## Syntax
`=TRANSPOSE(A1:Z1)`

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
