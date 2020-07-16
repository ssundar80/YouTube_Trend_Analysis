YouTube Trends Analysis


Our Goal
Help marketing agencies and content creators better understand the latest trends on YouTube & find what drives views and virality.

Data Source
Kaggle dataset collected from YouTube API
Included country information from United States, Great Britain, Canada, Germany, France, South Korea, Japan, Russia, and Mexico
Date range was Nov. 2017- June 2018
Time zone used was GMT +1 (Glasgow, Great Britain)
Our Process and Tools
Extract- Kaggle, Excel
Transform- Python, Jupyter Notebook, SQL, Tableau
Load- Tableau
Machine Learning- Google Colab, XGBoost
Questions we looked to answer
What types of trending content are people most likely to watch and/or engage with?

Are there specific channels/events marketers should work with/sponsor?

When should content creators post their videos to have a higher chance of trending? Is there a posting strategy to consider?

Can we statistically prove the most important factors that go into making a video trend?

What did we find?
People watch music/entertainment, but engage with causes they care about

Trending happens immediately, but chances are better posting on a weekday.

Tags are critical to trending while subscribers are not as valuable

Music drives views, causes drive engagement

First 24 hours are key

Machine Learning
Instead of looking up what increases views, we wanted to see what increased engagement. Therefore, we focused on how to increase 'Like' count
Using regression methods like Lasso, Elastic Net, Ridge, and XGBoost, we were able to confine our variables to a 78-83% R square which gives us confidence in the fit of the line.
View count, dislike count, comment count, number of tags, tags in description, and external website links in description all factored into predicting higher 'Like' count.
What does it all mean?
While aligning with music video releases are a sure way to reach a wider audience, brands should also look to work with content creators that drive engagement given it may be a more cost-efficient way to reach audiences who are very leaned in

Post on weekdays to maximize opportunity for trending

Getting a video to trend is critical for movie campaigns to get incremental views

Marketers should make sure they have a good tagging strategy in place to increase their chances at gaining likes → virality

Our Slides and Visualizations can be found here: https://docs.google.com/presentation/d/1dOlPg_edCZL9FTaLHF2NVNUrv79g9obzRtLnynRUXKA/edit#slide=id.g8b9b2062a4_0_166
