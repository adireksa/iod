README\
Inspired by :https://algotrading101.com/learn/reddit-wallstreetbets-web-scraping/\
\
Steps:\
1) Generate Stock List of Ticker / COMPLETED, IN DATA FOLDER ALREADY
2) Grab previous days 'daily discussion thread' link
3) Interact with reddit API to generate all comment links
4) Grab the text of each comment
5) Compare the stock ticker list with the comments text
6) output information to CSV file
&) Output information to googlesheets