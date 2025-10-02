# ✈️ Dynamic Pricing & Travel - Airfare Analysis from Jakarta

This project analyzes **flight ticket price patterns from Jakarta** to various domestic destinations in Indonesia.  
The analysis explores **price distribution, top destinations, temporal patterns, volatility, and business insights** that can be used for revenue management and strategic decision-making in the airline and OTA (Online Travel Agent) industry.

---

## 📑 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Key Analyses](#key-analyses)
- [Business Insights](#business-insights)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Future Work](#future-work)

---

## Overview
The project focuses on:
- Understanding airfare patterns from **Jakarta (CGK/JKTC/JKT)**.
- Detecting **price volatility** across destinations.
- Analyzing **temporal factors** such as booking time, days of the week, weekends, and seasonal trends.
- Providing **business insights and recommendations** for pricing strategies.

---

## Dataset
- **Source:** Kaggle — [Tiket.com Best Price for Flights from Jakarta](https://www.kaggle.com/datasets/datasciencerikiakbar/tiketcom-best-price-for-flights-from-jakarta) :contentReference[oaicite:0]{index=0}  
- **Format:** CSV with `|` separator  
- **Columns include:**  
  - `origin`, `destination`  
  - `depart_date`, `extract_timestamp`  
  - `best_price` (cleaned & converted)  

---

## Project Workflow
1. **Setup Environment**  
   Import Python libraries and set visualization styles.  

2. **Loading & Understanding Data**  
   Preview dataset, check structure, and inspect features.  

3. **Data Preprocessing**  
   - Convert data types  
   - Clean and normalize ticket prices  
   - Filter only flights from **Jakarta**  
   - Handle missing values  

4. **Feature Engineering**  
   Create new features such as:  
   - Days until departure  
   - Day of week & weekend indicator  
   - Monthly & temporal attributes  

5. **Exploratory Data Analysis (EDA)**  
   Visualize airfare trends, distributions, top destinations, and price dynamics.  

---

## Key Analyses
- **Descriptive Statistics** → Range, mean, median, and volatility of prices.  
- **Distribution Analysis** → Histograms & boxplots for outlier detection.  
- **Top Destinations** → Most popular flight routes from Jakarta.  
- **Price by Destination** → Comparison of mean & median prices.  
- **Temporal Patterns** → Weekday vs weekend premiums, monthly trends.  
- **Volatility Analysis** → Coefficient of Variation (CV) per destination.  
- **Advance Booking Analysis** → Relationship between booking window and airfare.  
- **Comprehensive Dashboard** → 4-in-1 visualization for quick insights.  

---

## Business Insights
Some key findings include:
1. **Top 3 Destinations:** Identified most popular domestic routes from Jakarta.  
2. **Weekend Premium:** Weekend flights are priced **higher than weekdays**.  
3. **High Volatility Routes:** Certain destinations have unstable pricing patterns.  
4. **Price Ranges:** Defined Interquartile Range (IQR) and outlier thresholds.  
5. **Booking Behavior:** Most customers book **X–Y days before departure** (median ~N days).  

---

## Technologies Used
- **Python 3.x**  
- **Pandas, NumPy** → Data processing  
- **Matplotlib, Seaborn** → Data visualization  
- **Datetime** → Time-based analysis  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/dynamic-pricing-travel.git
   cd dynamic-pricing-travel
    ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
    ```
3. Run the notebook/script:
   ```bash
   jupyter notebook analysis_airfare.ipynb
    ```

## Creator
Defrizal Yahdiyan Risyad
