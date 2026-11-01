### Social Media Engagement Analytics

Python data analytics project analyzing user engagement, content performance, behavioral patterns, and sentiment dynamics across a dataset of 5,000 social media posts.

### 📌 Project Overview

This project delivers a complete data science workflow executed in Jupyter Notebooks. The primary objective is to transform raw social media interaction data into actionable marketing insights by performing data cleaning, statistical modeling, feature engineering, and exploratory data visualization.

### 📊 Dataset Highlights

Dataset File: social_media_engagement_5000.xlsx

Total Records: 5,000 post entries

Primary Metrics: Likes, Comments, Shares, Watch Time (sec), Impressions, Engagement Rate, Follower Count, Post Type, Sentiment, Age, Country, Timestamp (posted_at).

Engineered Features:

hashtag_count: Extracted count of post hashtags.

engagement_score: Composite calculated score weighting user interactions.

log_likes & log_impressions: Log-transformed continuous metrics to handle skewed distributions.

### 🛠️ Key Tasks & Workflow

Data Import & Setup: Imported raw dataset, validated non-null schema integrity, parsed datetime fields, and computed initial vector metrics using NumPy.

Data Cleaning: Handled missing values (median imputation for numerical features, mode for categorical features), verified zero duplicate records, and validated value ranges.

Data Exploration & Statistical Profiling: Computed comprehensive descriptive statistics including mean, median, mode, standard deviation, variance, percentiles (25th, 50th, 75th), skewness, and kurtosis.

Data Wrangling & Feature Engineering: Created multi-variable groupby() aggregations and applied mathematical log transformations to reduce distribution skew.

Data Visualization: Built multi-chart analytical panels using Matplotlib and Seaborn (Scatter plots, line trends, bar charts, pie charts, distribution histograms, boxplots, and correlation heatmaps).

Data Export: Exported final feature-engineered dataset as social_media_engagement_cleaned.csv.

### 💡 Key Insights Summary

Content Performance: Video and carousel post formats generate the highest cumulative engagement score by driving greater watch time and share volume.

User Trends: Younger age demographics demonstrate higher responsiveness in likes and comments, while older cohorts exhibit longer session watch durations. Verified accounts lead total reach.

Behavioral Patterns: Impression volumes peak during evening hours (6:00 PM – 9:00 PM local time). Mobile devices account for over 80% of video watch time.

Sentiment Dynamics: Positive sentiment posts achieve the highest average engagement scores and virality. Neutral posts maintain consistent discussion volumes through informational inquiries.

### 💻 Tech Stack & Tools

Language: Python 3.x

Environment: Jupyter Notebook / JupyterLab

Data Manipulation: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

File Outputs: CSV, DOCX


### 📄 Output Deliverables

social_media_engagement_cleaned.csv — Final cleaned dataset with calculated metrics.

social_media_engagement_summary.docx — Executive project summary report.
