# Project Data Visualization [COM-480]

**Team CSS** 

| Member | SCIPER |
|--------|--------|
| Cadillon Alexandre | 288684|
| Sabaa Karim | 269647 |
| Shabaan Abed Alrahman | 237731|


## Milestone 1

### Dataset

We decided to use a dataset from [Kaggle](https://www.kaggle.com/) as suggested. The dataset is called [European Soccer Database](https://www.kaggle.com/hugomathien/soccer). It's composed of data about teams, players and matches of 11 European countries teams. It contains the data of +10,000 players and +25,000 matches from 2008 to 2016. Players and teams attributes are sourced from EA Sports's FIFA video game series. The dataset has a lot of specific attributes that we won't need, as for example a player's prefered foot or a squad's formation, thus we will only use a subset of it to tackle our topic that we're going to introduce in the next section.
The dataset is fairly clean, so we won't need much of preprocessing, but it contains many different tables with a lot of attributes that we won't need, which makes the data exploration a bit more tedious. We might end up needing to cross referencing our dataset with others to tackle our topic. 

### Problematic:
Our inspiration comes from the [Too-Much-Talent Effect](https://journals.sagepub.com/doi/10.1177/0956797614537280), a study published in Psychological Science Journal. Whether we're trying to build a sports team or a team of engineers, most people will choose talent as their top criteria in recruting. But does grouping together individuals only on the basis of talent guarantee the best possible performance ? That's what the study was about, they looked into the relationship betweet team member's individual talents and team performance. They studied around 400 football matches from the 2010 and 2014 world cup. Surveys have shown that 37% of people believe that it's a linear relationship, the more stars in a team there is, the more successful it becomes. The result of the study have shown that individual talent helps the team's performance but only up to a certain point then it starts having a negative effect. We would like to induct this study topic on our dataset and to produce an interactive visualization for people who are unaware of this effect and for the 37% percent who don't believe it.

### Pre-processing of the dataset:
We are interested mainly in 3 values that we need to extract and compute:
* How successful a team is:
    We could extract this value by looking on how many matches did a team win and by how much score difference. We could count goals scored on the opponent's turf counts as double. We would most likely only compare between teams in the same league, as some leagues are more challenging than others.
* How talented a player is:
    We could use fifa's overall score of an individual player.

### Related work:

[The Too-Much-Talent Effect: Team Interdependence Determines When More Talent Is Too Much or Not Enough](https://journals.sagepub.com/doi/10.1177/0956797614537280): Roderick I. Swaab, Michael Schaerer, Eric M. Anicich, Richard Ronay, Adam D. Galinsky
