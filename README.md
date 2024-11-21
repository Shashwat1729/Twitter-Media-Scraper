# Twitter-Media-Scraper
This script automates the process of scraping tweets and associated media (images) from Twitter using Selenium. It logs into multiple Twitter accounts, collects tweet data from specified months, and stores the results in an Excel file.

## Features

- Logs into multiple Twitter accounts automatically.
- Searches for tweets from a specific date range.
- Extracts tweet content (text), media URLs (images), and timestamps.
- Saves the data in an organized Excel file.

## How It Works

1. **Login**: The script logs into each provided Twitter account.
2. **Scrape Tweets**: It searches for tweets within the given date range, extracts:
   - **Tweet Content**: The tweet's text.
   - **Media URL**: The URL of the image/media associated with the tweet.
   - **Timestamp**: The time and date the tweet was posted, crucial for organizing data over several years.
3. **Save Data**: The script removes duplicates, resets the index, and saves the data in an Excel file.

## Output

The Excel file will have the following columns:
- **tweetContent**: The text of the tweet.
- **mediaUrl**: The URL of the image or media linked to the tweet.
- **timeStamp**: The timestamp when the tweet was posted, which is necessary to identify tweets from different years.
