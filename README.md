# Narendra Modi News Scraping - The Guardian API

## Overview
This project contains a Python script that scrapes news articles related to *Narendra Modi* from The Guardian's API. The fetched data includes article titles, section names, URLs, and publication dates, which are then converted into a CSV file.

## Features
- Scrapes the latest articles related to *Narendra Modi*.
- Converts the news data into a structured CSV format.
- Uses **pandas** for data manipulation and **requests** for API calls.

## Requirements
- **Python 3.6+**
- Python libraries:
  - `requests`
  - `pandas`

You can install the required libraries by running:
```bash
pip install requests pandas
```

## Setup Instructions
1. **Get The Guardian API Key**:
   - Sign up and get your API key from [The Guardian Open Platform](https://open-platform.theguardian.com/).



## CSV File Output
The `readme.csv` file contains the following columns:
- **Title**: Title of the article.
- **Section**: The section under which the article is published (e.g., Politics, World News).
- **URL**: The URL to the article on The Guardian website.
- **Publication Date**: The date when the article was published.

## Example Output
Here’s an example of what the CSV file looks like:

| Title                     | Section     | URL                               | Publication Date      |
|----------------------------|-------------|-----------------------------------|-----------------------|
| Modi's Speech on Economy    | Politics    | https://www.theguardian.com/xyz   | 2024-10-01T10:15:30Z  |
| India's Growth under Modi   | World News  | https://www.theguardian.com/abc   | 2024-10-02T11:20:45Z  |

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any changes you'd like to suggest.

