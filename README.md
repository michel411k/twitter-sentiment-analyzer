# Twitter Sentiment Analysis

This project analyzes the sentiment of tweets to classify them as positive or negative.  
Using Natural Language Processing techniques and machine learning, the project explores tweet data, cleans and visualizes it, and builds a model to predict sentiment with about 75% accuracy.  
The results can be used to better understand public opinion on social media and provide a foundation for further NLP applications.




[Sentiment Distribution](sentiment_plot.png)





# Twitter Sentiment Analysis Project

## Project Summary
This project analyzes tweets to determine whether they express positive or negative sentiment. By applying data cleaning, exploratory data analysis (EDA), visualization, and machine learning, the project extracts insights from Twitter data and builds a simple yet effective sentiment classifier. Such analysis is valuable for understanding public opinion, brand monitoring, and social media research.

---

## Step-by-Step Explanation

### 1. Exploratory Data Analysis (EDA)
- Loaded a dataset of tweets labeled as positive or negative.
- Visualized the distribution of sentiments using bar charts.
- Used TextBlob to calculate a polarity score (-1 to 1) for a more nuanced sentiment analysis.
- Analyzed tweet activity by year, hour of day, and day of week to reveal usage patterns.

### 2. Text Cleaning
- Cleaned the tweet texts by:
  - Converting text to lowercase.
  - Removing URLs, mentions (@users), and special characters.
  - Removing English stopwords using spaCy for better text quality.
- These steps help improve the model’s understanding of the data.

### 3. Advanced Visualizations
- Created word clouds showing the most common words and hashtags.
- Generated a Twitter-logo-shaped word cloud for thematic presentation.
- Compared word clouds of positive vs. negative tweets to highlight sentiment-related vocabulary.

### 4. Machine Learning Model
- Used `TfidfVectorizer` to transform cleaned tweets into numeric feature vectors.
- Trained a Multinomial Naive Bayes classifier to predict sentiment.
- Achieved approximately 75% accuracy, demonstrating good baseline performance.
- Evaluated the model with precision, recall, and F1-score to assess classification quality.

### 5. Interactive Demo with Gradio
- Built a web interface using Gradio where users can input tweets and receive instant sentiment predictions.
- Makes the project interactive and user-friendly for real-time analysis.

---

## Presentation Tips for GitHub

- Include **screenshots** of your charts and word clouds to make the README visually engaging.
- Start with a **clear project description** that summarizes what the project does and its value.
- Highlight that this is a **personal NLP project** showcasing skills in data processing, visualization, modeling, and deployment.
- Use **organized sections and headings** for clarity.
- Add a **requirements.txt** file for easy environment setup.
- Optionally, include a **short demo video or GIF** of the Gradio app to show it in action.

---

Thank you for checking out this project!  
Feel free to reach out if you have any questions or feedback.

