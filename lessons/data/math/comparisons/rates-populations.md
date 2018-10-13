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
Calculate the crime rate for the following:

## Next: [Ratios and Proportions](ratios-proportions.md)
