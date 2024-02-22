# Twitter-Sentiment-Analysis

## Project Overview:
In this project, I employed Natural Language Processing (NLP) techniques to analyze sentiments expressed on Twitter. 
The primary objective was to discern people's sentiments as they tweeted about various topics. The dataset used for the analysis was sourced from Kaggle, accessible [here](https://www.kaggle.com/datasets/bhavikjikadara/tweets-dataset/data) .

In the [Jupyter Notebook](https://github.com/Mayreeobi/Twitter-Sentiment-Analysis/blob/main/Twitter%20Sentiment%20Analysis%20using%20NLP.ipynb), you will learn how I carried out the following steps for the project:

## Tools and Libraries:
To accomplish the project goals, a combination of Python libraries was utilized:
- Pandas: Employed for effective data cleaning and manipulation.
- NLTK (Natural Language Toolkit): Utilized for advanced natural language processing tasks.
- TextBlob: Chosen for sentiment analysis, assigning Subjectivity and Polarity scores to each tweet.
- Matplotlib, Seaborn & WordCloud: These libraries played a crucial role in exploring and visualizing the dataset.

## Sentiment Analysis:
The sentiment analysis aspect relied on TextBlob, which evaluates text by providing Polarity scores. The Polarity score became the basis for categorizing tweets into Positive, Negative, or Neutral sentiments. Specifically, a Polarity score below 0 indicated negativity, a score of 0 denoted neutrality, and a score above 0 signified positivity.

## Remark: 
The sentiment analysis revealed intriguing findings within the dataset. A notable portion, accounting for 37.1% of the tweets, exhibited a dual nature, being classified as both positive and neutral. This suggests a nuanced sentiment among Twitter users, where expressions may carry elements of positivity while maintaining an overall neutral tone. In contrast, approximately 25.74% of the tweets were categorized as negative, indicating a substantial presence of unfavorable sentiments within the dataset.
It's worth noting that the dataset was obtained this month, coinciding with Valentine's Day. This temporal alignment may have influenced the sentiment distribution, as events and holidays often play a significant role in shaping the emotional tone of social media discourse.

## Limitations:
While the sentiment analysis provided valuable insights, there are certain limitations to consider:
* Limited Dataset Columns: The dataset was constrained by the inclusion of only a few columns, and some of these columns might have been insignificant for the sentiment analysis. Expanding the dataset to include more relevant features, user demographics, or tweet engagement metrics, could enhance the depth of analysis.
* Scope of Analysis: The analysis primarily focused on sentiment categorization (positive, negative, neutral) without delving into specific topics, hashtags, or keywords associated with these sentiments. A more granular exploration of these aspects could unveil nuanced patterns and provide a deeper understanding of the factors influencing sentiment distribution.
* Geographical Context: The dataset did not include information about the geographical locations of tweets. Incorporating location data could offer insights into regional variations in sentiment, allowing for a more comprehensive understanding of sentiment dynamics.



## Relevant Links
* [Jupyter Notebook]( https://github.com/Mayreeobi/Twitter-Sentiment-Analysis/blob/main/Twitter%20Sentiment%20Analysis%20using%20NLP.ipynb)
* [Portfolio Website](https://mayreeobi.github.io)
* [LinkedIn](https://www.linkedin.com/in/chinyere-obi/)




