# Exploratory Data Analysing Using Youtube Video Data from Most Popular Data Science Channels

## Aims and objectives

## 1.Introduction

Founded in 2005, Youtube has grown to become the second largest search engine in the world (behind Google) that processes more than 3 billion searches per month. It is, however, generally a myth how the Youtube algorithm works, what makes a video get views and be recommended over another. In fact, YouTube has one of the largest scale and most sophisticated industrial recommendation systems in existence. For new content creators, it is a challenge to understand why a video gets video and others do not. There are many "myths" around the success of a Youtube video, for example if the video has more likes or comments, or if the video is of a certain duration. It is also worth experimenting and looking for "trends" in the topics that Youtube channels are covering in a certain niche.

Therefore, in this project will explore the statistics of around 10 most successful data science Youtube channel.

## 2.Aims and objectives
Within this project, I would like to explore the following:

- Getting to know Youtube API and how to obtain video data.
- Analyzing video data and verify different common "myths" about what makes a video do well on Youtube, for example:
- Does the number of likes and comments matter for a video to get more views?
- Does the video duration matter for views and interaction (likes/ comments)?
- Does title length matter for views?
- How many tags do good performing videos have? What are the common tags among these videos?
- Across all the creators I take into consideration, how often do they upload new videos? On which days in the week?
- Explore the trending topics using NLP techniques
- Which popular topics are being covered in the videos (e.g. using wordcloud for video titles)?
- Which questions are being asked in the comment sections in the videos
  
## Steps of the project

1. Obtain video meta data via Youtube API for the top 10-15 channels in the data science niche (this includes several small steps: create a developer key, request data and transform the responses into a usable data format)
2. Prepocess data and engineer additional features for analysis
3. Exploratory data analysis
4. Conclusions

## Tool and Technology

### Data Analysis
Python libraries like Pandas, Numpy,
### Data Visulization
Python libraries like matplotlib and seaborn
### NLP Libraries
nltk and wordcloud

## Conclusion
In this project, we have explored the video data of the 9 most popular Data science/ Data analyst channels and revealed many interesting findings for anyone who are starting out with a Youtube channel in data science or another topic:

- The more likes and comments a video has, the more views the video gets (it is not guaranteed that this is a causal relationship, it is simply a correlation and can work both way). Likes seem to be a better indicator for interaction than comments and the number of likes seem to follow the "social proof", which means the more views the video has, the more people will like it.

- Most videos have between 5 and 30 tags.

- Most-viewed videos tend to have average title length of 30-70 characters. Too short or too long titles seem to harm viewership.

- Videos are usually uploaded on Mondays and Fridays. Weekends and Sunday in particular is not a popular time for posting new videos.

- Comments on videos are generally positive, we noticed a lot "please" words, suggesting potential market gaps in content that could be filled.

