![Preview](https://s3.tradingview.com/snapshots/n/N8Zr3ReA.png)

Library  `”StrategyDashboards”`

In my strategies, so far private, but not about that, I constantly use dashboards, which clearly show how my strategy is working out.

Of course, you can also find a number of these parameters in the standard strategy window, but I prefer to display everything on the screen, rather than digging through a bunch of boxes and dropdowns.

At the moment I am using 2 dashboards, which I would like to share with you.

1. `monthly(isShow)`
This is a dashboard with the breakdown of profit by month in per cent. That is, it displays how much percentage you made or lost in a particular month, as well as for the year as a whole.
Parameters:
  `isShow (bool) - determine allowance to display or not.`

2. `total(isShow)`
The second dashboard displays more of the standard strategy information, but in a table format. Information from the series “number of consecutive losers, number of consecutive wins, amount of earnings per day, etc.”.
Parameters:
   `isShow (bool) - determine allowance to display or not.`

In future:
 - Add ability to customize color scheme
 - Add ability to provide own data in total`s dashboard
 - Add ability to change positions of dashboard