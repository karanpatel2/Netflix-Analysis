**Netflix Dataset Analysis and Content Strategy Optimization**

**Project Type**
Exploratory Data Analysis (EDA)

**Contribution**
Individual

**Team Member**
Karan Patel

**Project Summary**

This project aims to analyze the Netflix dataset to uncover valuable insights that can help improve content strategy and user engagement. Using Exploratory Data Analysis (EDA) techniques, this project dives deep into the data to explore trends, content categories, popular genres, and more. With a strong focus on visualization, various types of charts (bar charts, pie charts, histograms, heatmaps, etc.) are used to communicate key findings.

Netflix, being one of the leading OTT platforms, produces and hosts thousands of movies and TV shows. Understanding user preferences and the composition of content is crucial to staying competitive. Through this project, insights such as the most popular release years, country-wise content distribution, trends in content duration, and actor/director contributions have been visualized and interpreted. This not only helps in identifying content gaps but also aids in forming a data-driven content acquisition or production strategy.

The dataset used is preprocessed for missing values, data type corrections, and feature extraction. Key columns like release year, cast, genre, duration, and country were cleaned and analyzed. Both univariate and bivariate analyses were performed, followed by multivariate visualizations.

This project delivers 20 meaningful and logical charts that align with the UBM approach (Univariate, Bivariate, Multivariate), each followed by insights and their potential business implications.

**Problem Statement**

Netflix wants to better understand the type of content that is successful on its platform. This includes identifying trends in content release, geographic distribution, genre popularity, and contributor involvement (like actors and directors).

**Define Your Business Objective**

To extract meaningful insights from Netflix’s content dataset that can:
Help in identifying popular genres and trends over time.
Optimize content strategy for different regions.
Improve recommendations based on user-viewing habits and available content.
Assist in acquiring or producing content based on data-driven decisions.

**Dataset Information**

Source: Netflix dataset
Features include: title, director, cast, country, release_year, date_added, duration, rating, listed_in, type, etc.

**Variables Description**

title: Title of the show/movie
director: Director's name
cast: List of cast members
country: Country of origin
release_year: Year the content was released
date_added: Date the content was added to Netflix
rating: Content rating (TV-MA, PG, etc.)
duration: Duration in minutes or seasons
listed_in: Genre(s) of the content
type: Whether it's a Movie or TV Show

**What All Manipulations Have Been Done?**

*-Fill the  missing/null values in crucial columns like title, cast, director, country*
-Converted release_year from float to integer
-Extracted year, month, and day from date_added
-Created visualizations using seaborn, matplotlib

**Insights Found**

Majority of content added in recent years (2018–2020)
US is the highest content contributor
Dramas and Comedies are the most popular genres
TV Shows are shorter in duration but more frequent in releases

**Challenges Faced**

Handling mixed formats in the duration column (Minutes vs Seasons)
Extracting meaningful insights from multi-value columns like cast and listed_in
Null values in crucial categorical fields like director, cast
Plotting content distribution by multiple attributes in a clean, interpretable manner

**Solution to Business Objective**

By applying structured data wrangling and exploratory data analysis, Netflix can:
Strategize content acquisition by genre, country, and release trends
Focus on increasing content in high-demand categories (e.g., TV dramas from the US)
Use insights to improve the recommendation system and viewer retention
Identify underrepresented countries or genres to diversify the portfolio

**Conclusion**

The Netflix EDA project successfully delivers detailed insights using 15 diverse visualizations. The analysis provides actionable insights that can guide Netflix's business and content strategy. From understanding dominant genres and active content-adding years to exploring global content contributions, this project reveals the hidden story behind Netflix's content lineup.
