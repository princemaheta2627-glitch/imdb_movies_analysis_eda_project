# 🎬 IMDB Movies Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **IMDB Top 1000 Movies Dataset** to uncover insights into movie ratings, revenue, genres, directors, runtime, audience engagement, and trends over time.

Using Python's data analysis libraries, this project answers real-world business questions and demonstrates practical data analysis skills through visualizations and statistical exploration.

---

## 🎯 Objectives

- Inspect and understand the dataset
- Perform data profiling and quality assessment
- Analyze movie ratings and runtime distributions
- Explore relationships between ratings and revenue
- Compare critic scores with audience ratings
- Identify top-performing directors
- Analyze genre-wise revenue
- Study yearly movie production trends
- Create custom movie categories using feature engineering

---

## 📊 Dataset Information

| Feature | Details |
|----------|----------|
| Dataset | IMDB Top 1000 Movies |
| Rows | 1,000 |
| Columns | 12 |
| Year Range | 2006 – 2016 |
| Missing Values | Revenue (128), Metascore (64) |
| Duplicate Rows | 0 |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure

```
IMDB_Movies_EDA/
│
├── 7-IMDB-Movie-Data.csv
├── imdb_eda_project.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── rating_distribution.png
│   ├── runtime_distribution.png
│   ├── runtime_vs_rating.png
│   ├── revenue_vs_rating.png
│   ├── top_directors.png
│   ├── genre_revenue.png
│   └── yearly_revenue.png
```

---

# 📈 Exploratory Data Analysis

The project covers:

- Dataset Inspection
- Missing Value Analysis
- Duplicate Detection
- Descriptive Statistics
- Rating Distribution
- Runtime Distribution
- Runtime vs Rating
- Rating vs Revenue
- Metascore vs Rating
- Director Performance Analysis
- Genre Revenue Analysis
- Movie Category Classification
- Long Movie Analysis
- Temporal Trend Analysis
- Actor Performance Analysis

---

# 📊 Key Visualizations

- 📉 IMDB Rating Distribution
- 📉 Runtime Distribution
- 📊 Runtime vs Rating
- 📊 Rating vs Revenue
- 📈 Revenue Trend by Year
- 📊 Votes by Year
- 📊 Top Directors
- 📊 Genre Revenue Analysis

---

# 🔍 Key Insights

- ⭐ Average IMDB Rating: **6.72**
- 🎬 Average Runtime: **113 minutes**
- 💰 Highest Grossing Genre: **Action + Sci-Fi**
- 🎥 Highest Rated Director: **Christopher Nolan**
- 📈 Revenue generally increased from **2006–2016**
- 🎭 Most movies fall into the **Good (6–7.9)** rating category
- 🎬 Only **3 movies** have runtimes longer than **180 minutes**
- 📊 Ratings have only a weak positive relationship with revenue
- 🎯 Critics and audiences generally agree on movie quality

---

# 💡 Feature Engineering

A custom function was created using `.apply()` to classify movies into:

| Category | Rating |
|----------|---------|
| ⭐ Excellent | >= 8.0 |
| 👍 Good | 6.0 – 7.9 |
| 📉 Average | < 6.0 |

---

# 📚 Python Concepts Used

- Data Cleaning
- Feature Engineering
- GroupBy Operations
- Sorting & Ranking
- Filtering
- Aggregation
- Custom Functions
- Lambda Functions
- Correlation Analysis
- Data Visualization

---

# 🚀 Future Improvements

- Movie Rating Prediction
- Revenue Prediction Model
- Genre-wise Recommendation System
- Sentiment Analysis on Movie Descriptions
- NLP-based Movie Similarity
- Interactive Dashboard using Streamlit
- Plotly Visualizations

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/imdb-movies-eda.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

Install manually

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

# 📸 Sample Output

Add screenshots of your charts inside the **images** folder.

Example:

```
images/
├── rating_distribution.png
├── runtime_vs_rating.png
├── genre_revenue.png
└── yearly_revenue.png
```

---

# 👨‍💻 Author

**Prince Maheta**

📚 Aspiring Data Scientist & Data Analyst

🔗 GitHub: https://github.com/princemaheta2627-glitch

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is intended for learning, educational, and portfolio purposes.
