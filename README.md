# Twitter_Sentiment_Analysis

Project Overview
This project performs sentiment analysis on a dataset of tweets to classify them into different sentiment categories (Positive, Negative, Neutral, Irrelevant).
Dataset
The dataset used for this analysis is sourced from Kaggle: Twitter Entity Sentiment Analysis. Specifically, the twitter_training.csv file was used.
Methodology
1. Data Loading: The twitter_training.csv dataset was loaded into a pandas DataFrame.
2. Data Preprocessing: The tweet text data was preprocessed to remove URLs, special characters, and numbers. The text was then lowercased, tokenized, and lemmatized, with stop words removed.
3. Model Training: A Logistic Regression model was trained on the preprocessed text data using TF-IDF vectorization. The data was split into training and testing sets to evaluate the model's performance.
4. Model Evaluation: The trained model was evaluated using accuracy and a classification report to assess its performance across different sentiment categories.
5. Sentiment Prediction: The trained model was used to predict sentiment on sample text data.
6. Data Visualization: Visualizations were created to understand the distribution of sentiment categories and the most frequent words associated with each sentiment.
Results
The Logistic Regression model achieved an accuracy of approximately [Insert Accuracy Score from Model Evaluation Output] on the test set.

The classification report provides detailed precision, recall, and f1-score for each sentiment class.

Visualizations show the overall distribution of sentiments and the prominent words in each category, offering insights into the language used in tweets with different sentiments.
![distribution_sales](https://github.com/user-attachments/assets/cf7860d8-42a3-4274-bbd9-53ad30599202)

![Top10](https://github.com/user-attachments/assets/f6e05a4e-fed1-4471-b110-29c3903632c7)

![Top10_Neutral](https://github.com/user-attachments/assets/5c4f8c2f-9036-4c8d-b622-cc3fb6b962de)

![Top10_Negative](https://github.com/user-attachments/assets/dbfd725f-1c81-4042-8fbd-75590841e5d7)

![Top10_Irrelevant](https://github.com/user-attachments/assets/bc1f15a3-5b51-43e2-9129-8a6446f50a39)




Files
• twitter_training.csv: The dataset used for training and analysis.
• This notebook: Contains the code for data loading, preprocessing, model training, evaluation, prediction, and visualization.
How to Run
1. Open the notebook in Google Colab.
2. Ensure the dataset is accessible in the Colab environment (e.g., mounted from Google Drive or through Kaggle integration).
3. Run the cells sequentially to execute the sentiment analysis pipeline.
