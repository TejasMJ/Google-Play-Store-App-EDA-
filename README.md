# Google Play Store Apps EDA 📊

A comprehensive **Exploratory Data Analysis (EDA)** on 10,000+ Google Play Store apps using Python, Pandas, Plotly, Seaborn, and Matplotlib to uncover insights about the Android app ecosystem.

---

## 🌟 Features

### Core Features
- **Data Cleaning & Preprocessing:** Handling missing values, duplicates, and type conversions.
- **Statistical Insights:** Summary statistics, distribution analysis, and outlier detection.
- **Category & Rating Analysis:** Visualizations to understand which app categories perform best.
- **User Engagement Analysis:** Insights on app installs, reviews, and ratings.
- **Pricing & Revenue Insights:** Analysis of Free vs Paid apps and monetization trends.
- **Visualization:** Interactive and static plots using Plotly, Seaborn, and Matplotlib.

---

## 🗂 Project Structure

The project folder is organized as follows:

```text
Google_Play_Store_EDA/
├── googleplaystore.csv               # Dataset of 10k Google Play Store apps
├── Google_PlayStore_Apps_EDA.ipynb   # Jupyter Notebook with full EDA
├── requirements.txt                  # Python dependencies
└── venv/                             # Virtual environment
```

---

## 🏗️ System Architecture

```text
+----------------------+  
|      DATA LAYER      |  
|  Raw app dataset     |  
|  (CSV / Excel)       |  
+----------+-----------+  
           ↓  
+-------------------------+  
|  ANALYSIS LAYER         |  
|  - Data Cleaning        |  
|  - Statistical Insights |  
|  - Category & Rating    |  
|    Analysis             |  
|  - User Engagement      |  
|  - Pricing & Revenue    |  
+----------+--------------+  
           ↓  
+---------------------------------------+  
| VISUALIZATION LAYER                   |  
|  - Interactive Dashboards (Plotly)    |  
|  - Static Plots (Seaborn & Matplotlib)|  
|  - Scatter, Bar, Boxplots             |  
+---------------------------------------+  

```

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Data Source:** [Kaggle – Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

---

## 📊 Dataset Overview

- **Rows:** 10,000+ apps  
- **Columns include:** App Name, Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, Genres, Last Updated, Current Version, Android Version.  

**Context:**  
While Apple App Store data is widely available, Google Play Store data is harder to scrape due to dynamic page loading. This dataset provides structured insights for Android apps.

**Acknowledgements:**  
- Data sourced from Google Play Store via Kaggle (L. Gupta, 2019).  
- Thanks to Kaggle contributors for making this dataset accessible.

**Inspiration:**  
Understanding app trends and user preferences can guide developers, marketers, and researchers to make data-driven decisions in the Android ecosystem.

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone <repo_url>
cd Google_Play_Store_EDA
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```
### 3. Activate Virtual Environment
#### Windows:
```bash
.\venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```
### 5. Run Notebook

```bash
jupyter notebook
```

# 📊 App Analysis Project

## Detailed Analysis Scope

### Data Cleaning & Preprocessing
- Remove duplicates
- Handle missing values
- Convert column types (e.g., `Rating` to float, `Installs` to numeric)

### Statistical Insights
- Summary statistics (mean, median, mode, standard deviation)
- Distribution analysis for `Rating`, `Installs`, and `Price`
- Outlier detection for extreme values

### Category & Rating Analysis
- Average rating per category
- Most and least rated categories
- Category vs Installs analysis

### User Engagement Analysis
- Correlation between `Reviews`, `Rating`, and `Installs`
- Identify top trending apps

### Pricing & Revenue Insights
- Free vs Paid apps distribution
- Price analysis and trends
- Paid apps with highest installs

### Visualization
- Interactive dashboards using **Plotly**
- Static plots using **Seaborn** & **Matplotlib**

## 👨‍💻 Author
**Tejas Jadhav**  

- GitHub: [@tejas-jadhav](https://github.com/tejas-jadhav)  
- LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-jadhav)
