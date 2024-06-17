# day36_100
I am currently engaged in a 100-day Python Bootcamp, which I am documenting and sharing my progress on GitHub. The boot camp is designed to progressively intensify, allowing me to deepen my understanding and proficiency in Python programming.

Additionally, I have chosen to include the beginner, intermediate and advanced in my documentation to provide a valuable reference for my future growth and development.

---------------------
# Stock and News Alert System
This Python script monitors the stock price of a specified company and sends alerts via WhatsApp using the Twilio API if there are significant changes. Additionally, it fetches relevant news articles about the company to provide context for the stock price changes. It's sort of similar to how a stock trader would use using a Bloomberg Terminal but a small scale.

## Features
- Fetches daily stock prices for a specified company from Alpha Vantage.
- Calculates the percentage change in stock price.
- If the percentage change exceeds a threshold, fetch the latest news articles related to the company from NewsAPI.
- Sends alerts with stock changes and news headlines to a specified WhatsApp number using Twilio.

## Example Output
If the stock price change exceeds the threshold, you will receive WhatsApp messages similar to the following:
```python
TSLA: 🔺2%
Headline: Were Hedge Funds Right About Piling Into Tesla Inc. (TSLA)?
Brief: We at Insider Monkey have gone over 821 13F filings that hedge funds and prominent investors are required to file by the SEC. The 13F filings show the funds' and investors' portfolio positions as of March 31st, near the height of the coronavirus market crash.
```

## .gitignore
Ensure your .env file containing secret keys is not tracked by Git. Add the following lines to your .gitignore file:

```python
.env
```
## Demo 
![](https://github.com/AlvinChin1608/day36_100/blob/main/Finished_Product_Screenshot.PNG)
