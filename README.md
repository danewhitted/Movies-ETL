# Movies-ETL

We made the assumption that mostly empty (less than 90% null values) columns would not be useful and deleted them from our dataset. We reduced 191 sloppy columns down to 21 useful datafilled columns.

After dropping about 1500 movies based on box office earnings, we assumed 5500 titles would still be good enough to perform analysis.

After parsing the budget data we had dropped 30 budget values. We decided have 4700 other budget values to work with, and assumed the remaining 30 values wasn't worth the time. 

We assumed after casual observation all the dates were correct after formatting the datetime stamps.

After examing the bar chart for ratings we assumed the data made sense. The spikes we saw can be explained by people being more likely to give a whole number rating than fratctions.
