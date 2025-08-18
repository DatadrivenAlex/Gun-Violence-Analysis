# 🍫 Chocolate Bar Analysis

## 📌 Project Summary
This project analyzes the **Chocolate Bar Ratings dataset** from Kaggle, featuring expert evaluations of over **1,700 plain dark chocolate bars**.  
The ratings focus on **cacao flavor and tasting experience** (flavor, texture, aftermelt, overall impression) rather than health or ethical aspects.  

The dataset provides insights into chocolate quality worldwide by examining **manufacturers, bean origins, cocoa percentages, and ratings**.

---

## 📊 Key Attributes
- **Company** – Brand or producer (416 producers)  
- **Bar Name** – Chocolate variety or bean origin (1,039 variations)  
- **REF** – Unique identifier for each bar  
- **ReviewDate** – Year of evaluation  
- **CocoaPercent** – Cocoa content percentage  
- **Location** – Country of manufacturer (60 countries)  
- **Rating** – Score from **1.0 to 5.0** (taste-based)  
- **BeanType** – Cocoa bean type or blend (41 listed, many missing)  
- **BroadOrigin** – Country of bean source (100 origins)  

---

## ❓ Key Questions
- What is the **average chocolate rating by country**?  
- Which countries produce the **top 5 cocoa beans**?  
- Which countries host the **top 5 chocolate manufacturers**?  
- What’s the **relationship between rating and cocoa percentage**?  

---

## 📂 Repository Contents
- **Datasets**  
  - `Chocolate_Bar_ratings.csv` – Original dataset  
  - `Cleaned_ChocolateBarRating.csv` – Cleaned dataset  
  - `world.countries.json` – GeoJSON for mapping  

- **Notebooks**  
  - Data sourcing & preprocessing  
  - Exploratory Data Analysis (EDA)  
  - Geospatial visualizations  

---

## 📑 Data Source
- **Creator**: Brady Brelinski (Manhattan Chocolate Society)  
- **Host**: Kaggle – [Chocolate Bar Ratings Dataset](https://www.kaggle.com/datasets/rtatman/chocolate-bar-ratings)  
- **Type**: Community-driven, expert tasting reviews  
- **Credibility**: Expert but **subjective**, not industry-official  

---

## ⚠️ Data Limitations
- **Reuse rights**: Intended for research/learning, not commercial use  
- **Incomplete bean type details**: ~50% missing  
- **Sampling bias**: Reflects chocolate enthusiasts’ tastes, not general consumers  
- **Outdated coverage**: Reviews stop at 2017  

---

## 🧭 Ethical Considerations
- **Privacy**: No personal identifiers, minimal risks  
- **Representation**: Biased toward enthusiast community  
- **Transparency**: Ratings are subjective, interpret with caution  

---

## 🚀 Purpose
This project demonstrates practical skills in:  
- Data wrangling and cleaning  
- Exploratory Data Analysis (EDA)  
- Geospatial and statistical visualization  
- Data storytelling and interpretation  

The goal is to showcase **data analysis techniques** and present **insights into global chocolate trends**.
