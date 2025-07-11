#  Naukri Job Listings Scraper & Data Analysis

##  Objective

To build a web scraper that extracts job listings from [Naukri.com](https://www.naukri.com) based on custom keywords and locations, then clean and analyze the data to extract meaningful insights such as top hiring companies, required skills, and job locations.

---

##  Project Structure

- `Web_Scrapping__Naukari_data.ipynb` — Main Jupyter notebook with scraping, cleaning, and EDA steps.
- `README.md` — Project overview and documentation.
- `requirements.txt` — Required Python libraries (optional).
- `scraped_jobs.csv` — (Optional) Saved output of scraped data.

---

##  Challenges

-  Handling dynamic web content loaded by JavaScript.
-  Cleaning and standardizing inconsistent formats across listings.
-  Dealing with missing or incomplete data fields.
-  Preventing IP blocks while scraping multiple pages.

---

##  Outcome

-  Extracted job data for selected roles and locations.
-  Cleaned fields: Job Title, Company, Experience, Location, Skills.
-  Visualized key insights using bar plots and counts.
-  Created a structured dataset that can be reused or extended.

---

##  Sample Insights

-  Most in-demand job locations
-  Top companies hiring for a role
-  Most frequent required skills
-  Experience requirements distribution

---

##  Technologies Used

- `Python`
- `BeautifulSoup` and `requests` for web scraping
- `pandas` for data cleaning
- `matplotlib` and `seaborn` for data visualization
- `Google Colab` for running the notebook

---

##  Colab Link
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/120lcc9ZLTjjKa3pxSd51OJ2XCyiWBIxh)

   
>  Disclaimer: This project is intended for educational purposes only. The data is scraped from publicly available pages on Naukri.com without login or authentication. No personal or copyrighted data is used or redistributed.
