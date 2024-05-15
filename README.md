# Hacker-News
Data scraper in Python to check top posts on Hacker News

Project Overview
This Python script scrapes news stories from the first two pages of Hacker News, a social news website focusing on computer science and entrepreneurship. It filters and sorts the stories by the number of votes, specifically highlighting stories with over 99 votes. This tool is ideal for users interested in quickly identifying the most popular discussions on Hacker News without manually browsing through the site.

Features
Scrapes the top stories from the first two pages of Hacker News.
Filters stories with more than 99 votes.
Sorts stories by the number of votes in descending order.

Requirements
Python 3
Libraries: requests, bs4

Setup and Installation
Ensure Python 3 is installed on your machine.
Install the required Python libraries using pip:
pip install requests beautifulsoup4

Clone this repository or download the script to your local machine.
Run the script using Python:
python scrape.py

How to Use
Once you run the script, it will fetch stories from Hacker News and display them in the terminal. The output will include the title of each story, its URL, and the number of votes it has received, provided the story has more than 99 votes.

Contributing
Contributions to this project are welcome! You can contribute by improving the script, adding features, or reporting bugs. Please feel free to fork the repository and submit a pull request.
