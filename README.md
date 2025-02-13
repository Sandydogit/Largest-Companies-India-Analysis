# Largest-Companies-India-Analysis
# List of Largest Companies in India - Data Analysis & Visualization

## Overview
This project analyzes and visualizes data on the largest companies in India. The dataset is scraped from Wikipedia and processed using Python. The analysis explores company revenue, market capitalization, and industry trends.

## Dataset
- **Source:** Wikipedia (List of Largest Companies in India)
- **File:** `data/List of largest companies in India.csv`
- **Preprocessing:** Data cleaning, handling missing values, and converting data types

## Features & Methodology
- **Web Scraping:** Extracted data using `BeautifulSoup` from Wikipedia
- **Data Analysis:** Performed exploratory data analysis (EDA) using `pandas`
- **Visualization:** Used `matplotlib` and `seaborn` for bar charts, histograms, and scatter plots
- **Insights:** Trends in revenue, market cap, and company distribution by sector

## Project Structure
```
📂 Your-Repository-Name
│-- 📜 README.md
│-- 📂 data
│   │-- List of largest companies in India.csv
│-- 📂 notebooks
│   │-- List of largest companies in India.ipynb
│   │-- List of largest companies in India analysis.ipynb
│-- 📜 requirements.txt
│-- 📜 .gitignore
```

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Run the analysis notebooks inside the `notebooks` folder.

## Requirements
Dependencies are listed in `requirements.txt`:
```
bs4
matplotlib
pandas
requests
seaborn
```
Create `requirements.txt` by adding the dependencies above in the root folder of your repository.

## Example Output
- **Top 10 Companies by Revenue** (Bar Chart)
- **Revenue vs. Market Cap** (Scatter Plot)
- **Industry Distribution of Top Companies** (Pie Chart)

## License
This project is for educational purposes only.

---
Feel free to contribute or suggest improvements!
