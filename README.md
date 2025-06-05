# 🚗 Mudah.my Used Car Listings Scraper & Cleaner

This project is dedicated to extracting, cleaning, and preparing car advertisement data from [Mudah.my](https://www.mudah.my/)—Malaysia’s top online marketplace—for exploratory analysis and machine learning applications. The focus is on automating the retrieval of car listings and transforming the raw data into structured insights for understanding the used car market in Malaysia.

---

## 🎯 Project Goals

- Scrape car listings from multiple pages of Mudah.my using `requests` and `BeautifulSoup`.
- Extract relevant attributes such as:
  - Car model and name
  - Year of manufacture
  - Listing price
  - Vehicle condition
  - Region
  - Mileage
  - Engine capacity
- Clean and standardize the dataset by:
  - Handling missing or inconsistent values
  - Formatting numeric fields (e.g., prices, mileage)
  - Simplifying product names
- Detect and filter outliers using the **Interquartile Range (IQR)** method (for price and engine capacity).
- Export cleaned data to CSV for downstream analysis or modeling tasks.

---

## 🧰 Tools & Libraries

- **Python**: Main scripting language for scraping and data transformation
- **Libraries Used**:
  - `requests` & `BeautifulSoup` – for HTML parsing and scraping
  - `pandas` – for data manipulation and analysis
  - `re` – for regular expressions and text cleaning

---

## 📊 Applications & Use Cases

- **Used Car Market Trends**  
  Analyze pricing trends, regional availability, and condition-based pricing across Malaysia.
  
- **Price Estimation Models**  
  Use the cleaned dataset as a foundation for predictive modeling of used car prices.
  
- **Model Demand Analysis**  
  Identify the most frequently listed makes/models to uncover demand patterns in the used car market.

---

## 🗃 Output Format

The final processed dataset is saved as a `.csv` file and includes structured, cleaned features suitable for analysis or feeding into machine learning pipelines.

---

## ⚠️ Disclaimer

This project is created for **educational and research purposes only**. Please ensure your usage complies with [Mudah.my’s Terms of Use](https://www.mudah.my/info/terms) and avoid aggressive scraping practices.

---

## 👤 Author

Developed by [Luqman](https://github.com/luqyz)  
Feel free to contribute or open an issue for suggestions and improvements!

