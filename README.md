# 🍽️ Cognifyz Data Analysis Project

## 📌 Project Overview

This project was completed as part of the **Cognifyz Technologies Data Analysis Internship**.

The objective of this project is to analyze restaurant data using **Python, Pandas, NumPy, Matplotlib, and basic statistical analysis techniques** to identify meaningful patterns related to cuisines, cities, ratings, pricing, online delivery, restaurant chains, reviews, votes, and services.

The project is divided into **3 levels and 13 analysis tasks**, covering data understanding, data cleaning, exploratory data analysis, geographic analysis, customer review analysis, and service analysis.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Understand and clean the restaurant dataset.
* Identify the most common cuisines.
* Analyze restaurant distribution across cities.
* Study restaurant price ranges.
* Analyze online delivery availability.
* Understand restaurant rating distributions.
* Analyze cuisine combinations.
* Perform geographic analysis using latitude and longitude.
* Identify and analyze restaurant chains.
* Analyze restaurant reviews and keywords.
* Study restaurant votes and their relationship with ratings.
* Analyze price range against online delivery and table booking.

---

## 🛠️ Technologies & Tools Used

| Tool / Technology    | Purpose                             |
| -------------------- | ----------------------------------- |
| **Python**           | Data analysis                       |
| **Pandas**           | Data cleaning and manipulation      |
| **NumPy**            | Numerical analysis                  |
| **Matplotlib**       | Data visualization                  |
| **Jupyter Notebook** | Analysis and documentation          |
| **CSV**              | Dataset and analysis outputs        |
| **GitHub**           | Project documentation and portfolio |

---

# 📊 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning & Validation
   ↓
Exploratory Data Analysis
   ↓
Cuisine Analysis
   ↓
City Analysis
   ↓
Price Analysis
   ↓
Delivery Analysis
   ↓
Rating Analysis
   ↓
Cuisine Combination
   ↓
Geographic Analysis
   ↓
Restaurant Chain Analysis
   ↓
Review Analysis
   ↓
Votes Analysis
   ↓
Price vs Services
   ↓
Insights & Findings
```

---

# 📁 Project Structure

```text
Cognifyz_Data_Analysis
│
├── Dataset
│   ├── restaurant_data.csv
│   └── restaurant_data_cleaned.csv
│
├── Step_1_Data_Understanding
│   └── Step_1_Data_Understanding.ipynb
│
├── Step_2_Data_Cleaning
│   └── Step_2_Data_Cleaning.ipynb
│
├── Step_3_Top_Cuisines
│   ├── Step_3_Top_Cuisines.ipynb
│   └── top_3_cuisines.csv
│
├── Step_4_City_Analysis
│   ├── Step_4_City_Analysis.ipynb
│   ├── city_analysis.csv
│   └── city_summary.csv
│
├── Step_5_Price_Range
│   ├── Step_5_Price_Range.ipynb
│   └── price_range_analysis.csv
│
├── Step_6_Online_Delivery
│   ├── Step_6_Online_Delivery.ipynb
│   ├── online_delivery_analysis.csv
│   └── delivery_rating_comparison.csv
│
├── Step_7_Restaurant_Ratings
│   ├── Step_7_Restaurant_Ratings.ipynb
│   ├── rating_distribution.csv
│   └── rating_summary.csv
│
├── Step_8_Cuisine_Combination
│   ├── Step_8_Cuisine_Combination.ipynb
│   ├── cuisine_combination_analysis.csv
│   └── top_10_cuisine_combinations.csv
│
├── Step_9_Geographic_Analysis
│   ├── Step_9_Geographic_Analysis.ipynb
│   ├── city_geographic_analysis.csv
│   ├── restaurant_geographic_data.csv
│   └── location_grid_analysis.csv
│
├── Step_10_Restaurant_Chains
│   ├── Step_10_Restaurant_Chains.ipynb
│   ├── restaurant_chain_analysis.csv
│   └── top_restaurant_chains.csv
│
├── Step_11_Restaurant_Reviews
│   ├── Step_11_Restaurant_Reviews.ipynb
│   ├── review_keyword_analysis.csv
│   ├── review_length_analysis.csv
│   └── review_rating_analysis.csv
│
├── Step_12_Votes_Analysis
│   ├── Step_12_Votes_Analysis.ipynb
│   ├── top_10_restaurants_by_votes.csv
│   ├── bottom_10_restaurants_by_votes.csv
│   ├── rating_by_vote_group.csv
│   └── votes_analysis_summary.csv
│
└── Step_13_Price_vs_Services
    ├── Step_13_Price_vs_Services.ipynb
    ├── price_range_summary.csv
    ├── price_vs_online_delivery.csv
    ├── price_vs_table_booking.csv
    └── price_vs_services_summary.csv
