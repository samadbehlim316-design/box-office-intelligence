# 🎬 Movie Industry Analytics

### End-to-End Data Analytics Project | Python • Pandas • Excel • Power BI

**Movie Industry Analytics** is an end-to-end data analytics project that explores the global film industry through data cleaning, exploratory data analysis, and interactive business intelligence.

The project analyzes **9,591+ cleaned movie records** to understand box office performance, genre profitability, Oscar impact, audience ratings, film-industry performance, and long-term cinema trends.

---

## 👨‍💻 About the Project

**Created by: Samad Behlim**

This project demonstrates an end-to-end analytics workflow, starting with raw movie data and transforming it into meaningful business insights through **Python, Pandas, Excel, and Power BI**.

The primary objective is to answer practical business questions such as:

* Which movie genres generate the highest ROI?
* Does Oscar recognition have an impact on box office revenue?
* Which film industries perform better in terms of revenue, ROI, and audience ratings?
* How have movie ratings and revenues changed over the decades?
* Which release periods and genres show stronger performance?

---

## 🎯 Business Problem

The film industry generates large amounts of data related to budgets, revenue, ratings, genres, awards, directors, and production industries.

However, these individual data points become much more useful when combined and analyzed together.

This project connects these signals to provide insights into:

| Business Question                                     | Analysis                       |
| ----------------------------------------------------- | ------------------------------ |
| Which genres provide the best return?                 | Genre ROI Analysis             |
| Do Oscar-nominated movies perform better financially? | Oscar Impact Analysis          |
| Which film industries perform best?                   | Industry Comparison            |
| How has cinema changed over time?                     | Decade & Trend Analysis        |
| What factors are associated with successful movies?   | Revenue, Rating & ROI Analysis |

---

# 🔄 Project Workflow

```text
Raw Movie Dataset
      │
      ▼
Python + Pandas
      │
      ├── Data Inspection
      ├── Data Cleaning
      ├── Duplicate Removal
      ├── Data Validation
      ├── Missing/Unknown Value Analysis
      └── Exploratory Data Analysis
      │
      ▼
Cleaned Dataset
      │
      ├── CSV
      └── Excel
      │
      ▼
Power BI
      │
      ├── Data Modeling
      ├── DAX Measures
      ├── Interactive Visualizations
      ├── Slicers & Filters
      └── Business Analysis
      │
      ▼
Interactive 5-Page Dashboard
```

---

# 📊 Dataset

The dataset contains information about movies, including:

| Column                          | Description                                  |
| ------------------------------- | -------------------------------------------- |
| `ID`                            | Unique movie identifier                      |
| `Title`                         | Movie title                                  |
| `Overview`                      | Movie plot summary                           |
| `Release Date`                  | Original release date                        |
| `Popularity`                    | Movie popularity score                       |
| `Vote Average`                  | Audience rating                              |
| `Vote Count`                    | Number of audience votes                     |
| `Category`                      | Movie genre                                  |
| `Production Budget (USD M)`     | Production budget in USD millions            |
| `Box Office Collection (USD M)` | Box office revenue in USD millions           |
| `Oscar Nominated`               | Oscar nomination status                      |
| `Film Industry`                 | Film industry such as Hollywood or Bollywood |
| `Director`                      | Movie director                               |

**Original Dataset:** 18,520 records
**Final Cleaned Dataset:** 9,591 records
**Total Columns:** 13

---

# 🧹 Data Cleaning & Preparation

The raw dataset was processed using **Python and Pandas**.

### Key cleaning steps:

1. Loaded the raw Excel dataset using Pandas.
2. Inspected dataset structure, columns, data types, and record counts.
3. Removed duplicate movie IDs.
4. Removed duplicate movie titles.
5. Checked missing values across important fields.
6. Investigated unknown or incomplete director information.
7. Validated important analytical fields such as budget, revenue, rating, and release date.
8. Exported the cleaned dataset for further analysis in Excel and Power BI.

### Dataset Transformation

```text
18,520 Raw Records
        ↓
Duplicate ID Removal
        ↓
9,959 Records
        ↓
Duplicate Title Removal
        ↓
9,591 Final Records
```

---

# 🔎 Exploratory Data Analysis

Python was used to explore relationships and trends within the dataset.

The analysis focused on:

* Movie revenue distribution
* Production budget vs. box office revenue
* Genre performance
* Audience ratings
* Oscar-nominated movies
* Film industry comparison
* Movie production trends
* Decade-wise performance
* Release month performance
* ROI analysis

---

# 📈 Power BI Dashboard

The project includes a **5-page interactive Power BI dashboard** designed for business analysis.

### 1️⃣ Overview

Provides an executive-level summary of the movie industry.

**Key metrics include:**

* Total Box Office Revenue
* Number of Oscar-Nominated Movies
* Average Audience Rating
* Oscar Revenue Lift
* Revenue Trends Over Time

---

### 2️⃣ Industry Analyst

Compares major film industries based on:

* Total Revenue
* ROI
* Average Audience Rating
* Movie Output

