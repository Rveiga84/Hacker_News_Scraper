# Hacker News Scraper

## Project Overview
The Hacker News Scraper is a Python-based tool that fetches and displays top stories from Hacker News, focusing on those with over 99 votes for greater relevance. It leverages the Beautiful Soup and Requests libraries to parse HTML content from the site, providing a streamlined view of the most valued discussions by the Hacker News community.

## Features
- Retrieves stories from the first two pages of Hacker News.
- Filters out stories with fewer than 100 votes.
- Sorts qualified stories by their vote counts in descending order.
- Displays each selected story's title, URL, and vote count.

## Technologies Used
- Python
- Requests
- Beautiful Soup

## Setup & Installation
Ensure you have Python 3.6+ installed on your machine.

1. **Clone the repository:**
git clone https://github.com/Rveiga84/Hacker_News_Scraper/hacker-news-scraper.git

2. **Navigate to the project directory:**
cd hacker-news-scraper

3. **Install the required dependencies:**
pip install -r requirements.txt

## Usage
Execute the script from the command line to fetch and display the top stories from Hacker News that have more than 99 votes, sorted by the number of votes:

python scraper.py

This command runs your Python script, scraper.py, which contains the logic for scraping Hacker News stories, filtering, and displaying them based on your criteria.

The script will output the top stories from Hacker News that have more than 99 votes, sorted by the number of votes.

## How It Works
- The script makes HTTP GET requests to Hacker News to retrieve HTML pages.
- Beautiful Soup parses the HTML to extract news story details.
- It filters and sorts these stories based on the number of votes.
- The results are printed to the console in a readable format.

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/[Your GitHub Username]/hacker-news-scraper/issues).

## License
This project is open source and available under the [MIT License](LICENSE).


