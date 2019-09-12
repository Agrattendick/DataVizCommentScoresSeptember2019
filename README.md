# Effects of Hiding Comment Scores in /r/formula1
# r/dataisbeautiful's DataViz Battle for September 2019

## Background
For september 2019 Reddit's r/dataisbeautiful's DataViz Battle's dataset deals with the effects of hiding scores in Reddit's r/formula1.

## Data Collection
This dataset is large. Unsure about the best way to import it. Ended up pulling the raw data from the webpage, spliting it into a list, and transforming that list into a dataframe. To ensure nothing in that code is ever acidently deleted, the dataframe was saved to a csv file.

## Data Analysis
Need to find out what this dataset says about the number of likes when that number is hidden (do people like a post just because other people aready did?). The best angle to start with is the total number of likes while that number is still hidden, and compare it to the total number of likes after the number is avaiable for all. Then it's wise to see if the amount of time the number of likes was hidden matters. 

Initial data analysis shows that hiding comment's scores has little effect on scores, but this seems to occur because most posts don't go viral* and only get a score from -3 to 3. Examining scores outside this range might be the best option, with the understanding that most posts never get anywhere.


(* Not sure reddit shows posts that score higher more often, though they likely do get shared on other social media platforms more. Viral might not be the best term here, but it seems accurate enough)
## Links
[r/dataisbeautiful DataViz Battle for September 2019](https://www.reddit.com/r/dataisbeautiful/comments/d0oh2m/battle_dataviz_battle_for_the_month_of_september/)

[Dataset of comment information](https://raw.githubusercontent.com/RedditFormula1/Data/master/commentdata.dat)
