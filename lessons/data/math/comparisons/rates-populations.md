# Rates and Populations
Use rates to compare different sized groups on a fair scale. In journalism, rates are frequently used to compare crime rates and similar socio-demographic data.

It's not enough to say that one city has more reported crimes than another city has and therefore the former city must be a more dangerous place than the latter. To be fair, you have to account for the population of each city before you draw any conclusion. You need to know how many crimes there were per person (per capita), or proportionally, per 100,000 people.

NOTE: Per capita figures are usually deep decimal values that are too small to make much sense of. So, similar to percentage figures, which you multiply by `100`, you have to multiply per capita figures by `100,000` for them to be significant.

## To calculate the crime rate between two cities
1. Divide each city's number of crimes by the respective population figures to get a per capita count (it'll be a small decimal value).
2. Multiply that by a population segment number that both cities have in common, i.e. `1,000` or `10,000` people. For large U.S. cities, this is typically measured at `100,000` people. This step is known as _normalizing_ the data.
3. Round down the decimal places to one digit.

## Formulas
1. `=(crimes/poulation)`
2. `=(A2/B2)*100000`
3. `=ROUND((A2/B2), 1)*100000`

## Practice
Calculate the crime rate for these major U.S. cities in 2017 and 2016.

|City|2017 Pop|Violent Crime|Property Crime|2016 Pop|Violent Crime|Property Crime|
|:--|--:|--:|--:|--:|--:|--:|
|Chicago|2,706,171|29,737|88,324|2,725,153|30,126|86,960|
|Dallas|1,338,551|10,369|42,634|1,320,939|10,071|44,910|
|Houston|2,338,235|25,609|96,532|2,334,348|23,960|100,856|
|Los Angeles|4,007,147|30,507|101,618|4,007,905|28,817|99,151|
|New York|8,616,333|46,433|124,815|8,566,917|49,124|125,278|
|Philadelphia|1,575,595|14,930|48,268|1,570,826|15,534|49,334|
|Phoenix|1,644,177|12,511|60,353|1,586,611|10,700|58,552|
|San Antonio|1,520,712|10,759|73,676|1,498,642|10,754|77,786|
|San Diego|1,424,116|5,221|26,246|1,413,414|5,332|28,624|
|San Jose|1,037,529|4,188|25,323|1,041,844|3,887|24,749|

_Source: FBI Uniform Crime Reporting_
- _[Table 6: 2017 U.S. Crime by Metro Statistical Area](https://ucr.fbi.gov/crime-in-the-u.s/2017/crime-in-the-u.s.-2017/tables/table-6)_
- _[Table 6: 2016 U.S. Offenses Known to Law Enforcement by City](https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/tables/table-6/table-6.xls/view)_

## Next: [Ratios and Proportions](ratios-proportions.md)
