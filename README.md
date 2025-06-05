# 📊 Restaurant Data Analysis Project – Cognifyz Internship

Welcome to my data analysis project developed as part of the **Level 1 and Level 3 Data Analysis Internship** at **Cognifyz Technologies** – *Where Data Meets Intelligence*.  
This project explores a real-world restaurant dataset to uncover insights about cuisines, cities, pricing, online delivery, reviews, and more.

---

## 📁 Dataset
- The dataset contains detailed information about restaurants including:
  - Name
  - Cuisines
  - City
  - Rating
  - Price Range
  - Online Delivery, Table Booking, etc.
  - Customer Reviews and Votes

---

## 🔧 Tools Used
- Python 🐍
- Pandas 🐼
- NumPy 🔢
- Seaborn 🎨
- Jupyter Notebook / Google Colab 📓

---

## ✅ Task Summary

### 🔹 Level 1 – Exploratory Data Analysis (EDA)

#### 📌 Task 1: Top Cuisines
- **Objective**: Find the top 3 most common cuisines.
- **Methods**:
  - Used `.explode()` to handle multiple cuisines per restaurant.
  - Calculated percentage share of top cuisines.
- **Output**: Top cuisines with their restaurant share in the dataset.

---

#### 📌 Task 2: City Analysis
- **Objective**:
  - Identify the city with the highest number of restaurants.
  - Calculate average rating per city.
  - Find the city with the highest average rating.
- **Methods**:
  - Used `.value_counts()` and `.groupby()` on city.
  - Used `.idxmax()` to extract the top-rated city.
  
---

#### 📌 Task 3: Price Range Distribution
- **Objective**:
  - Visualize price range distribution.
  - Calculate percentage of restaurants per price category.
- **Methods**:
  - Used `seaborn.countplot()` for visualization.
  - Calculated frequency and percentages using `value_counts(normalize=True)`.

---

#### 📌 Task 4: Online Delivery Analysis
- **Objective**:
  - Determine what percent of restaurants offer online delivery.
  - Compare average rating of restaurants with and without online delivery.
- **Methods**:
  - Filtered dataframe on `Has Online Delivery`.
  - Used `.groupby()` and `.mean()` to compare ratings.

---

### 🔹 Level 3 – Advanced Insights

#### 📌 Task 1: Restaurant Reviews
- **Objective**:
  - Identify common positive and negative keywords.
  - Calculate average review length.
  - Explore link between review length and rating.
- **Methods**:
  - Performed basic NLP using `str.split()` and word frequency.
  - Calculated review length and used `.corr()` to analyze relationship.

---

#### 📌 Task 2: Votes Analysis
- **Objective**:
  - Identify restaurants with the highest and lowest number of votes.
  - Check if there's a correlation between votes and ratings.
- **Methods**:
  - Used `.nlargest()` and `.nsmallest()`.
  - Used `.corr()` to find correlation between `Votes` and `Rating`.

---

#### 📌 Task 3: Price Range vs. Services
- **Objective**:
  - Check if higher-priced restaurants offer online delivery or table booking.
- **Methods**:
  - Grouped by `Price range`, `Has Online delivery`, and `Has Table booking`.
  - Used visualization (bar plots) to analyze patterns.

---



