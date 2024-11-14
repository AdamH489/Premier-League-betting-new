# Premier-League-betting-new
I created an excel spreadsheet that allows the user to look at statistics relating to Premier League football to help inform potential betting decisions.

I predicted the results of Premier League football matches in the 2024/25 season utilising complex statistical methods using an excel workbook. I will details the contents of the excel workbook, but I also recommend that you look through to understand the formulae and how I calculated varying parts of the workbook.

The excel workbook has 11 sheets:

Dashboard: Where the key information regarding expected goals of each team is, percentage chance of each team winning or a draw, percentage cover spread, fractional odds of each team winning and moneyline edge for each team and monte carlo simulation results for each team. The dashboard is structured so that the data in each area is changed if you change the home and away team.

monteCarlo: This sheet runs the monte carlo simulations which helps to determine the probability of each team winning, data which is then displayed in the dashboard.

teamStats: This sheet includes data on past information for games throughout the season with home team, away team, expected goals for each team and number of goals scored for each team. Using this information, I also found the average number of goals for a home team per game and average goals conceded for the home team and the same information for the away team.

homeStats: This shows the same data as teamStats, however teamStats shows the data in chronological order and this sheet shows it in alphabetical order for home teams. homeStats2 is the same data as homeStats except homeStats has a live connection to the home results in 2023/24.

awayStats: This shows the same data as teamStats, however shows the data in alphabetical order for away teams. awayStats2 is the same data as awayStats except homeStats has a live connection to the away results in 2023/24.

averageStats: This shows the average home goals for and against and the average away goals for and against for each team in the league.

seasonalStats: This shows many stats for each team in the league.

pDist: This shows the poisson distribution for the home and away team calculating the probability of a home win, draw and away win; it also shows the home cover and away cover.

teamNames: This sheet shows a list of all the team names in the league.

A few advantages of this workbook is that you can access the information for various teams easily through the dashboard and also as the data has live connections, the data is added as the season progresses meaning that yo don't have to manually type in the data when a new weeks of games are played. In additon, there are live connections to websites which show the results for the latest games meaning that I don't have to manually update the spreadsheet for new data. The only downside is that the user must look up the odds themselves and input into the dashboard to see if there is a money line edge for the specific fixture they're viewing.
