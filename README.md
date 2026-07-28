# Google-Play-Store-App-Review-Analysis
This project performs Exploratory Data Analysis (EDA) on the Google Play Store Apps and User Reviews datasets to identify patterns in app performance, user engagement, pricing strategies, and customer sentiment.

The objective is to transform raw data into meaningful business insights that can help developers and businesses understand user behavior, improve application quality, and make data-driven decisions.

## Problem Statement

The Google Play Store hosts millions of applications across different categories, making it challenging for developers and businesses to understand what drives an app's success. Factors such as ratings, reviews, installs, pricing, and user feedback play an important role in user engagement and app performance. Analyzing these factors helps businesses make informed decisions and improve their applications.

## Business Objective

The objective of this project is to analyze Google Play Store app data and user reviews to identify patterns, trends, and relationships that influence app performance. The insights generated can help developers optimize pricing strategies, improve user experience, enhance customer satisfaction, and support data-driven business decisions.

## Datasets Used

This project uses two datasets:

### 1. Google Play Store Apps Dataset
This dataset contains information about applications available on the Google Play Store, including:
- App Name
- Category
- Rating
- Reviews
- Installs
- Price
- Content Rating
- Genres
- Android Version
- App Type (Free/Paid)

### 2. Google Play Store User Reviews Dataset
This dataset contains customer reviews for different applications along with:
- Translated Review
- Sentiment (Positive, Negative, Neutral)
- Sentiment Polarity
- Sentiment Subjectivity

  ## Technologies Used

- **Programming Language:** Python
- **Notebook Environment:** Google Colab
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Version Control:** GitHub

  ## Project Workflow

The project was completed in the following stages:

1. Data Collection
2. Data Loading
3. Data Cleaning
4. Data Preprocessing
5. Exploratory Data Analysis (EDA)
6. Data Visualization
7. Sentiment Analysis
8. Business Insights and Recommendations

   ## Data Cleaning

The datasets were cleaned and prepared before analysis by performing the following steps:

- Removed duplicate records.
- Handled missing values appropriately.
- Converted Reviews, Installs, and Price columns into numeric format.
- Removed special characters from numeric columns.
- Merged the Play Store Apps dataset with the User Reviews dataset using the App column.
- Verified data types and prepared the dataset for analysis.

  ## Exploratory Data Analysis

The analysis was performed to understand the characteristics of Google Play Store applications and user reviews. Various visualizations were created to identify trends, relationships, and business insights.

The analysis includes:

- Category-wise app distribution
- Rating distribution
- Free vs Paid apps comparison
- Content Rating analysis
- Genre analysis
- Category vs Average Rating
- Category vs Total Installs
- Price vs Rating
- Reviews vs Rating
- Free vs Paid Rating comparison
- Category vs Average Reviews
- User Sentiment analysis
- Sentiment Polarity distribution
- Sentiment Subjectivity distribution
- Rating vs Sentiment Polarity
- Average Sentiment by Category
- Correlation Heatmap
- Pair Plot
- Top 10 Categories by Average Price
- Top 10 Categories by Average Reviews

  ## Key Insights

- Most applications on the Google Play Store are free.
- Family, Game, and Tools are among the largest app categories.
- Most apps have ratings between 4.0 and 4.5.
- Reviews and installs show a moderate positive relationship.
- Price has little impact on app ratings.
- Finance apps have the highest average prices among paid applications.
- Social and Communication apps receive the highest average number of reviews.
- User sentiment is predominantly positive, indicating overall customer satisfaction.

  ## Business Recommendations

- Focus on delivering a high-quality user experience to improve ratings and engagement.
- Encourage users to leave reviews through regular feedback prompts.
- Analyze category-specific pricing before launching paid applications.
- Monitor customer sentiment to identify areas for improvement.
- Release regular updates to maintain user satisfaction and retention.
- Use data-driven insights to improve marketing and product strategies.

## Conclusion

This project explored the Google Play Store Apps and User Reviews datasets using Exploratory Data Analysis (EDA). The analysis revealed valuable insights into app categories, ratings, installs, pricing strategies, user engagement, and customer sentiment. These findings can help developers and businesses make informed decisions to improve app performance, enhance user experience, and develop effective growth strategies.

 ## Future Scope

- Build machine learning models to predict app ratings or installs.
- Perform time-series analysis using app update information.
- Develop an interactive dashboard using Power BI or Streamlit.
- Analyze app reviews using advanced Natural Language Processing (NLP) techniques.
- Compare trends across different app categories to support business decision-making.

**Author:** Aparna Galav

If you found this project helpful, feel free to ⭐ this repository.
