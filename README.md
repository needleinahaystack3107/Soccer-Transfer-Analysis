# Soccer-Transfer-Analysis
**A: Indroduction**
**1. Background**

As the most popular league in the world, the English Premier League is of particular interest for this analysis. 20 clubs compete every year, but only 5 different clubs have managed to win the competition over the last 10 years. We want to take a closer look at how different the player transfer policies of the serial winners are from those of the less successful clubs. Apart from the transfer market, we look into the gap between these two sets of clubs in terms of physical and tactical statistics gathered during game time.

**2. Transfer Fee and Market Value**

When a player is transferred from one club to another, the receiving club pays a ‘transfer fee’ to complete the transaction. This ‘transfer fee’ is the basis the market value which is the perceived value of that player in the market. A lot of factors influence these fees; analyzing and predicting the future values of certain players is an integral part of the financial planning for soccer clubs. Getting these details right could decide how well these clubs do for decades to come.

**3. Data Sources**

The sources that we have used are :

Fbref.com :https://fbref.com/en/comps/9/stats/Premier-League-Stats

This website hosts a collection of player features in various leagues and competitions in multiple sports. The relevant dataset we consider is a characteristic that describes the performance of a soccer player in the English Premier League

Fifa Index:(https://www.fifaindex.com/players/)

This website hosts a repository of all Club Player performance statistics and market values.

Github repository on transfer fees for each season for each league:https://github.com/ewenme/transfers/tree/master/data

This Github repository hosts all the features and data related to transfers performed within each league during the year. Our analysis only requires transfers within the English Premier League

**B: Research Questions**
B.1. Examining expenditure history of soccer clubs that have traditionally been successful and clubs that have had average performances over the last few years. How does a club’s ability to spend on player transfers impact their success? Do clubs with different success levels generally target different player profiles for acquisitions?

Owing to the nature of how players are acquired in soccer as opposed to other sport leagues, we believe this is an important question to ask. Further, given that the top 5 clubs are relatively static in the English premier league as opposed to other sport leagues where some level of performance volatility can be seen, we aim to investigate if there's a correlation between spending and on-pitch performance.

B.2. How do on-field stats differ amongst these two groups of clubs? Do synergies exist between strategies of the successful clubs? Are there things a smaller club can emulate or do differently to perform better?-

Adding to the above, it must be noted that clubs vary in budgets because of revenue differences which can be significant or marginal on a case-by-case basis. As a result, this can potentially impact a club's spending capability, the talent that they can attract, and their overall result in a season. We believe that this question is worth asking to compare how different clubs can be in terms of on-field performance, determine if commonalities exist between successful teams and suggest strategies for clubs to improve their performance.

B.3. How does a club determine a player’s value in terms of money? What are the most prominent factors influencing the valuations? Are the player's individual performances helpful in determining the market valuations?-

Given the contrasts in revenues for clubs across a league, the percentage of revenues that a club spends on player transfers can vary significantly. For example, 1% of a billion dollar club would be equivalent to 10% of a 100 million dollar club and this can potentially mean significant spending for the latter. We aim to determine if a club is valuing players appropriately and getting their money's worth. To this effect, we built a model that determines player valuation based on a player's performance indicators.

