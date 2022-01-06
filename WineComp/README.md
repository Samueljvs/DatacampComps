# Link to Analysis [here](https://samueljvs.github.io/Competition-Oct/)


## 📖 Background
Your company owns a chain of stores across Russia that sell a variety of alcoholic drinks. The company recently ran a wine promotion in Saint Petersburg that was very successful. Due to the cost to the business, it isn’t possible to run the promotion in all regions. The marketing team would like to target 10 other regions that have similar buying habits to Saint Petersburg where they would expect the promotion to be similarly successful.

### The data
The marketing team has sourced you with historical sales volumes per capita for several different drinks types.

- "year" - year (1998-2016)
- "region" - name of a federal subject of Russia. It could be oblast, republic, krai, autonomous okrug, federal city and a single autonomous oblast
- "wine" - sale of wine in litres by year per capita
- "beer" - sale of beer in litres by year per capita
- "vodka" - sale of vodka in litres by year per capita
- "champagne" - sale of champagne in litres by year per capita
- "brandy" - sale of brandy in litres by year per capita


```{r message = FALSE}
library(tidyverse)
library(skimr)
data <- readr::read_csv('./data/russian_alcohol_consumption.csv')
skim(data)
```


## 💪 Competition challenge

1. Recommend 10 additional regions they should select for the promotion.
2. Tell the story that supports your recommendations.


## 🧑‍⚖️ Judging criteria

Recommendations (30%).
- Quality of recommendations - how clear and well presented the recommendation is.
- Validity of recommendation - is it a fair thing to conclude from the data?
- Number of insights found.

Story telling (30%).
- How well the data and insights are connected to the recommendation.
- How the narrative and whole report connects together.
- Balancing making the report in depth enough but also concise.

Visualizations (20%).
- Appropriateness of visualization used.
- Clarity of insight from visualization.

Votes (20%).
- Up voting - most upvoted entries get the most points.


## ✅ Checklist before publishing into the competition
*(hint: Press "share" to publish your workbook. Make sure your workbook is set to Public Access)*
- Rename the title of this workbook to make it descriptive of your work.
- Remove redundant items like the judging criteria so the workbook is focused on your story.
- Make sure the workbook reads well and explains how you found your insights.
