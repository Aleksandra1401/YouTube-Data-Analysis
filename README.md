# YouTube-Data-Analysis  
Databases for this project are found on kaggle.com and incorporate a collection of data for videos that gained a "Trending" status on Youtube.com. Description of the database collection explains how YouTube keeps the list of top-trending videos determed by combination of different factors such as the number of likes, dislikes and comments. Trending videos do not have to be videos with highest number of views.

URL https://www.kaggle.com/datasnaek/youtube-new

This database contains couple years of YouTube data for daily top-trending videos collected in 2017 and 2018 from few different countries. Countries included are United States, United Kingdom, Germany, Canada, France, Russia, Mexico, South Corea, Japan and India. Data for each country is in separate .csv files. Additionally, each country dataset has a corresponding JSON file containing categorical labels for video category. It is stressed that different category files are needed because numerical category columns represent different categories for different countries.

Since all videos are taken from the list of videos in Trending category, if we trained model for this task, we wouldn't have a testing set for it: data is from 2017 and 2018 and since YouTube updated their algorithms since then, even scraping new data wouldn't do justice. This is the main reason for not using ML algorithm for this project. However, we can still explore this dataset, as there is a lot this data can tell us about about trending videos and user behavior. I will summarize the outcome at the bottom of this notebook.

References to the sites I took code from are above the cells where the code was used. Additionally, here are some notebooks that I peaked in for the workflow:
https://www.kaggle.com/edwars/youtube-ca-trending-video-eda
https://www.kaggle.com/lordkun/clean-show (sns pairplot taken from here)
