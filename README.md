# Youtube-Trends

If a video's popularity is defined by trending, views, and likes, what factors determine the popularity of a Youtube video in the United States? Can a model be built that predicts, based on the title, description, and tags assigned to a video, if and when a published video will trend?

### CONTEXT
Youtube keeps a list of the top trending videos on its website that it updates every day. To determine what videos trend, it uses a combination of factors including the number of views, shares, comments, and likes (Variety Magazine). Although one would think that the algorithm used to determine trending (assuming that this is first a classification algorithm - trending or not trending - followed by a ranking algorithm to determine where the video must lie on the trending list) is fair and unbiased, there have been studies conducted that determined that certain channels get prioritized over others. A study conducted by the Youtube channel ‘Coffee Break’ in 2019 determined that Youtube creators need to get a million more views than late-night TV shows in order to appear in the Trending section (The Verge). This goes to show that the Trending is not merely a place to showcase viral videos but a hub to attract advertisers to traditional media sources.

### CRITERIA FOR SUCCESS
The project will be deemed successful if I am able to build a predictive model that can predict when a video will trend (in relation to when it was published) and performance metrics based on the title, description, and tags assigned to the video.

### SCOPE OF SOLUTION SPACE
I am only analyzing the datasets for US, Canada, and India, and am only looking at how the title, tags, and description of a video, along with popularity metrics like likes and comments affect the chances of a video trending. I am not examining thumbnails, although I am certain they play a role in deciding if a video will trend or not as well.

### CONSTRAINTS
I don’t have a dataset with videos that did not trend on Youtube. That would have made the prediction better, since I could have also turned it into a classification problem (Trend vs Did not Trend).
The data we have does not offer us a full picture of trends on Youtube, since a part of what makes videos trend on one website is it/something similar trending on another website (like Twitter/Facebook). Without knowing what other factors made a video popular/trend, it is difficult to ascertain qualitative information about what makes certain kinds of videos trend.

### STAKEHOLDERS
Youtube creators, Youtube Ad Sales team (since this research will help them decide what kind of videos should be monetized)

### KEY DATA SOURCES
Dataset by Mitchell J on Kaggle (Trending YouTube Video Statistics) which he procured by running a script to access information from Youtube’s API (included on his Github - scraper.py). The dataset contains videos trending between 11/14/2017 and 06/14/2018 and examines a series of statistics including number of likes, number of views, video description, and tags.
