# Ratios and Proportions
It's good to use ratios to help your readers understand the relationship between two numbers and how large and small things compare to one another. They often compare two numbers and they're typically calculated in comparison to `1`.

For instance, while a percentage can communicate...

>In 2018, the Red Sox won 66.67% of their games.

a ratio can communicate the same quantity in a more comprehensible way by stating...

>In 2018, the Red Sox had 2 wins for every one of their losses.

__To calculate ratio, divide the greater value (dividend) by the lesser value (divisor) then use the result (quotient) as the part of the ratio you compare to `1`.__

## Formulas
First, apply this example formula to the respective column and row locations in your spreadsheet.  
`=(A2/B2)`

Next, use the `&` operator to append quoted text to your result to make it read in a familiar `x:1` format, such as `2:1`.  
`=(A2/B2)&":1"`

Similarly, you could include phrasing within the quoted text to make it read like part of a sentence.  
`=(A2/B2)&" wins for every one loss"`

Finally, you could surround the equation with the `=ROUND()` function to shorten the resulting figure down to two decimal places.  
`=ROUND((A2/B2),2)&" wins for every one loss"`

## Practice
A. Use column __D__ to calculate the ratio of total workers to every one minority worker at daily newspapers over the years, using the `x:1` format.

|Year|Total Work Force|Minorities In Work Force|Ratio|
|:--|--:|--:|--:|
|1980|47,000|2,300||
|1985|53,800|3,100||
|1990|56,900|4,500||
|1995|53,800|5,900||
|2000|56,200|6,700||
|2005|54,100|7,300||
|2010|41,500|5,500||
|2015|32,900|4,200||

_Source: American Society of News Editors (ASNE), [Table A: Minority Employment in Daily Newspapers](https://www.asne.org/content.asp?pl=140&sl=129&contentid=129)_

B. Revisit the table of 2018 MLB Standings and use column __G__ to calculate the ratio of wins to every one loss, using the readable format of your choice.

|Team|League|Games|Wins|Losses|Win to Loss Ratio|
|:--|:--|--:|--:|--:|--:|
|BOS|AL|162|108|54||
|HOU|AL|162|103|59||
|NYY|AL|162|100|62||
|OAK|AL|162|97|65||
|MIL|NL|163|96|67||
|CHC|NL|163|95|68||
|LAD|NL|163|92|71||
|CLE|AL|162|91|71||
|COL|NL|163|91|72||
|ATL|NL|162|90|72||
|TBR|AL|162|90|72||
|SEA|AL|162|89|73||
|STL|NL|162|88|74||
|PIT|NL|161|82|79||
|WSN|NL|162|82|80||
|ARI|NL|162|82|80||
|PHI|NL|162|80|82||
|LAA|AL|162|80|82||
|MIN|AL|162|78|84||
|NYM|NL|162|77|85||
|TOR|AL|162|73|89||
|SFG|NL|162|73|89||
|CIN|NL|162|67|95||
|TEX|AL|162|67|95||
|SDP|NL|162|66|96||
|DET|AL|162|64|98||
|MIA|NL|161|63|98||
|CHW|AL|162|62|100||
|KCR|AL|162|58|104||
|BAL|AL|162|47|115||

_Source: [Baseball Reference](https://www.baseball-reference.com/leagues/MLB-standings.shtml)_

## Proportion
Use proportions to phrase things in ways that help readers comprehend scale. When two ratios are equal, they are said to be proportional. For instance, a proportion can be written as "twenty is to twenty-five as four is to five" or `20:25 = 4:5`.

[Read all about ratio and proportion](https://www.mathplanet.com/education/algebra-1/how-to-solve-linear-equations/ratios-and-proportions-and-how-to-solve-them)

## Next: [Spreadsheets](../../spreadsheets/readme.md)
