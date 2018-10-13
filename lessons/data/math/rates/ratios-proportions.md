# Ratios and Proportions
You can use ratios to help your readers understand the relationship between two numbers and how things compare to one another. They typically compare two numbers and they're typically calculated in comparison to `1`. For instance, while a percentage can communicate, _In 2018, the Red Sox won 66.67% of their games_, a ratio can communicate the same quantity in a more comprehensible way by stating, _In 2018, the Red Sox had 2 wins for every 1 loss_.

To calculate ratio, divide the greater value (dividend) by the lesser value (divisor) then use the result (quotient) as the part of the ratio you compare to `1`.

`=(A2/B2)`

You can use the `&` operator to append quoted text to your result to make it read in a familiar format, such as `2:1`.
`=(A2/B2)&":1"`

Similarly, you could include phrasing within the quoted text to make it read like part of a sentence.
`=(A2/B2)&" wins for every 1 loss"`

Finally, you could surround the equation with the `=ROUND()` function to shorten the resulting figure down to two decimal places.
`=ROUND((A2/B2),2)&" wins for every 1 loss"`

## Practice
Revisit the table of 2018 MLB Standings and use column __G__ to calculate the win to loss ratio for each team.

|Team|League|Games|Wins|Losses|Win Pct|Win Ratio|
|:--|:--|--:|--:|--:|--:|--:|
|BOS|AL|162|108|54|||
|HOU|AL|162|103|59|||
|NYY|AL|162|100|62|||
|OAK|AL|162|97|65|||
|MIL|NL|163|96|67|||
|CHC|NL|163|95|68|||
|LAD|NL|163|92|71|||
|CLE|AL|162|91|71|||
|COL|NL|163|91|72|||
|ATL|NL|162|90|72|||
|TBR|AL|162|90|72|||
|SEA|AL|162|89|73|||
|STL|NL|162|88|74|||
|PIT|NL|161|82|79|||
|WSN|NL|162|82|80|||
|ARI|NL|162|82|80|||
|PHI|NL|162|80|82|||
|LAA|AL|162|80|82|||
|MIN|AL|162|78|84|||
|NYM|NL|162|77|85|||
|TOR|AL|162|73|89|||
|SFG|NL|162|73|89|||
|CIN|NL|162|67|95|||
|TEX|AL|162|67|95|||
|SDP|NL|162|66|96|||
|DET|AL|162|64|98|||
|MIA|NL|161|63|98|||
|CHW|AL|162|62|100|||
|KCR|AL|162|58|104|||
|BAL|AL|162|47|115|||

_Source: [Baseball Reference](https://www.baseball-reference.com/leagues/MLB-standings.shtml)_

## Next: [Spreadsheets](../../spreadsheets/readme.md)
