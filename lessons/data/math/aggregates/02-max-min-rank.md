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
There's also `=MAXA()` and `=MINIFS()` etc.

## Practice
Use the same campaign donations data from the [COUNT/SUM lesson](01-count-sum.md) and answer the following questions:
1. What is the greatest amount donated to Democrats?
2. What is the least amount donated by a corporation?
3. What is the rank of the donation from Freedom Foundation?

---

### Speaking of rank, here's a good example of bad reporting

[Miami Ranks Second-Worst in Nation for Income and Poverty Level, Census Survey Says](http://www.miaminewtimes.com/news/miami-ranks-second-worst-in-country-for-income-and-poverty-level-census-survey-says-9689540)

>__Of the top 25 metro areas__, Miami [has the second-lowest median household income](https://www.census.gov/newsroom/press-releases/2017/acs-single-year.html?intcmp=s1-acs) __in the U.S.__ According to the Census Bureau's latest ... Survey, the median household earned only $51,362 per year, putting the Magic City just a measly $247 ahead of Tampa, the metro area with __the nation's__ lowest median income.  
by Jessica Lipscomb, Miami New Times, Sep 2017

#### What happened here?
The reporter began by comparing Miami to other cities among 25 most populous metro areas in the U.S., then switched the scope and labeled Miami and Tampa the lowest in the entire nation, instead of just lowest among the 25 largest cities.

## Next: [Averages](../averages/readme.md)
