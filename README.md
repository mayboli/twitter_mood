# twitter_mood

Tools: Jupyter Notebook, Tweepy, Numpy, Pandas, Matplotlib, VADER

In order to analyze the sentiments of five different media sources on Twitter, I pulled the 100 most recent tweets using Twitter's API and then used VADER to analyze the sentiments to compare the "compound" score of the different sources with -1 being negative, 0 as neutral, and 1 as positive. 

Looking at the scatter plot, there are data points all over the graph showing that all the media sources have tweets that vary widely from super positive +1 to super negative -1, but also have tons of data points that are neutral since the grid line for zero is completely covered. 

Copmaring the scatter plot with the bar graphs, the average sentiment of all media sources is very close to zero, which means that the average sentiment they want to send out is fairly neutral. 

After running the analysis for 3 different days and multiple times during the day, the average sentiment for each media source can change rapidly even in intervals of 5 minutes! For example, a media source can have a 0.1 compound and then 5 minutes later, it will be -0.05, then 5 minutes later it'll be 0.01. 