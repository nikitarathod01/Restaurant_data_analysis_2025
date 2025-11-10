# Restaurant_data_analysis_2025
This project performs comprehensive data analysis on restaurant-related data to uncover insights about customer ratings, votes, pricing, and service features such as table booking and online delivery. The analysis leverages Python libraries including pandas, seaborn, matplotlib, and scipy for statistical testing and visualization.

# Key Objectives

Explore relationships between customer review length, ratings, and votes.

Identify common positive and negative keywords in customer reviews using sentiment analysis.

Analyze correlations between numeric metrics such as votes and aggregate ratings.

Investigate associations between categorical features like price range and services provided (online delivery, table booking).

Perform Chi-square tests to statistically assess dependency between categorical variables.

# Data Preparation

The dataset columns were cleaned for consistency (trimming spaces, converting data types).

Missing or invalid data entries were handled by filtering or replacing.

Columns with categorical data (e.g., 'Has Online delivery', 'Has Table booking') were standardized to lowercase for uniformity.

# Customer Review Analysis

Review length was calculated as word count per review.

Sentiment polarity was computed for each review text using TextBlob.

Common positive and negative keywords were extracted by filtering tokenized words from reviews classified by sentiment.

# Statistical Analysis

Correlation coefficients were computed to measure linear relationships between votes and aggregate ratings.

Chi-square contingency tests were applied to assess the relationship between price ranges and availability of online delivery & table booking services:

Example result: Table Booking and Price Range showed a strong dependency with Chi2 ≈ 2823.95 and p-value ≈ 0, indicating the likelihood of having table booking is related to price.

# Visualizations

Bar plots and scatterplots were used to visualize distributions and relationships.

Boxplots illustrated review length variations across different rating values.

Side-by-side bar charts compared service availability percentages across price ranges.

## Libraries Used
pandas: Data manipulation and cleaning.

seaborn & matplotlib: Data visualization.

TextBlob: Sentiment analysis.

scipy.stats: Statistical hypothesis testing (chi-square).

# Conclusion
This project offers insight into customer behavior patterns, highlighting how price ranges impact services offered, how review attributes relate to ratings, and identifying linguistic trends in feedback. These findings can inform restaurant management decisions and marketing strategies.
