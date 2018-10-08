# Count and Sum

## How Many?
Use the `=COUNT()` function to answer the question, "how many?" It returns a tally of how many __numeric__ values there are in a selection of cells or in a given range of cells, allowing you to take inventory of a certain set of values.

|Syntax|Example|
|:--|:--|
|`=COUNT(cell1,cell2,cell3...)`|`=COUNT(A3,A5,A8,A9...)`|
|`=COUNT(cell range)`|`=COUNT(A1:A11)`|

## How Much?
Use the `=SUM()` function to answer the question, "how much?" It returns a calculated sum in a selection of cells or from a given range of cells.

|Syntax|Example|
|:--|:--|
|`=SUM(cell1,cell2,cell3...)`|`=SUM(A3,A5,A8,A9...)`|
|`=SUM(cell range)`|`=SUM(A2:A11)`|

### Tips
- You can include multiple ranges and/or non-consecutive cells in these functions by separating each element with a comma.
- If you need to count data types other than numbers, i.e. text cells or blank cells, use `=COUNTA()` to _count all_ data types.
- If you need to count items based on certain criteria, use `=COUNTIF()` to only _count if_ given conditions are met.
- If you need to sum items based on certain criteria, use `=SUMIF()` to only _sum if_ given conditions are met.
- The `=SUM()` function also handles _difference_ calculations when summing negative values.

### Challenge
Use the Count and Sum functions on the following campaign donations.

|ID|Donor|Type|Recipient|Party|Amount|
|:--:|:--|:--|:--|:--|--:|
|01|Jim James|Individual|Senator Morris|Democrats|$250|
|02|Energy Corps|Corporation|Congressman Baker|Republicans|$1,800|
|03|Sky Net|Corporation|Judge Allen|Republicans|$4,000|
|04|Media Market|Corporation|Congresswoman Williams|Democrats|$6,700|
|05|Betty Andrews|Individual|RNC|Republicans|$90|
|06|George Smith|Individual|Mayor Collins|Democrats|$380|
|07|Mega Manufacturing|Corporation|Governor Roberts|Republicans|$725|
|08|Pharma Well|Corporation|Senator Davis|Republicans|$5,650|
|09|Harry Peterson|Individual|DNC|Democrats|$1,200|
|10|Virtual Malls|Corporation|RNC|Republicans|$9,463,800|

Copy and paste this data into your spreadsheet app and do the following:
1. Find how many donations there are for each party.
2. Find how many donors were individuals and how many were corporations.
3. Find how much the donors gave to each party.
4. Find how much came from individuals and how much came from corporations.
5. Find how much donation money there is overall.

---

## Count vs Sum
Here's a great way to think about the difference between counting versus summing. Think about how many units of currency there are in circulation in the United States today.

![Silvrback blog image](https://silvrback.s3.amazonaws.com/uploads/ed7f5ac0-e196-4323-bb1d-c46ecfb7fc25/usd-coins_crop_large.jpg)

![Silvrback blog image](https://silvrback.s3.amazonaws.com/uploads/3d8c214c-43b6-4c2f-a035-c1da94f6be48/usd-bills_reduced_large.jpg)

If you _count the units_, they equal __14__ -- we have the penny, nickel, dime, quarter, half-dollar, and two versions of the dollar as the [current coins](https://www.usmint.gov/mint_programs/circulatingCoins/). And then the [current treasury notes](https://www.treasury.gov/resource-center/faqs/Currency/Pages/denominations.aspx) are the one, two, five, ten, twenty, fifty and hundred dollar bills.

Yet if you add their values together:
$0.01 + $0.05 + $0.10 + $0.25 + $0.50 + $1.00 + $1.00 + $1 + $2 + $5 + $10 + $20 + $50 + $100
their _sum total amount_ is __$190.91__.

In one case you count, in the other case you sum. While you can __COUNT__ both numeric and non-numeric data, you can only __SUM__ numeric data. Why is this the case?

__IMPORTANT: When you count and/or sum, the figures that the spreadsheet displays are not actual numbers within the data, rather they are results of calculations performed on the fly, called "aggregate functions."__

---
Next: [Max, Min, Rank](02-max-min-rank.md)
---