```

---

# 🔎 Level 1 — Basic Analysis

## Step 1 — Dataset Understanding

* Loaded the restaurant dataset.
* Checked dataset dimensions.
* Examined column names and data types.
* Checked missing values.
* Checked duplicate records.
* Reviewed numerical and categorical columns.
* Generated basic descriptive statistics.

---

## Step 2 — Data Cleaning & Validation

Performed basic data quality checks:

* Missing value analysis.
* Duplicate record checking.
* Column name standardization.
* Text/category validation.
* Numerical value validation.
* Rating and price range checks.
* Created a cleaned dataset.

Output:

```text
restaurant_data_cleaned.csv
```

---

## Step 3 — Top Cuisines

Analyzed restaurant cuisines to identify:

* Top 3 most common cuisines.
* Number of restaurants serving each cuisine.
* Percentage of restaurants serving each cuisine.

Output:

```text
top_3_cuisines.csv
```

Visualization:

* Top 3 Cuisines Bar Chart

---

## Step 4 — City Analysis

Analyzed restaurants by city to identify:

* City with the highest number of restaurants.
* Average restaurant rating by city.
* Cities with higher average ratings.
* Additional comparison using cities with sufficient restaurant records.

Outputs:

```text
city_analysis.csv
city_summary.csv
```

Visualizations:

* Restaurant Count by City
* Average Rating by City

---

## Step 5 — Price Range Distribution

Analyzed restaurants according to their price range.

The analysis includes:

* Restaurant count by price range.
* Percentage of restaurants in each price range.
* Price range distribution visualization.

Output:

```text
price_range_analysis.csv
```

Visualization:

* Price Range Distribution Chart

---

## Step 6 — Online Delivery

Analyzed online delivery availability.

The analysis includes:

* Number of restaurants offering online delivery.
* Percentage of restaurants offering delivery.
* Average rating with and without online delivery.

Outputs:

```text
online_delivery_analysis.csv
delivery_rating_comparison.csv
```

Visualizations:

* Online Delivery Distribution
* Rating Comparison by Delivery Availability

---

# 📈 Level 2 — Intermediate Analysis

## Step 7 — Restaurant Ratings

Analyzed restaurant rating distribution.

The analysis includes:

* Rating frequency.
* Rating ranges.
* Most common rating range.
* Average number of votes.
* Rating distribution.

Outputs:

```text
rating_distribution.csv
rating_summary.csv
```

Visualizations:

* Rating Distribution
* Rating Range Distribution
* Rating vs Votes

---

## Step 8 — Cuisine Combination

Analyzed combinations of cuisines offered by restaurants.

The analysis includes:

* Most common cuisine combinations.
* Restaurant count for each combination.
* Average rating by cuisine combination.
* Additional comparison for combinations with sufficient records.

Outputs:

```text
cuisine_combination_analysis.csv
top_10_cuisine_combinations.csv
```

Visualizations:

* Top Cuisine Combinations
* Average Rating by Cuisine Combination

---

## Step 9 — Geographic Analysis

Used restaurant **latitude and longitude** information to study geographic distribution.

The analysis includes:

* Restaurant locations.
* Geographic concentration.
* Restaurant count by city.
* Location grid analysis.

Outputs:

```text
city_geographic_analysis.csv
restaurant_geographic_data.csv
location_grid_analysis.csv
```

Visualizations:

* Restaurant Location Scatter Plot
* Geographic Distribution
* Top Cities by Restaurant Count

---

## Step 10 — Restaurant Chains

Identified restaurants appearing multiple times in the dataset as potential restaurant chains.

The analysis includes:

* Restaurant chain frequency.
* Number of outlets/records.
* Average rating.
* Total votes.
* Average votes.

Outputs:

```text
restaurant_chain_analysis.csv
top_restaurant_chains.csv
```

Visualizations:

* Top Restaurant Chains
* Average Rating by Chain
* Total Votes by Chain

---

# 🚀 Level 3 — Advanced Analysis

## Step 11 — Restaurant Reviews

Analyzed restaurant review text.

The analysis includes:

* Positive keywords.
* Negative keywords.
* Average review length.
* Review length distribution.
* Relationship between review length and rating.

Outputs:

```text
review_keyword_analysis.csv
review_length_analysis.csv
review_rating_analysis.csv
```

Visualizations:

* Positive Keyword Frequency
* Negative Keyword Frequency
* Review Length Distribution
* Review Length vs Rating

> Note: Positive and negative keywords were analyzed using a transparent predefined keyword-list approach because the project requirements do not specify a particular sentiment-analysis model or dictionary.

---

## Step 12 — Votes Analysis

Analyzed restaurant votes to identify:

* Restaurants with the highest number of votes.
* Restaurants with the lowest number of votes.
* Average votes.
* Median votes.
* Votes distribution.
* Relationship between votes and ratings.

Outputs:

```text
top_10_restaurants_by_votes.csv
bottom_10_restaurants_by_votes.csv
rating_by_vote_group.csv
votes_analysis_summary.csv
```

Visualizations:

* Top 10 Restaurants by Votes
* Lowest 10 Restaurants by Votes
* Votes Distribution
* Votes vs Rating
* Average Rating by Vote Group

---

## Step 13 — Price Range vs Services

Analyzed the relationship between restaurant price range and service availability.

Services analyzed:

* Online Delivery
* Table Booking

The analysis includes:

* Restaurants by price range.
* Online delivery percentage by price range.
* Table booking percentage by price range.
* Comparison of service availability across price ranges.

Outputs:

```text
price_range_summary.csv
price_vs_online_delivery.csv
price_vs_table_booking.csv
price_vs_services_summary.csv
```

Visualizations:

* Restaurants by Price Range
* Online Delivery by Price Range
* Table Booking by Price Range
* Combined Service Availability

---

# 📊 Key Analysis Areas

```text
🍽️ Cuisines
      ↓
