# Analyzing Amazon reviews on Glassdoor
Analysis of Glassdoor Reviews

Prediction of Glassdoor Rating & Sentiment Based on Review Text

OBJECTIVE 
The project was designed to scrape employee reviews from Glassdoor and predict rating of reviews using Machine learning and NLP techniques. The goal was to predict star rating and sentiment rating and compare the performance of the models.

INTRODUCTION:
Glassdoor reviews are quite important for a potential candidate to decide their fit towards a company's values and work culture. It's important to analyze the free-text and measure the importance of a review. This project involves a combination of topic modeling and sentiment analysis to summarize the content and thereby help predict the review stars.

Data Sources:
Glassdoor website was scraped to obtain employee reviews for a company.
The technique was provided the initial URL for the company employee review page to the program which scraped the page, extracted the tags, retrieved the elements from the page that were intended and then formed the URL for the next page. All the review data is then gathered in a dataframe and saved off to a csv file.BeautifulSoup & urllib packages were primarily used for scraping and parsing the reviews.

Conclusion
The task of mining opinion from a review was successful. The model to predict whether the sentiment is positive or negative is 72% accurate. But, when we try to predict the sentiment stars it's not very effective. It's probably because the structure of the reviews and choice of words is quite different. The project would atleast help the potential candidates to understand the overall employee engagement policies of a company
