# Book Price Web Scraping and Exploratory Analysis

This project uses Python to collect book listings from [Books to Scrape](https://books.toscrape.com/), prepare the extracted information, and explore pricing and rating patterns.

## Project Overview

Web pages are designed for readers, not for analysis. This notebook demonstrates how to turn HTML content into structured data that can be inspected, cleaned, visualised, and exported.

## Workflow

1. Retrieve HTML pages using Requests.
2. Parse book listings with BeautifulSoup.
3. Extract available book attributes.
4. Clean text and convert values into analysable formats.
5. Explore price and rating distributions.
6. Visualise the results and save a CSV dataset.

## Tools

- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Contents

```text
.
├── main.ipynb
├── books_data.csv
├── requirements.txt
└── README.md
```

## Run the Analysis

Install the listed dependencies and open the notebook:

```bash
pip install -r requirements.txt
jupyter notebook
```

Execute `main.ipynb` from top to bottom. The website's HTML may change over time, so extraction logic may require maintenance.

## Interpretation

The notebook explores differences in listed book prices and ratings. Any observed relationship is descriptive and should not be interpreted as evidence that ratings cause higher prices.

## Data Source

[Books to Scrape](https://books.toscrape.com/) is an educational website designed for scraping practice.

## Author

Jehosaphat Brobbey Impiani  
[GitHub](https://github.com/Slimjoey56)