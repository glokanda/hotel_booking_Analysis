

# Hotel Booking Analysis – Exploratory Data Analysis 

This project performs an **exploratory data analysis (EDA)** on a real-world **hotel booking dataset** to uncover patterns related to guest behavior, pricing, cancellations, and booking trends. Python is used for data cleaning, analysis, and visualization to support data-driven insights.

---

## Overview

The goal of this project is to analyze hotel booking data to understand:

* Booking and cancellation patterns
* Differences between **City Hotels** and **Resort Hotels**
* Guest demographics and country distribution
* Pricing trends across seasons and room types
* Length of stay behavior

The project follows a standard data analytics workflow:

**Load data → Explore data → Clean data → Analyze data → Visualize results → Summarize insights**

---

## Dataset

* **File:** `hotel_bookings.csv`
* **Records:** ~119,000 hotel bookings
* **Hotel Types:** City Hotel, Resort Hotel

### Key Features

* **Booking details:** lead time, arrival date, length of stay
* **Guest information:** adults, children, babies, country
* **Pricing:** ADR (Average Daily Rate)
* **Booking status:** canceled vs. not canceled
* **Room information:** reserved and assigned room types
* **Market data:** market segment, distribution channel

---

## Tools Used

* **Python**
* **Pandas** – data loading, cleaning, and manipulation
* **NumPy** – numerical calculations
* **Matplotlib & Seaborn** – static visualizations
* **Plotly** – interactive charts and maps
* **Jupyter Notebook**

---

## Project Steps

### 1. Data Loading & Exploration

* Loaded the dataset using Pandas
* Inspected dataset shape, columns, and data types
* Reviewed summary statistics and unique values
* Identified missing and inconsistent data

---

### 2. Data Cleaning

* Handled missing values in columns such as `country`, `agent`, and `company`
* Replaced undefined categorical values (e.g., meal types)
* Removed invalid bookings (records with zero guests)
* Created new calculated fields such as **ADR per person**

---

### 3. Exploratory Data Analysis (EDA)

Key analyses performed include:

* **Hotel comparison:** City Hotel vs. Resort Hotel bookings
* **Cancellation analysis:** total cancellations and monthly trends
* **Guest analysis:** top guest countries and geographic distribution
* **Pricing analysis:**

  * Average daily rate by month
  * Price comparison by hotel type
  * Room price per person by room type
* **Stay duration:** total nights stayed by guests
* **Market segments:** booking distribution by customer type and channel

---

### 4. Visualization

* Bar charts and count plots for booking and cancellation trends
* Line charts showing **monthly pricing trends**
* Box plots comparing **room prices by hotel and room type**
* Choropleth maps displaying **guest country distribution**
* Interactive charts for deeper exploration of insights

---

## Key Insights

The analysis revealed that:

* **City Hotels receive more bookings and cancellations** than Resort Hotels
* **Most guests come from Europe**, with Portugal, the UK, and France leading
* **Room prices vary significantly by season**, peaking in summer months
* **Resort Hotels are more expensive during peak vacation seasons**
* Longer stays are more common at **Resort Hotels**, while City Hotels see shorter stays
* Data cleaning significantly improved the accuracy of pricing and guest analysis

*All findings are supported by visualizations and calculations in the notebook.*

---

## What This Project Demonstrates

* Real-world data cleaning and preprocessing skills
* Strong understanding of exploratory data analysis
* Ability to analyze business-focused datasets
* Effective use of visualizations to communicate insights
* Practical Python skills relevant to data analyst roles

---

## Author

**GLOIRE KANDA**



