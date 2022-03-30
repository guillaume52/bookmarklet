# This is bookmarklet will inject javascript onto a GA template and create a tbale that allows to calculate AB tests stats.
#Defaulted to p=0.05
#You can select differnt metrics and group by several dimensions (as many as GA allows)

The JS code needs to be added as a bookmark on your browser (tested only on Safari and Chrome), place the JS in the URL input box. when you click on the bookmark, the code gets injected on the page.
The GA dashboard should be constructed as follow:
Flat table:
Dimensions:First column should be the variant of the test, then you can have as mnay dimension as you please.
Metrics: any metrics you like howver this is built for non binomial data so calculated metrics or averged metrics will either not work or returned wrong results.
template below
https://analytics.google.com/analytics/web/template?uid=kNwNceGdQUW50cR9P-74hw