This page helps identify differences in performance between industries such as Hollywood, Bollywood, and other global film industries.

---

### 3️⃣ Genre Performance

Analyzes movie genres based on:

* Total Revenue
* Average Rating
* ROI
* Number of Movies

This makes it possible to distinguish between **high-revenue genres and high-ROI genres**.

---

### 4️⃣ Oscar Impact

Analyzes whether Oscar-nominated movies demonstrate stronger financial and audience performance.

The analysis compares:

* Revenue
* Production Budget
* ROI
* Audience Rating
* Oscar vs. Non-Oscar Movies

---

### 5️⃣ Trends & Direction

Explores long-term movie industry trends.

The page includes:

* Decade-wise revenue trends
* Decade-wise audience ratings
* Best release months
* Director performance
* Historical industry patterns

---

# ⚙️ Key DAX Measures

The Power BI dashboard contains **18+ DAX measures**.

Some important measures include:

| DAX Measure            | Purpose                                                            |
| ---------------------- | ------------------------------------------------------------------ |
| `ROI Multiplier`       | Calculates Box Office Revenue ÷ Production Budget                  |
| `Oscar Revenue Lift %` | Measures revenue difference associated with Oscar-nominated movies |
| `Oscar Movie ROI`      | Calculates ROI for Oscar-nominated movies                          |
| `Revenue Growth %`     | Measures year-over-year revenue growth                             |
| `Best ROI Genre`       | Identifies the highest-performing genre by ROI                     |
| `Best Rated Decade`    | Identifies the decade with the highest average rating              |
| `Date Range Label`     | Creates a dynamic year-range label                                 |

---

# 💡 Key Business Insights

The dashboard is designed to help answer questions such as:

### 💰 Profitability

A genre generating the highest revenue is not necessarily the genre generating the highest ROI.

### 🏆 Oscar Impact

Oscar recognition can be analyzed against revenue, budget, ROI, and audience ratings to understand its financial association.

### 🌎 Industry Performance

Different film industries can be benchmarked using revenue, ROI, ratings, and movie output.

### 📅 Long-Term Trends

Decade-level analysis helps identify changes in movie production, audience ratings, and box office performance.

---

# 🛠️ Tech Stack

| Technology           | Purpose                      |
| -------------------- | ---------------------------- |
| **Python**           | Data processing & analysis   |
| **Pandas**           | Data cleaning & manipulation |
| **NumPy**            | Numerical operations         |
| **Matplotlib**       | Data visualization & EDA     |
| **Jupyter Notebook** | Development & analysis       |
| **Excel**            | Structured data storage      |
| **Power BI**         | Interactive dashboard        |
| **DAX**              | Business calculations & KPIs |

---

# 📁 Project Structure

```text
movie-industry-analytics/
│
├── movie.ipynb
│
├── top_rated_movies_final.xlsx
│
├── movie_cleaned-01_data.csv
│
├── movies_analyst.pbix
│
├── requirements.txt
│
├── .gitignore
│
└── assets/
    └── dashboard_preview.png
```

---

# 🚀 How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/movie-industry-analytics.git
cd movie-industry-analytics
```

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

## 3. Run the Python Notebook

Open:

```text
movie.ipynb
```

using **Jupyter Notebook or VS Code** and run the cells sequentially.

## 4. Explore the Power BI Dashboard

Open:

```text
movies_analyst.pbix
```

using **Power BI Desktop**.

---

# 📦 Requirements

```text
numpy
pandas
matplotlib
requests
openpyxl
```

---

# 📤 Project Outputs

| File                          | Description                           |
| ----------------------------- | ------------------------------------- |
| `movie.ipynb`                 | Python EDA and data-cleaning workflow |
| `movie_cleaned-01_data.csv`   | Cleaned movie dataset                 |
| `top_rated_movies_final.xlsx` | Final structured dataset              |
| `movies_analyst.pbix`         | Interactive Power BI dashboard        |
| `dashboard_preview.png`       | Dashboard preview                     |

---

# 🎓 Skills Demonstrated

This project demonstrates practical experience in:

* Python Programming
* Pandas
* Data Cleaning
* Exploratory Data Analysis
* Data Transformation
* Excel Data Handling
* Power BI
* DAX
* Data Visualization
* KPI Development
* Business Intelligence
* Analytical Thinking
* Dashboard Development

---

# 👤 Author

**Samad Behlim**

Aspiring Data Analyst / Python Developer

📍 Jaipur, Rajasthan, India

---

## ⭐ Project Highlights

**18,520+** Raw Movie Records
**9,591** Cleaned Records
**13** Dataset Columns
**5** Power BI Dashboard Pages
**18+** DAX Measures
**Python + Pandas + Excel + Power BI**

---

## 📌 Future Improvements

Potential future enhancements include:

* Adding more recent movie data
* Improving director information
* Adding streaming-platform analysis
* Including IMDb or Rotten Tomatoes data
* Building predictive models for box office revenue
* Creating a live/automated data pipeline
* Adding machine learning-based movie success prediction

---

### 📜 License

This project is intended for educational and portfolio purposes.
