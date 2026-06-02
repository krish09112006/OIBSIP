Project Title

Unveiling the Android App Market: Analyzing Google Play Store Data

Objective

The objective of this project is to analyze Google Play Store data to understand Android app market trends, user behavior, app popularity, pricing patterns, and customer sentiment. The project focuses on data cleaning, exploratory data analysis (EDA), sentiment analysis, and data visualization to generate meaningful business insights.

Dataset

The project uses two datasets:

1. Google Play Store Dataset

Contains information about Android applications, including:

App Name
Category
Rating
Reviews
Size
Installs
Type (Free/Paid)
Price
Content Rating
Genres
Last Updated
2. Google Play Store User Reviews Dataset

Contains user review information, including:

App Name
User Reviews
Sentiment
Sentiment Polarity
Sentiment Subjectivity
Tools and Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Steps Performed
1. Data Loading
Imported Google Play Store dataset.
Imported User Reviews dataset.
Loaded datasets using Pandas.
2. Data Inspection
Viewed sample records using head().
Checked dataset dimensions using shape.
Examined data types using info().
Identified missing values.
3. Data Cleaning and Preparation

Performed the following preprocessing tasks:

Removed duplicate records.
Corrected data types.
Cleaned Rating column.
Converted Reviews column into numeric format.
Cleaned Installs column by removing symbols and commas.
Converted Price column into numeric format.
Cleaned Size column.
Handled missing values using appropriate techniques.
Category Exploration
App Distribution Analysis
Identified the number of apps available in each category.
Analyzed category-wise distribution of applications.
Created visualizations to compare categories.
Visualization
Count Plot of App Categories
Metrics Analysis
Rating Analysis
Calculated statistical measures of ratings.
Examined rating distribution.
Visualization
Histogram of Ratings
App Size Analysis
Analyzed application size distribution.
Investigated common app size ranges.
Visualization
Histogram of App Sizes
Popularity Analysis
Analyzed installs to determine app popularity.
Identified the most downloaded applications.
Visualization
Bar Chart of Top Installed Apps
Pricing Analysis
Compared Free and Paid applications.
Examined pricing trends among paid apps.
Visualizations
Free vs Paid Apps Count Plot
Price Distribution Histogram
Sentiment Analysis
User Review Analysis
Analyzed sentiments from user reviews.
Categorized reviews as Positive, Negative, or Neutral.
Sentiment Distribution
Calculated sentiment counts.
Computed sentiment percentages.
Visualization
Sentiment Count Plot
Category-wise Sentiment Analysis
Merged app dataset with review dataset.
Compared sentiments across app categories.
Visualization
Category-wise Sentiment Distribution Chart
Interactive Visualizations

Created visualizations to understand relationships between variables:

Rating vs Installs
Examined how app ratings affect popularity.
Rating by Category
Compared rating distributions across categories.
Price vs Rating
Investigated the relationship between app pricing and user ratings.
Visualizations
Scatter Plot: Rating vs Installs
Box Plot: Rating by Category
Scatter Plot: Price vs Rating
Key Insights
Certain categories dominate the Google Play Store in terms of app count.
Most applications are free to download.
Highly rated apps generally attract more installations.
User reviews are predominantly positive for popular applications.
Paid apps represent a smaller portion of the market.
App ratings and installs provide valuable indicators of success.
Sentiment analysis helps understand user satisfaction and app performance.
Outcome

This project improved understanding of:

Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Data Visualization Techniques
Sentiment Analysis
Business Insight Generation
Python-based Data Analytics



Conclusion

The project successfully explored the Google Play Store ecosystem through data analysis and visualization. By examining app categories, ratings, installs, pricing strategies, and user sentiments, valuable insights were obtained regarding Android app market dynamics. The findings can help developers, businesses, and analysts better understand factors influencing app success and user engagement.