# 🏡 Villa Listings in Hyderabad – Data Extraction & EDA

This project focuses on extracting real estate data of **villa listings in Hyderabad** from the [MagicBricks](https://www.magicbricks.com/) website using web scraping techniques and performing exploratory data analysis (EDA) to uncover insights into pricing trends, location preferences, and property features.

---

## 📌 Project Overview

- **Objective:** Analyze villa property listings in Hyderabad to understand pricing distribution, popular locations, and key features affecting price.
- **Data Source:** [MagicBricks](https://www.magicbricks.com/) – scraped using `BeautifulSoup`.

---

## 🔧 Tools & Technologies

- 🐍 **Python**
- 🌐 **BeautifulSoup** – for scraping HTML content
- 📊 **Pandas, Matplotlib, Seaborn** – for data wrangling and visualization
- 📓 **Jupyter Notebook** – for code development and EDA
- 🔣 **Regular Expressions** – to clean and format text data

---

## 📂 Repository Structure
villa-analysis-hyderabad/
│
├── 📁 data/ # Optional: to store raw/cleaned datasets
│
├── 📓 Data Extraction.ipynb # Web scraping logic using BeautifulSoup
├── 📓 EDA magic brics.ipynb # Exploratory data analysis of the dataset
│
├── 📄 README.md # Project documentation
└── 📄 requirements.txt # Python dependencies


---

## 📈 Key Features of the Analysis

- Extracted villa listings including:
  - Price
  - Area (sq. ft.)
  - Location
  - Number of bedrooms (BHK)
  - Amenities (like parking, furnishing)
- Cleaned and transformed scraped data for analysis
- Visualized trends:
  - Price distribution by area
  - Top localities with most listings
  - BHK vs Price trends
  - Correlation between features and price

---

## 🧠 Insights

- Identified popular villa hotspots in Hyderabad.
- Compared price variation with location and size.
- Derived statistical summaries and outlier detection.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/villa-analysis-hyderabad.git
   cd villa-analysis-hyderabad
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run notebooks in Jupyter or VSCode:

   Data Extraction.ipynb – for scraping data

   EDA magic brics.ipynb – for analysis
