# Crypto-Sentiment-Analysis

This project pulls crypto related tweets using Twint and then calculates sentiment scores using Vader and TextBlob

The scores are visualized on a Flask App using plotly and Dash
The following plots are available:
1. The percentage of people with a positive sentiment on crypto at a given time 
2. Average cumulative crypto score: The average sentiment score for every data pull will be visualized on a line graph. A user can see changing trends in the average sentiment over time. 
A user will be able to select which sentiment analysis score they wish to view using a dropdown- they can select from Vader and TextBlob
