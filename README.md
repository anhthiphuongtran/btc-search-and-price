# Investigate associated patterns between Bitcoin Search and Price

## About
* Google Trends give us an estimate of search volume. Let's explore if search popularity relates to cryptocurrency prices. For this project, I will investigate whether there are related patterns between Google Search Trend and the price of Bitcoin - the most famous cryptocurrency.

* This project is about data exploration and visualisation using Python. In this project, I use Pandas and Matplotlib library to handle 6-year period data collected from websites:

1. [Google Search Trend](https://trends.google.com/trends/explore)
2. [Yahoo Finance for Bitcoin Price](https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)


* While the website continuously updates the book's price, I will write code to extract the price and automatically send an email to myself (using smtplib) notifying when the price is below my cut-off price, or in other words, the price I am willing to pay.

![image](https://github.com/anhthiphuongtran/web-scraping/assets/105230494/b277a047-9046-44b1-b180-00b334359450)

## Dependencies:

1. Python v3.x is required.
2. Beautiful Soup library is required to scrape web data.
3. Smtp module is required to send email automatically within the program.

## Additional information
The code can be uploaded on [Python Anywhere](https://www.pythonanywhere.com/) so that the program can be run in the cloud to continuously check the price and send email automatically even if I do not turn on my computer.
