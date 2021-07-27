# Capstone Project: Measurement and Analysis of Trending YouTube Videos

Youtube is the second most popular social media platform with 2.3 billion users worldwide after Facebook. Users watch over 1 billion hours of videos daily which is around 8.4 minutes per day per person. It has gained popularity over the years since 2005 due to its simplicity that makes it easy for content creators to upload their videos to a wide audience globally.

The content loaded is not just limited to a particular niche but you can find anything on a topic you are interested in. Try searching for the most absurd topic and you will definitely find content on it.

Youtube trending videos capture viewers attention for a short period of time after it’s been uploaded. Some of these videos would trend for a longer period than others which would influence whether the video will be popular or not.


## Objectives: 

* Compare and analyze key aspects of trending features of Youtube videos over a period of time.
* Analyze patterns that can be used as a guide for uploading videos by content creators.
* Help content creators determine characteristics of videos that will or will not trend on YouTube.


### Data Collection 
The dataset used was from trending videos from 14th November 2017 - 14th June 2018. This dataset was mostly used for analysis to get the features of trending videos. Reference data: (https://www.kaggle.com/muskangoyal2104/youtubedata)

Additionally for the predictive model, I selected data that had videos uploaded from 21st December 2020- 9th January 2021 but did not necessarily trend. Reference data: (https://www.kaggle.com/wchaktse/data-of-5132-youtube-videos)


### Data Cleaning
The data didn’t have any null objects. I added columns that would be useful for exploratory analysis and changed the object types of some of the columns.


## Observations: ##
* On average, a video takes 7 days to trend from the date it is published and 75% percent of the videos that were published took 3 days to trend. However we seem to have a major outlier as there was a video that took 4,215 days of it being published to trend. This affected the mean and standard deviation.
* Most trending videos had an average of 266 tags total. The minimum had 2 tags and the maximum had 1,476 tags. 75% of the trending videos had 431 tags.
* The trending videos had an average title count of 63 words, 75% of the videos had 81 words.
* The trending videos had an average description count of 938 words, 75% of the videos had 1,251 words.
* The average number of views for trending videos was 1.32 million with a 75% percentile of 647,692 views. Interestingly, there’s a trending video that had 117 views and the highest number of views received was 424.5 million.
* The average number of likes for trending videos was 37,884. Minimum number of likes was zero and the maximum number of likes was 5.61 million translating to 1.3% of the maximum number of viewed videos.
* 46.5% of trending videos trend after one day of it being published. This number gradually decreases as the days go by. This is a very short life span meaning if you haven’t captured your audience by day 5, there’s a 14% chance that your video will trend post publish date.
* The number of views gradually increased from Saturday having the lowest views, and Friday having the highest views.
* Disabling the rating feature of a Youtube video has a drastic effect on the number of views, likes and the difference in dates it trends from the publish date. This is one feature that should not be disabled for maximum viewership.
* Putting the year of the published date seems to be quite popular in tags. Other popular words in tags of trending videos are news, new, show, latest, best, how, vs, de are also popular tags that one can incorporate in your tags. Surprisingly, a number of videos that didn’t have tags made it to the trending videos. It would be interesting to see which categories these videos fall under.
* The top 3 categories with the highest views are Entertainment, People & Blogs and Music. This is definitely not a surprise indicating that most Youtube users go to Youtube for
entertainment and updates from celebrities. The least viewed category is Movies and Trailers meaning that Youtube users prefer to watch movies from other platforms rather than Youtube. Nonprofits & Activism also do not have much of a chance on Youtube as the viewer rate is quite low.


## Observations of the Prediction Model
Another data set was loaded that had YouTube videos published in 2021 so as to build a model that’s not only biased to Trending Videos. The previous data only had data with Trending videos.
* Thursday received the highest number of views compared to Friday for trending videos.
* The top category with the highest views was People & Blogs, followed by Entertainment. A new entrant in the top 5 is education showing that more people were viewing Education in 2021 compared to the previous data for 2017. News & Politics completely drops to the bottom 3 which appeared in the top 5 in the previous data.


## Conclusion
The model is based on chances seeing that the AUC score is 0.53.

Precision value is 0.92 and the recall is 1, meaning that this model is returning 92% of the data as accurate and a recall of 100%, returning a majority of positive results. 

With an AUC score of 0.53 I can say that the information is not sufficient and the following features would be a great addition to increase the AUC score:
* An analysis on the length of the videos.
* Number of channel subscribers for the trending data.
* Age of the channels.
* Tag words in the non-trending data.
* Number of videos posted in the channel.
* Comparison data within the same period of time for both the trending and non trending data to make a more accurate model
