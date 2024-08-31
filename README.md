# News Headline and Article Matcher

## Project Overview
This project is designed to fetch the latest sports news headlines from India using the NewsAPI and match them against keywords extracted from a given input text. The project aims to identify news articles with a high degree of similarity to the input text and fetch full articles for detailed analysis.

## Features
- **Keyword Extraction**: Extracts keywords from the input text using TF-IDF.
- **News Fetching**: Retrieves the latest sports headlines from India using the NewsAPI.
- **Matching Algorithm**: Calculates the matching percentage between the extracted keywords and fetched headlines.
- **Full Article Fetching**: Retrieves the full article content for the top-matching headline using web scraping.

## Installation
### Prerequisites
- Python 3.x
- Libraries: Install the required dependencies using the `requirements.txt` file.

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/news-headline-matcher.git

Navigate to the project directory:
cd news-headline-matcher

Install the required dependencies:
pip install -r requirements.txt

Usage:
Input Text: Define the input text for which you want to find matching news articles.
input_text = "Neeraj Chopra wins silver medal in Olympic Games"

Run the Script: Execute the script to fetch headlines, calculate matching percentages, and retrieve the full article for the top match.
python main.py

Output: The script will display the following:

Extracted Keywords
Total Headlines Fetched
Headlines with at least 70% match
Top Headline with the highest matching percentage, including the article content.

Acknowledgements
NewsAPI: For providing access to the latest news headlines.
BeautifulSoup and Requests: For enabling web scraping to fetch full article content.
NLTK and Scikit-Learn: For text processing and keyword extraction.