🏙️ Cities
      ↓
💰 Price Range
      ↓
📦 Online Delivery
      ↓
⭐ Ratings
      ↓
🥘 Cuisine Combinations
      ↓
📍 Geographic Distribution
      ↓
🏢 Restaurant Chains
      ↓
📝 Reviews
      ↓
🗳️ Votes
      ↓
📅 Services Analysis
```

---

# 💡 Skills Demonstrated

Through this project, I practiced:

### Python

* Pandas
* NumPy
* Matplotlib
* Functions
* DataFrame operations
* GroupBy
* Aggregation
* Sorting
* Filtering
* Merging
* Correlation analysis
* Basic text processing

### Data Analysis

* Data Understanding
* Data Cleaning
* Data Validation
* Exploratory Data Analysis
* Categorical Analysis
* Numerical Analysis
* Geographic Analysis
* Correlation Analysis
* Text/Keyword Analysis
* Business-oriented interpretation

### Data Visualization

* Bar Charts
* Histograms
* Scatter Plots
* Comparative Charts

### Project Skills

* Jupyter Notebook documentation
* CSV output generation
* Structured project organization
* GitHub project documentation

---

# 📌 Project Outcomes

This project provided practical experience in analyzing restaurant data from multiple perspectives, including:

* Cuisine preferences
* Restaurant locations
* Pricing
* Ratings
* Customer reviews
* Votes
* Restaurant chains
* Online delivery
* Table booking

The analysis demonstrates how raw restaurant data can be transformed into structured information and visual insights using Python.

---

# ⚠️ Analysis Notes

* Results are based on the provided restaurant dataset.
* Correlation indicates association and does not establish causation.
* Small groups should be interpreted carefully.
* Restaurant names appearing multiple times were treated as potential chains for analysis.
* Review keyword analysis used a predefined keyword approach rather than a machine-learning sentiment model.
* Price range categories were analyzed according to the values available in the dataset.

---

# 📂 Dataset

The project uses the restaurant dataset provided for the Cognifyz Data Analysis Internship.

The original dataset is preserved separately from the cleaned dataset:

```text
Dataset/
├── restaurant_data.csv
└── restaurant_data_cleaned.csv
```

---

# 🎓 Internship Project

**Organization:** Cognifyz Technologies
**Project:** Data Analysis Internship
**Domain:** Restaurant Data Analysis
**Tools:** Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

---

# 👨‍💻 Author

**Vikash Rao**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

---

## ⭐ If you find this project useful

Feel free to explore the notebooks and analysis files to understand the complete data-analysis workflow from **data cleaning to advanced analysis and visualization**.
