# Amazon Web Scraping Project (Guided Learning)

## Overview
This is a **guided learning project** that demonstrates basic web scraping using Python. The script tracks the **title, price, and date** of an Amazon product over time and logs it into a CSV file.  

This project is inspired by Alex The Analyst's tutorials and is meant to showcase **data extraction, automation, and basic analysis skills**.

---

## Skills Demonstrated
- Python (functions, loops, modules)  
- Web scraping with **BeautifulSoup**  
- Data logging into **CSV files**  
- Optional: Sending automated emails with **smtplib**  
- Handling dates with **datetime**  

---

## How It Works
1. The script sends a request to the Amazon product page using `requests`.  
2. Parses HTML content with **BeautifulSoup** to extract:
   - Product title  
   - Product price  
3. Saves the extracted data to `AmazonWebScraperDataset.csv`.  
4. Optionally sends an email alert if the price drops below a set threshold.  
5. Can be scheduled to run automatically at regular intervals using `while True` and `time.sleep()`.

---

## How to Use
1. Clone the repository:  
```bash
git clone <your-repo-link>
