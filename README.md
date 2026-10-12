# 🚗 Used Car Market Analysis | Python & EDA

An end-to-end data analysis project exploring the used car market to understand pricing patterns, vehicle characteristics, and brand-level trends. The project uses web scraping, data cleaning, and Exploratory Data Analysis (EDA) to transform raw vehicle listings into meaningful business insights.

## 📌 Project Overview

The used car market is influenced by several factors, including brand, fuel type, transmission, ownership history, vehicle age, and kilometers driven. This project analyzes used car listings to identify patterns that can help buyers make informed decisions and understand market pricing trends.

## 🎯 Objectives

- Collect used car listing data through web scraping.
- Clean and preprocess raw data for analysis.
- Analyze vehicle prices across brands and locations.
- Explore relationships between price, kilometers driven, fuel type, and ownership.
- Identify trends and generate actionable insights through visualizations.

## 🛠️ Tech Stack

| Category | Tools & Technologies |
|---|---|
| Programming | Python |
| Web Scraping | Requests, BeautifulSoup |
| Data Manipulation | Pandas, NumPy |
| Data Cleaning | Regular Expressions (Regex), Missing Value Handling |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |

## 📂 Project Workflow

1. **Data Collection:** Extract used car listing information from automotive websites using Python web-scraping techniques.
2. **Data Cleaning:** Handle missing values, remove duplicates where appropriate, standardize text fields, and prepare data for analysis.
3. **Feature Preparation:** Organize relevant attributes such as price, brand, fuel type, transmission, ownership, and kilometers driven.
4. **Exploratory Data Analysis:** Perform univariate, bivariate, and comparative analysis to investigate market patterns.
5. **Visualization:** Create charts to communicate price distributions, brand comparisons, and relationships between vehicle characteristics and price.
6. **Business Insights:** Summarize findings that may support used car buyers and market analysis.

## 📊 Key Insights

- **Location-wise pricing:** Coimbatore showed the highest average listed price, while Surat showed the lowest average listed price in the analyzed dataset.
- **Brand-wise pricing:** Audi had the highest average listed price, while Renault had the lowest among the brands analyzed.
- **Fuel preferences:** Petrol vehicles accounted for the largest share of listings.
- **Transmission trends:** Manual-transmission vehicles represented the majority of listings.
- **Ownership patterns:** First-owner vehicles were the most common ownership category.
- **Brand representation:** Mahindra had the highest number of listings in the analyzed data.
- **Kilometers driven:** Lower kilometers driven generally corresponded with higher listed prices.
- **Vehicle age:** Newer vehicles generally had higher listed prices than older vehicles.

*Note: These observations describe the analyzed dataset and should not be interpreted as universal market trends or proof of causation.*

## 💡 Business Recommendations

- Compare vehicles by brand, age, mileage, and ownership history rather than price alone.
- Use location-specific pricing patterns as a starting point for market comparisons.
- Investigate unusually high or low listed prices before drawing conclusions.
- Consider vehicle condition, service history, and other factors not necessarily captured in the dataset.
- Expand the analysis with additional listings and more complete vehicle attributes to improve the reliability of comparisons.

## 📈 Skills Demonstrated

- Python Programming
- Web Scraping and HTML Parsing
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical and Comparative Analysis
- Data Visualization
- Business Insight Generation

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project directory:

   ```bash
   cd Cars24-Used-Car-Market-Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn requests beautifulsoup4 jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the analysis notebook and run the cells in sequence.

## 🔮 Future Improvements

- Expand the dataset with additional listings and locations.
- Improve scraping reliability with request timeouts, error handling, and data validation.
- Investigate outliers and missing data more systematically.
- Develop an interactive dashboard using Power BI.
- Build a used car price prediction model after validating data quality and selecting appropriate features.

## 👨‍💻 Author

**Anvesh Hirve**

Aspiring Data Analyst | Python | Exploratory Data Analysis | Power BI

Explore my other data analysis projects on GitHub and connect with me on LinkedIn.

---

⭐ If you find this project useful, consider giving the repository a star.
