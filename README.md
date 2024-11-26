# Stock-Movement-Analysis-Based-on-Social-Media-Sentiment
![image](https://github.com/user-attachments/assets/075205d3-296a-4178-bbed-61f9e3970732)


# Project Overview
Project Description:
This project is about analyzing social media data about Apple Inc. and predicting its future stock trend with sentiment classification. We applied sentiment analysis and machine learning principles to discover the possible effect of "public sentiment" on "market trends".

Prediction of stock price is an extremely complex and very challenging task because there are too many factors involved such as economic circumstances, political events, and other environmental factors which may impact the stock price. Due to these factors, it is difficult to find out the dependence of a single factor on future prices and trends.

The popularity and importance of numerous social media platforms has risen to new levels over the past few years, as more people spend time online. One such social media platform that has seen an explosive rise in popularity is Twitter. Twitter is a rich source of real-time information regarding current societal trends and opinions. The "Twittesphere" is a melting pot driving various opinions, emotions and trends and could be a pivotal factor in influencing and shaping perceptions.

Some statistics regarding Twitter:

Twitter has 145 million monetizable daily active users.

30 million (or 20%) of Twitter’s daily users are American.

92% of the U.S. population is familiar with Twitter (even if they don’t use it).

According to a recent survey by Pew Research Center, around one-in-five U.S. adults (22%) say they use Twitter.

Twitter stands out as one of the social media sites with the most news-focused users.

Behavioural economics tell us that people are not rational consumers and individual behaviours and decisions are greatly affected by emotions and indeed by the opinions of others. Twitter sentiment analysis can be extremely helpful for predicting emotions or opinion on a certain stock. So examining the trending mood on Twitter and observing its relationship to the movement in stock price can help predict the future trend in the market.
# Objective
The objective of this project is to understand the relationship between social media sentiment and stock price movements. By scraping relevant data, performing sentiment analysis, and correlating these insights with stock prices, we aim to uncover actionable insights for traders and investors.
# Setup Instructions

## Prerequisites
Ensure you have Python installed (version 3.6 or higher) and have `pip` available for package management.

## Installation

Clone the repository to your local machine:

```bash
git clone <repository-url>
cd Stock_Sentiment_Analysis
```
Install the required dependencies using `pip`:

```bash
pip install -r requirements.txt
```
 ### Get API Keys

 You will need API keys to access Reddit API:

 ### Reddit API:
- Go to the Reddit App Preferences.
- Click on "Create App" or "Create Another App."
- Fill in the required fields. Select the script option.
- Note the `client_id`, `client_secret`, and `user_agent`.

### Configure API Keys:

REDDIT_CLIENT_ID = `your_reddit_client_id`

REDDIT_CLIENT_SECRET = `your_reddit_client_secret`

REDDIT_USER_AGENT = `your_reddit_user_agent`

Run the data scraping script to collect the required data:
```bash
python scripts/data_scraping.py
```
Open the Jupyter Notebook for analysis:
```bash
jupyter notebook notebooks/Stock_Sentiment_Analysis.ipynb1
```
- Open the notebook and run the cells to perform sentiment analysis and feature extraction.

#### Visualize Results

The notebook contains code for visualizing the results. Run the corresponding cells to generate the visualizations.

### Data Collection
- Input: Raw data from Reddit (e.g., posts from r/wallstreetbets).
- Output: Cleaned dataset containing sentiment scores, post metadata, and stock mentions.

### Analysis and Feature Extraction
- Input: Cleaned data from the scraping step.
- Output:
- Sentiment scores (positive, negative, neutral)
Frequency of mentions
- Additional features for correlation analysis

# Analysis Results

## Visualization
- Input: Results from the analysis step.
- Output: Visualizations (charts, graphs) that show trends in stock sentiment, Frequency of Mentions Over Time and Correlations between sentiment and stock price movements.

Results/ Key findings
## Screenshots

![Screenshot 2024-11-26 073133](https://github.com/user-attachments/assets/c342e7a4-af09-4d1a-b024-e320a0c613d2)

## Sent![Screenshot 2024-11-26 073104](https://github.com/user-attachments/assets/161dfc58-8682-457d-a7d3-d536c91c81a7)![Uploading Screenshot 2024-11-26 073133.png…]()

iment Counts
- Neutral Sentiments: 298 occurrences
- Negative Sentiments: 2 occurrences
This indicates that a vast majority (approximately 99.3%) of the comments are neutral, with only a minimal presence of negative sentiment.

## Stock Mentions
- Total Mentions of AAPL: 0 mentions

This suggests that there were no discussions regarding the stock AAPL in the comments analyzed. This could indicate a lack of interest in AAPL in the context of the discussions on the specific subreddit or threads examined.

## Recommendations Based on Findings
- Broaden Data Collection: To obtain a more comprehensive view, consider scraping additional subreddits or posts related to stocks or more popular stocks to capture relevant discussions and sentiments.

- Analyze Other Stocks: If AAPL is not being mentioned, it may be beneficial to track discussions around other stocks that are currently trending or of interest to the audience, such as those in the news or actively traded.

- Sentiment Analysis Model Evaluation: Given the overwhelming neutrality in sentiment, reviewing the sentiment analysis model's configuration may help enhance its sensitivity and accuracy in capturing a broader range of sentiments, especially positive ones.

- Monitor Changes Over Time: It might be valuable to conduct this analysis over different time periods to observe trends and changes in sentiment and stock mentions. This could help identify any potential correlations with stock price movements.

Python libraries
-Numpy
-Pandas
-Matplotlib
-Mplfinance
-Seaborn
-Plotly
-SciPy
-Statsmodels
-Scikit-learn
-Keras
-TensorFlow
-Yfinance
-Beautiful Soup
-Selenium
-NLTK
-TextBlob
-SpaCy
-Gensim
-BERT
-Hugging Face
-PyTorch


