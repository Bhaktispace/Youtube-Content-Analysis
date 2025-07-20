# Youtube Content Analysis
<img src="https://github.com/Bhaktispace/Youtube-Content-Analysis/blob/main/graphs/Main.png?raw=true">

# Business Problem
With millions of videos uploaded online, creators need data driven strategies to enhance content visibilty, engagement and emotional resonance. This project uncover patterns between video metadata (views, likes, keywords) and comment sentiment to identify what makes a video successful.

# Data Overview
Working with two main datasets:
* video-stats.csv - Contains metadata for each video, such as views, likes, keywoord, comment counts and publissh date
* comments.csv - Contains the top 10 releveant comments per video along with their sentiment and the number of likes.

# Project Gaols
* Identify high-performing keywords that drive views and engagement
* Understand the relationship between viewer sentiment and video popularity
* Evaluate how comment quality and sentiment correlate with video metrics
* Develop a scoring system to rank video engagement
* Provide insights to help optimize future content strategies

# KPIs to Consider
| KPI | Description
|---|---
|Average Views per Keyword| Measures the popularity by keyword topics
|Like to View Ratio|How compelling videos are to the viewers
|Comment Count|Reflects how engaging a video is
|Engagement Score|Composite metric combining views, likes and comments
|Average Sentiment Score| Tracks emotional response to videos
|Monthly Trends|How enagagement and sentiments changes over time

# Tools and Technology USed
Python

# Key Observations and Recommendations
* **Top 5 Keywords by Average Views**

