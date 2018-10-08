# Count, Sum, Difference

## How Many?
Use the `COUNT` function to answer the question, "how many?" It returns the number of values in a dataset or in a given range of cells. To take inventory of how many items there are in a given set of values and/or in a given range, use the following function:

```
=COUNT(values)
=COUNT(range)
```
or
```
=COUNT(value1, value2, range1, range2 ...)
```

Here, _range1_ is the range of values to consider when counting, and _range2, range3..._ are optional, additional ranges to include.

### Example
```
COUNT(A12:A94, B3:B57)
```

---

## How Much?
Use the `SUM` function to answer the question, "how much?" It returns the sum of a series of numbers and/or cells.
```
=SUM(value1, value2, value3)
```

### Example
```
=SUM(A2:A100)
=SUM(1,2,3,4,5)
=SUM(1,2,A2:A50)
```

Here, _value1_ is the first number or range to add together, and _value2, value3..._ are optional, additional numbers or ranges to add to value1.


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

## Difference

