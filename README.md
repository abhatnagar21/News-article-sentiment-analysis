# News-article-sentiment-analysis
Project Overview
This project involves scraping news articles from a specified website (NDTV in this case), performing sentiment analysis on the content of those articles using the VADER sentiment analysis tool, and then calculating and visualizing the accuracy of the sentiment predictions.

Data Collection
The project scrapes articles from the NDTV website. The scraping function targets URLs containing the /news/ path, extracts the title and content, and stores them in a list of dictionaries.

Sentiment Analysis
Sentiment analysis is performed using the VADER sentiment analysis tool from the NLTK library. The tool provides a compound sentiment score for each article, which is used to classify the article as positive or negative.

Model Evaluation
The model's accuracy is calculated by comparing the predicted sentiment labels with randomly generated true labels (for demonstration purposes). The accuracy score is then printed.

Visualization
A histogram is plotted to visualize the distribution of compound sentiment scores. A red line is drawn at the threshold (0.05) used to classify the articles.

Statistics
Articles Scraped: The script scraped a total of X articles from NDTV (replace X with the actual number of articles).
Accuracy: Achieved an accuracy of Y% in sentiment classification using a random set of true labels (replace Y with the actual accuracy percentage).
Sentiment Distribution:
Positive Articles: Z% of articles were classified as positive (compound score > 0.05).
Negative Articles: 100-Z% of articles were classified as negative (compound score ≤ 0.05).
Acknowledgments
NDTV for the content used in this project.
NLTK for the sentiment analysis tools.
Matplotlib for the data visualization capabilities.