![image alt](https://github.com/Bhaktispace/Youtube-Content-Analysis/blob/main/graphs/Top%205%20Keywords.png?raw=true)

This bar chart visualizes the average video views for the top 5 keywords, providing insights into which content theme resonates with the viewers.
Key observations:
1. Dominance of google and animal: This suggests that the content related to these broad categories consistently attracts a very large audience.
2. Strong performance of MR Beast: This indicates a dignificant impact of individual creator.
3. Moderate Performance of bed: It represents substantial vieweship, hinting at its popularity. The main viewership is because of the video of songs BED but there are some videos for actual Bed. 
4. Lower Performance of Music: Music is at the bottom of the top 5 average views. Its position relative to the other keywords suggests that music content is popular and more engaging.

Potential Implications and Recommentations:
1. Some investigation needs to happen to understand how the categorization of viedos happen for various keywords.
2. Investing in Google and Animal content keywords appear to be high yield for maximizing average views.
3. The success of MR Beast emphasizes the importance of understanding and potentially collaborating with the creators or developing strong brand to attract viewers.
4. Further investigation would be needed to categorization of this keyword to understand it is miscategorization of the keyword bed instead of music.
5. For music content, it might be beneficial to analyze what specific types of music, artists, or video formats perform best to optimize engagement and average views. Strategies could include focusing on trending artists, specific genres, or unique video concepts

* **Videos with high Like to View Ratio and their Keywords**

![image alt](https://github.com/Bhaktispace/Youtube-Content-Analysis/blob/main/graphs/high%20like%20to%20view%20ratio.png?raw=true)

This metric is crucial as it not only highlights the numbers of viewers it attracts but gives the information how many are engaging with the video.

Key Observations:
1. The first video on education has a high like to view ratio given the relatively low view count, this shows that education videos connect with the audience better.
2. Gaming dominates the top engaged content, taking 3 spots out of 5. This indicates that the gaming community is highly engaged and passionate.
3. It is important to note that a high like to view ratio do not necessarily have high absolute view counts 21.9% is a high engagement ratio. This emphasizes that high like to view ratio is a mesure of content qualitty and viewer satisfaction.
4. The presence of Arabic content in the top 5 suggests strong engagenment within speicifc language community.

Potential Implications and Recommendations:
1. For content creators, focusing on the like to view ratio can be powerful strategy for identyfying impactful videos. 
2. The high engagement for education, gaming and chess indicates that creating content for specific, passionate comuunites can yield high satisfaction rates.

* **Keywords that generates most and least comments**

This visualization of the keywords that generates the highest and the least comments serves as an indicator of interaction by the viewers.

Key Observations:
1. Mr Beast dominates the Comment engagement. This indicates an extremely active and engaged community around the creator. The content maybe creates lot of discussions, and fan interactions.
2. Google and History drive significant discussion. This suggests that content related to historical topics and tech with google encourage viewers to share their thoughts, ask question and engage discussions.
3. Animals and Bed show moderate engagement. This indicates that the comments are way less than the other ones but they still represent substantial interactions.
4. There is a significant difference in the number of interactions with the top and the bottom performing keywords. This indicates a difference in how audience interacts with the various contents.
5. News, Finance, Crypto, Literature and data science has the least number of interactions. The audience might consume the content for information rather than interactions.

Potential Implicationa dn Recommendations:
1. For creators aiming for strtonger communities, content related to high-engagement keywords should be prioritized. 
2. If the goal is discussion and interaction, focusing on videos that start opinions, debates would be beneficial.
3. For categories with low comment counts need to understand is to due to content nature, do the audience prefers passive consumption.

* **Engagament Score and find top 10 videos**

Key Observations and Insights:
1. The video "Education should be a right.." has the highest engagement score of 26.3%. the video has a relatively low views but high likes and comments indicates that the viewers are engaged audience for this topic.
2. There are 3 videos for gaming  which has a high engagement score. This highlights the consistently high engagement within the gaming community, whether it's for music mixes, gameplay commentary, or specific game-related content.
3. Two crypto videos makes to the top 10. Crypto was among the lowest keywords by raw comment fromt the previous analysis.  with the engagement score it shows that viewers who do watch crypto content are highly inclined to engage. This suggests that crypto content, while perhaps niche, cultivates a very active and interactive audience.
4. Chess and History show strong engagement. Viewers of these topics are actively reposnding to the content.
5. The video No More A Family has a high engagemtn score but the Video ID starts with -. This might indicates a missing or uncategorized keyword or perhaps a speific tag. Further analysis of videos with Vieo ID starting with -

Potential Implications and Recommendations:
1. For creators aiming to build an active community, focusing on topics like education, gaming, crypto could yield higher audience interactions.
2. High engagement often correlates with brand loyalty and deeper connection, which can be valuable for sponsorships, merchandise, or community-driven monetization models, even for videos with fewer absolute views.
3. The presence of - in Video ID suggests that there is some analysis required here.

* **Avg Sentiment Scores for comments on videos published in 2022-08**

This table presents the average sentiment scores for the top 10 comments on a selection of videos published in August 2022. The sentiment score, ranging from -1 (most negative) to 1 (most positive), indicates the overall emotional tone of the comments. 
Sentiment Analysis adds a qualitative layer to engagement metrics. Avideo might have high views and comments but if those comments are negative then it a different story than highly positive engagement.

Key Observations and Insights:
1. The top 5 videos in the list all exhibits high positive avg sentiment scores. this suggests that these videos resonated well with the audiences, leading to positive feedback.
2. Interview and crypto stands out. They have the highest sentiment score, indicating positive reception. 
3. Other positively received videos include "ASMR"  "apple"  and "tutorial". This indicates that a variety of content types, from personal development to product announcements and educational content, can elicit strong positive sentiment.
4. The bottom 5 videos show significantly negative average sentiment scores, ranging from -0.537150 to -0.912200. This is a strong indicator of audience dissatisfaction, controversy, or negative reactions to the content.
5. News keyword generating negative sentiment is understanbole given the nature of new event about bombing.

Potential Implications:
1. For the reputation of brand negative sentiment can take away trust and viewership over time.
2. A video with fewer positive comments is more valuable than a video with many negative comments.

* **Monthly Engagement Score for the year 2022**

The heatmap visualizes the average Engagement Scorefor the various keywords across different months from Jan 20222 to Aug 2022. The color intensity (from light yellow for low engagement to blue for high engagement) allows for quick identification of trends and peaks in audience interaction.

Key Observations and Insights:
1. Crypto shows the strongest peak in Aug 2022, indicating exceptional audience interest.
2. Computer Science demonstrates consistently high engagement throughout the observation period.
3. Education exhibits spikes in specific months, suggesting seasonal or event driven engagement pattern.
4. Aug has a highest engagement for several keywords.
5. Topics likes tutorial, trolling, data science and tutorial demonstrate consistent moderate to high engagement throughout the time period.
6. Certain topics computer science, tech and business show sustained enagagment indicating a dedicATED AUDIENCE BASE.
7. Crypto's peak demonstrates audience responsiveness to external events.
8. Lower enagagement topics like literature and physics may represnt underserved area with some growth potential.
9. Some topics show steady performance while others exhibit viral-like spikes, suggesting different content strategies

Potential Implications and Recommendations:
1. Higher engagement periods correlate with increased monetization opportunities.
2. Consistent performance in tech-related topics suggests strong brand association with technology conten
3. Data-driven content planning can improve ROI on content creation efforts
4. Engagement patterns may indicate shifting audience preferences and interests
5. Underperforming topics with growth potential represent future expansion opportunities
6. Establishes baseline metrics for measuring future content performance
7. Increase content production for consistently high-performing topics (computer science, tech, gaming)
8. Align content calendar with identified seasonal patterns, particularly preparing for summer engagement peak
9. Focus on building dedicated communities around consistently engaging topics
10. Develop content formats that can span multiple topic categories
11. Gradually expand into underperforming topics that align with audience interests

* **How Views, Likes and Comments metrics interact with each other and can they predict engagement or content success**

Key Observations:
1. Views and Likes have a Correlation of 0.76.
This indicates there is a strong positive correlation between the number of views a content recives and the number of likes it gets.
This is an expected and logical relationship. As more people view content, there is a high probability that a larger number of them will engage by liking it. This suggests that increasing the content visibility (views) is a crucial prerequisite for generating likes.

2. Views and Comments have a Correlation of 0.66
This indicates there is moderately strong positive correlation between views and Comments.
Similar to likes, m,ore views generally lead to more conmments. However, the correlation is slightly weaker than views and likes. This could imply that while views are important for commnets, other factor such as content type i.e. keyword over here might play a relatively larger role in prompting users to leave a comment compared to simple like.

3. Likes and Commentshave a correlation of 0.89
there is a very strong positive correlation between the likes and comments.
This is the strongest relationship observed in the matrix. It suggests that content that resonates strongly enough recive likes is also highly likely to generate more discussions and comments.This could indicate: Content that recives many likes is generally seen as valuable, which encourages users to express their thoughts in comments. 

All the three engagement metrics are postitively correlated, indicating that they tend to move together. Content capable of generating likes is particularly effective at stimulating converstation.

Stategic Implications:
1. focus on Views
2. Optimize for Likes

# Future Project Ideas

* Trend Analysis: To see the keywords are consistently popular or their performance varies over time.
* Audience Demographics: Understand which keywords are popular for the demographics and tailor the content for the audience.
* Enagagement Metrics: Understand audience interaction beyond just views, like the video view time, shares  
* To see if high like to view ratios correlate with the longer watch times.
* Do the highly engaged videos converts viewers to subscribers
* Analyze the all the comment of these videos and understand why the people like these videos.
* Bring video count for each keywords to see if there are very few number of the video in the bottom keywords.
* Performance the time series analysis for comment counts for these keywords over time.  
* A more robust analysis can be performed if all the comments are available for a video.
