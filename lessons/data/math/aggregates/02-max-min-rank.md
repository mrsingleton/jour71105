## What's the most?
To find the greatest or highest value, use the `=MAX()` function, which returns the maximum value in a given range of numeric data cells.

|Example|
|:--|
|`=MAX(A2:A11)`|

## What's the least?
To find the smallest or lowest value, use the `=MIN()` function, which returns the minimum value in a given range of numeric data cells.

|Example|
|:--|
|`=MIN(A2:A11)`|

## How does that rank?
To find a value's place in a hierarchy, use the `=RANK()` function, which returns a specific number's position among other values in a range.

|Example|
|:--|
|`=RANK(A6,A2:A11,1)`|

### Note
By default, the rank order is ascending, meaning the highest value in the range has the top rank. To use descending order and give the lowest value the top rank, include a 1 after the evaluation range (ascending also works by including a 0 after the evaluation range).

### Tips
There's also `=MAXA()` and `=MINIF()` etc.

## Challenge
Use the same campaign donations data from the [COUNT/SUM lesson](01-count-sum.md) and answer the following questions:
1. What is the greatest amount donated to Democrats?
2. What is the least amount donated by a corporation?
3. What is the rank of the donation from Freedom Foundation?

## Next: [Averages](https://github.com/mrsingleton/jour71105/blob/master/lessons/data/math/averages/readme.md)
