# Youtube API
This project analyzes YouTube video data to predict views, classify popularity, and uncover content themes. It features API-driven data collection, rich EDA with visualizations, Random Forest regression, multiple classifiers, and KMeans clustering of video titles based on keyword patterns.
Developed a comprehensive machine learning pipeline to analyze and predict YouTube video performance using data collected via the YouTube Data API. Processed JSON API responses to extract relevant metadata, followed by extensive exploratory data analysis (EDA) using Matplotlib and Seaborn, including distribution plots, correlation heatmaps, and a word cloud of video titles. Built a Random Forest Regressor to predict video view counts and evaluated multiple classification models (Logistic Regression, Naive Bayes, SVM, KNN) to predict video popularity based on engagement metrics. Applied KMeans clustering on TF-IDF-transformed video titles to group content into thematic clusters, labeling them with top keywords for interpretability.

🔍 Key Highlights:
    * Exploratory Analysis: 
         car attributes.
    * Data Preprocessing:
        -- Converted categorical values to numerical format for compatibility with ML models.
        -- Standardized data for better model performance.
        -- Split the dataset into training and testing sets.
    * Modeling & Evaluation:
        -- Trained a KNN classifier and assessed its performance using confusion matrices, accuracy scores, mean squared error, and R² score.
        -- Used cross-validation to evaluate model robustness across multiple splits.
        -- Created a custom function to predict the class of a car based on user-inputted attributes.
