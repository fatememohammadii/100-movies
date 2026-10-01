# 100 Must Watch Movies Scraper

A Python web scraping script that retrieves Empire Magazine's list of the top 100 greatest movies of all time from a Web Archive snapshot and saves them in chronological order (1 to 100) into a local text file.

## Features

* Fetches static HTML content using the `requests` library.
* Parses HTML and extracts movie titles using `BeautifulSoup`.
* Reverses the parsed list so movies are numbered from **1 to 100**.
* Automatically exports the ordered titles to a `movie.text` file.

## Prerequisites

Make sure you have Python 3.x installed on your system.

## Installation

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

```


2. **Install required dependencies:**
```bash
pip install requests beautifulsoup4

```



## Usage

Run the Python script directly from your terminal:

```bash
python 100-movies.py

```

After execution, a file named `movie.text` will be created in the same directory containing the top 100 movies list.
