# Cristiano Ronaldo YouTube Channel Analysis
![](https://github.com/shanthan98/Ronaldo_YT_Analysis/blob/main/Assets/Images/ronaldo.png)

## Project Overview
Although I’m not a football fan, I admire Cristiano Ronaldo for his discipline, commitment, and dedication to his sport. Recently, Ronaldo entered the world of YouTube, breaking records in an incredibly short span of time. As a **data analyst**, I decided to dig deep and gain insights into his YouTube channel using the **YouTube API**.

## Table of Contents

- [Dataset](#Dataset)
- [Concepts Used](#Concepts-used)
- [Data Preparation](#Libraries-Used)
- [Project Insights](#Project-Insights)

This project analyzes various metrics from Ronaldo's YouTube channel and provides insights into video performance, audience interaction, and content trends. From video length analysis to upload patterns, this repository covers a wide range of statistical insights.

## Dataset
The data was collected using the **YouTube API**. The data includes information such as:
- Video IDs
- Titles
- Views, likes, and comments
- Video upload date and time
- Tags
- Video duration
- Audience interaction
- comments

However, there is a limitation imposed by the YouTube API:
- **YouTube API Limitation**: The API only allows fetching **10,000 units per request**, which affected the ability to gather all possible insights, but I managed to work within these constraints and provide valuable insights.

## Concepts Used
In this project, the following data analysis and visualization concepts were used:
- **Exploratory Data Analysis (EDA)**: Understanding the data distribution, cleaning the data, and visualizing basic patterns.
- **Sentiment Analysis**: Extracting sentiment from the comments left on the videos.
- **Text Mining**: Creating a word cloud to identify trending topics and keywords.
- **Correlation Analysis**: Understanding relationships between views, likes, and comments.
- **Data Visualization**: Using various plots (bar plots, scatter plots, histograms) to represent insights visually.

## Libraries Used
The following Python libraries were used to perform the analysis:
- `Pandas`: For data manipulation and handling the dataset.
- `Matplotlib`: For creating various visualizations (bar charts, scatter plots).
- `Seaborn`: For enhanced data visualization.
- `TextBlob`: For performing sentiment analysis on YouTube comments.
- `WordCloud`: For generating the word cloud of video titles and comments.
- `YouTube API`: To retrieve data directly from Cristiano Ronaldo's YouTube channel.

## Project Insights
### 1. **Performance by Day of the Week**
   - **Insight**: Wednesday sees the highest average number of views, making it the best day for uploads. Likes and comments remain fairly steady throughout the week.
   - **Action**: Uploading videos on Wednesdays can help maximize views and overall engagement.

### 2. **Video Length vs. Engagement**
   - **Insight**: Shorter videos (under 3-4 minutes) tend to get more views and likes. This shows that the audience prefers quick, bite-sized content.
   - **Action**: Focus on creating shorter, engaging videos to optimize for maximum reach.

### 3. **Best Performing Videos**
   - **Insight**: Videos related to personal stories and behind-the-scenes moments with Ronaldo tend to perform exceptionally well, with the top video gaining over 50 million views.
   - **Action**: Repeating content themes related to personal insights and major career events might help capture similar interest.

### 4. **Trending Keywords**
   - **Insight**: Keywords like “Cristiano,” “Ronaldo,” “Goat,” and “Fan” dominate, indicating the importance of his personal brand and fan engagement.
   - **Action**: Leverage these keywords in future content to maintain engagement and relevance with the audience.

### 5. **Upload Schedule**
   - **Insight**: Most videos are uploaded on Wednesdays, which coincides with the highest viewership.
   - **Action**: Focus on uploading content mid-week to target peak audience activity.

### 6. **View Distribution**
   - **Insight**: There is a disparity in video performance. While some videos perform exceptionally well, many others attract fewer views, indicating a skewed distribution of viewership.
   - **Action**: Identify successful video themes and apply these lessons to future content to level out performance.

### 7. **Views vs. Likes & Comments**
   - **Insight**: As views increase, so do likes and comments, showing a strong correlation between these metrics.
   - **Action**: Encourage more audience interaction on high-view videos with calls-to-action for likes and comments.

### 8. **Word Cloud for Video Titles**
   - **Insight**: The most common keywords found in titles include "Cristiano," "Georgina," and "Goal." Videos related to his family and professional achievements receive significant attention.
   - **Action**: Continue producing content that resonates with these themes.

### 9. **Sentiment Analysis on Comments**
   - **Insight**: Viewer sentiment is overwhelmingly positive, with comments showing admiration and excitement for Ronaldo.
   - **Action**: Continue fostering a positive community with engaging content and responding to fan interaction.

