# DSA Search Engine

A search engine designed to retrieve relevant LeetCode coding questions based on user-entered keywords. This project involves web scraping, text relevance calculation, and a dynamic web interface.

## Project Overview

The DSA Search Engine allows users to search for LeetCode coding questions by entering relevant keywords. The project utilizes web scraping techniques to gather questions and employs the TF-IDF algorithm to determine the relevance of user queries to the scraped data.

## Features

- **Web Scraping:** Extracted around 1900 LeetCode questions from the website using Selenium and BeautifulSoup (bs4).
- **Relevance Calculation:** Implemented TF-IDF to calculate and rank the relevance of questions based on user-entered keywords.
- **Dynamic Interface:** Created a user-friendly website using Flask framework for easy interaction with the search engine.

## Technologies Used

- **Python:** Programming language for implementing web scraping and relevance calculation.
- **Selenium:** Used for automated web scraping.
- **BeautifulSoup (bs4):** For parsing HTML and extracting data.
- **TF-IDF Algorithm:** For calculating the relevance of keywords.
- **Flask:** Framework for building the dynamic web interface.

## Project Structure

- `app.py`: Main Flask application file.
- `scraper.py`: Contains the web scraping logic.
- `relevance_calculator.py`: Implements the TF-IDF algorithm.
- `templates/`: Directory containing HTML templates for the web interface.
- `static/`: Directory containing static files (CSS, JS).