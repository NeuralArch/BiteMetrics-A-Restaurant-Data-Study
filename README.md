# BiteMetrics - A Restraunt Data Study  
**Author:** Ayush Kanojiya
**Period:** Aug 2025 – Nov 2025

---

## Project Overview
This project analyses restaurant data for Bangalore (Zomato dataset) to extract actionable insights on:  
- distribution of restaurants across locations/neighbourhoods  
- cuisine popularity by area and average ratings  
- price/cost patterns and affordability clusters  
- relationships between ratings, number of votes, and cost for two  

We performed end-to-end steps: data ingestion, cleaning, feature engineering, exploratory data analysis (EDA), visualization, and basic modelling/segmentation to highlight patterns useful for customers and small restaurant owners.

---

## Repository structure 
The repo contains 3 python notebooks and a csv file.

- **No additional scripts** or folders are required.
- The dataset file (e.g., `zomato_bangalore.csv`) should be placed in the same directory as the notebooks.

---

## 📝 Project Overview

The goal of this project is to analyze patterns among restaurants across different locations in Bangalore.  

### The analysis focuses on:
- Restaurant distribution across key localities  
- Cuisine types and popularity  
- Pricing trends (`cost_for_two`)  
- Ratings and review patterns  
- Relationships between cost and rating  
- Identifying clusters or standout regions  

The project is split into two stages, each in its own notebook.

---

## 🧹 1. restaurants_preprocessing.ipynb

This notebook handles:

### ✔ Data Loading & Cleaning
- Standardizing column names  
- Removing invalid or missing values  
- Cleaning the `cost_for_two` column  
- Extracting primary cuisine  
- Handling inconsistent rating formats  
- Removing duplicate entries  

### ✔ Exploratory Data Analysis (EDA)
- Most restaurant-dense locations  
- Distribution of ratings  
- Top cuisines by average rating  
- Cost analysis by locality  
- Votes vs rating relationships  

### ✔ Outputs
- A cleaned dataset (in-memory)  
- Multiple summary tables and plots  

---

## 📊 2. latlon.ipynb

This notebook:

### ✔ Scrapes latitude and longitude 
- area wise
- from google maps
- Cuisine distribution graphs  
- for the purpose of representing the location of the area on map in the dash board
- and stores them in the same csv file 

---

## 📊 2. restaurants_dashboard.ipynb

This notebook contains:

### ✔ Interactive Visualizations
- Location-based restaurant density charts  
- Cost vs rating scatterplots  
- Cuisine distribution graphs  
- Popularity and quality comparisons  

### ✔ Dashboard Elements 
- Dropdowns for selecting location or cuisine  
- Filters for rating / cost ranges  
- Interactive graphs (Plotly / Dash style)  

This notebook provides an **exploratory dashboard-style interface** to help understand trends quickly.

---


## 🚀 How to Run the Project

### 1. Install required Python libraries
pip install pandas numpy matplotlib seaborn plotly Dash selenium webdriver_manager urllib re
### 2. Open the notebooks
Use Jupyter Notebook or JupyterLab:

Then open:

1. `restaurants_preprocessing.ipynb`
2. `restaurants_dashboard.ipynb`

### 3. Add the dataset
Place `zomato_bangalore.csv` in the same folder.

---

## 🌟 Key Insights you can derive
- Which areas in Bangalore have the highest restaurant concentration  
- Most popular cuisines  
- Which cuisines have the *highest average rating*  
- Does higher price imply better ratings? (spoiler: *not always!*)  
- Identifying budget-friendly but well-rated restaurants  
- Outlier regions with unusually high/low prices  

---

## 📬 Contact

**Ayush Kanojiya**  
Email: ayushkanojiyaofficial2410@gmail.com 
LinkedIn: linkedin.com/in/ayush-kanojiya-462981313

---

## 📄 License
This project is for academic and learning purposes.  
Dataset belongs to Zomato or the respective source.
Latitudes and longitudes are scraped from Google maps for educational purspose.


