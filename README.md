# FinancialTweets_SentimentalAnalysis
Used the Kaggle dataset "Financial Sentiment Analysis" ( https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis ) to train the model.

The sentiment analysis model focuses on analyzing the input tweets related to finance, providing users with a breakdown of sentiment percentages (positive, neutral, negative). This information is presented through graphs, helping users understand the overall sentiment towards stocks and assisting them in making informed investment decisions. Additionally, users have the option to download a CSV file that includes some of the analyzed tweets, along with the model's classifications and confidence levels. This feature aims to provide transparency and insights into the model's decision-making process.

Our model is based on the Roberta-Large architecture from transformers library and has been further trained and fine-tuned using a financial tweets dataset sourced from Kaggle. On average, our model achieves an accuracy of 83% for classifying individual tweets, and its accuracy tends to improve when analyzing larger volumes of tweets on specific topics.
