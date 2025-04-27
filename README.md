# ML--Anime-Recommendations-with-Simple-Linear-Regression

**Objective:**

    Explore the Anime Recommendations dataset by performing data cleaning, preprocessing, and feature engineering. 
    Then, use Simple Linear Regression to predict an anime’s rating based on the number of users who rated it and other relevant features

**Dataset Exploration:**

Import the Anime dataset and display its first few rows.

Identify key features such as anime_id, name, genre, rating, and members.

Perform initial visualizations to understand the distribution of ratings and the relationship between rating and members.

Identify missing values in the dataset.

Drop or impute missing values in columns like genre and rating.

Ensure categorical variables like genre are correctly encoded for analysis.

Detect outliers in numerical features such as rating and members.

Discuss strategies for handling outliers (e.g., capping, removal).

**Feature Engineering:**

Genre Count: Create a new feature that counts the number of genres associated with each anime.

Log Transformation: Apply a log transformation to the members' column to reduce skewness.

Feature Encoding: Encode the genre feature using methods like One-Hot Encoding or Label Encoding to make it suitable for model input.

**Simple Linear Regression:**

Regression Setup: Use the members feature as the independent variable (X) and rating as the dependent variable (Y) to explore their relationship using Simple Linear Regression.

Train-Test Split: Split the data into training and testing sets for the regression model.

Model Fitting: Fit a Simple Linear Regression model to predict rating based on the log-transformed members.

Plot the regression line on a scatter plot of members vs. rating.

**Insights and Reporting:**

Interpretation of Results: Discuss the impact of feature engineering and the relationship between the number of members and the rating.
Identify which features were most predictive of the anime rating.

**Conclusion:**

Summarize the findings and suggest potential improvements or next steps for the analysis and model building.
