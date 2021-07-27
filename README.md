# DataCquence-Capstone-Project - Part A #

YouTube is technically the second largest search engine in the world and following the COVID-19 pandemic, more and more traffic has been driven to YouTube as users are looking for great content to keep them entertained. 20% of users will leave a video if it hasn’t hooked them in the first 10 seconds.


As of 26th February 2020, there are 1.3 billion users on YouTube, 5 billion videos are watched daily, 30 million visitors visit YouTube daily spending an average of 11 minutes 24 seconds, 10,113 videos generated over 1 billion views and over 300 hours of YouTube videos are uploaded every minute.


The purpose of this project is to analyze the features of videos that trend on Youtube that would help content creators get more viewership for the videos they post on Youtube.


## Objectives: ##

* Does it matter in which country a video is posted for it to trend?
* Is there a correlation between likes, dislikes, comment count, tag count and view count?
* Which YouTube category has the most trending videos in duration? 
* What are the comparison ratios of the YouTube Category videos based on likes, dislikes, comment count, tag count and view count?


## The Process: ##

The Trending YouTube dataset used is YouTube data that trended August 2020 and November 2020 from USA, Japan, India, South Korea, Mexico and Brazil. 

The data was cleaned and analysed using the following libraries: Numpy, Pandas, Matplotlib and Seaborn.


## Observations: ##
* The average number of views of a trending video is 2,034,125. The median value is 620,621 which means half of the trending videos gave views that are less than that number and the other half have views larger than that number.
* The average number of likes of a trending video is 6% the number of views. The average % of dislikes is 3.39%.
* 84% of trending videos have less that 2.5 million views.
* 90% of trending videos have less than 250,000 likes.
* 98% of trending videos have less than 125,000 comments.
* The average tag count of trending videos is 197 characters. 
* It doesn’t matter which country a video is uploaded from. From the analysis, the countries had the same percentage of trending videos except for South Korea due its low internet usage. 
* There’s a strong correlation between likes, views and comment count. There’s a low correlation between dislikes and likes, views and comment count. Additionally, the tag count  has a low correlation with likes, views and comment count. This shows that dislikes and tag count does not affect the number of likes, views or comments a video gets. The graphs on ratio per video category confirms this too.
* Enduring videos have a higher chance of getting more likes, comments and views based on the analysis on the duration of trending videos.
* The top video categories with a high trend duration are:
    * Entertainment. 
    * Music.
    * Sports.
    * News & Politics.
    * People & blog.
* The YouTube audience don’t seem to care for Nonprofit & Activism as it had the lowest trend duration.





