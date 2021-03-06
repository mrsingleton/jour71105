# Percent
Readers and viewers can grasp the idea of *parts of a whole* far better than they can make sense of raw numbers or decimals that don't have context.

![The "Pie I have eaten" pie chart](https://i1.wp.com/flowingdata.com/wp-content/uploads/2008/09/Pie-I-have-Eaten.jpg)

A percent is a part of a whole, a distinct amount of a complete unit. Since parts of a singular unit amount to less than `1`, such as `0.25`, the decimal figures are multiplied by `100` so that they become more easily understandable, i.e. `25%`.

## Writing Tip
For clarity, when writing about numbers, convert odd sounding decimals into percentages or fractions or plain old English terms.

|Percent|Decimal|Fraction|English|
|:--|--|:--:|--|
|50%|0.5|1/2|half|
|33.3%|0.333...|1/3|one third|
|25%|0.25|1/4|one fourth|
|60%|0.6|3/5|three fifths|
|10%|0.1|1/10|one tenth|
|90%|0.9|9/10|9 out of 10|

### General Tip
Always ask, part of how much?

<img src="https://i.imgur.com/2W9uYA7.gif" width="*" height="350">

## To calculate percent
1. Determine the whole
2. Divide the part by the whole
- Note that the resulting figure will be zero point something, `0.xxx`
3. Multiply that by `100`

### Skill Drill
In 2013, a national survey of journalists found reporters idendified politically as follows:

|Dem|Rep|Ind|Oth|
|--|--|--|--|
|303|77|542|158|

Convert these figures into percentages.

_Source: [Washington Post news story](https://www.washingtonpost.com/news/the-fix/wp/2014/05/06/just-7-percent-of-journalists-are-republicans-thats-far-less-than-even-a-decade-ago/?utm_term=.e12e3df8a021) that cited an [Indiana University study](http://archive.news.indiana.edu/releases/iu/2014/05/2013-american-journalist-key-findings.pdf)
(see pg. 12)_

## Percent as a spreadsheet formula
Now try your calculations using a spreadsheet tool and this formula:
`=(A2/B2)*100`

### Percent Spreadsheet Setup

| Part | Whole | Pct |
|--:|--:|--:|
|`A2`|`B2`|`=(A2/B2)*100`|
|`A3`|`B3`|`=(A3/B3)*100`|
|`A4`|`B4`|`=(A4/B4)*100`|

Alternatively, divide the two figures, then use the spreadsheet tool's number formatting options under the __FORMAT » NUMBER__ menu to convert the result into a percent and to change the amount of decimal places.

## Practice
A. Copy and paste the following table of 2018 MLB Standings into a spreadsheet and use column __F__ to calculate the win percentage for each team.

|Team|League|Games|Wins|Losses|Win Pct|
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

- Which teams were better than 55 percent?
- Which ones made it to the postseason?

B. Copy and paste the following table of employees at daily newspapers into a spreadsheet and use column __D__ to calculate the percentage of minorities for each year.

|Year|Total Work Force|Minorities In Work Force|Pct Minority|
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

---

### Percent of what whole?
News stories frequently mention *millions* this and *billions* that, so it is crucial to comprehend the difference in scale.

In your estimation, one million `1m` is what percent of one billion `1b`?

- 10%
- 1%
- 0.1%
- 0.01%

---

### Is over Of

To figure out what percentage something __is of__ something else, use good old algebra...

`is over of = x% over 100`

and

`is * 100 over of = x%`

so

`1m * 100 over 1b = x%`

or

`100,000,000 over 1,000,000,000 = 0.1%`

i.e.

`One million is just a fraction of a percent of one billion (less than one percent).`

hmm...

- One million seconds is 11 days
- One billion seconds is 31 years
- One trillion seconds is 317 centuries

![Animated gif image of Kobe Bryant reacting to something in disbelief](https://i.imgur.com/1WFhioY.gif)

---

## Next: [Percent Change](02-percent-change.md)
