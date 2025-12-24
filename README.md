
# 🎬 Movie Data Analysis Project

## 📌 Overview

This project focuses on analyzing a movie dataset to uncover insights about movie popularity, audience ratings, and genre-wise trends. The analysis involves data cleaning, feature engineering, exploratory data analysis (EDA), and categorization of movies based on vote averages.

The project is designed to demonstrate practical data analysis skills using Python and pandas, making it suitable for portfolios, academic submissions, and beginner-to-intermediate data analytics roles.

---

## 📂 Dataset Description

The dataset contains information about movies with the following key columns:

* **Release_Date** – Year of release
* **Title** – Movie title
* **Popularity** – Popularity score
* **Vote_Count** – Number of votes received
* **Vote_Average** – Average rating (later categorized)
* **Genre** – Movie genres (multi-valued, comma-separated)

Some records contain missing values in the Genre column, which were handled during data cleaning.

---

## 🛠 Tools & Technologies Used

* **Python**
* **Pandas** – Data manipulation & cleaning
* **NumPy** – Numerical operations
* **Matplotlib / Seaborn** – Data visualization
* **Jupyter Notebook** – Development environment
* **GitHub** – Version control & project hosting

---

## 🔄 Project Workflow

### 1️⃣ Data Loading

* Loaded the dataset using pandas
* Inspected structure, data types, and missing values

### 2️⃣ Data Cleaning

* Handled missing values (especially in Genre column)
* Cleaned column names
* Converted data types where required

### 3️⃣ Feature Engineering

* Categorized `Vote_Average` into four levels:

  * `not_popular`
  * `below_avg`
  * `average`
  * `popular`
* Used quartile-based binning for fair categorization

### 4️⃣ Genre Processing

* Split multiple genres into individual values
* Used `explode()` to normalize genre data
* Handled missing genres by either removing or labeling them as `Unknown`

### 5️⃣ Exploratory Data Analysis (EDA)

* Popularity distribution analysis
* Vote average category analysis
* Genre-wise movie distribution

---

## 📊 Key Insights

* Popular movies generally receive significantly higher vote counts
* Certain genres dominate the popularity category
* Missing genre data can affect genre-wise insights and was handled carefully

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/movie-data-analysis.git
```

2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all cells to reproduce the analysis

---

## 📁 Repository Structure

```
movie-data-analysis/
│
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks
├── README.md            # Project documentation
└── requirements.txt     # Required libraries
```

---

## 🎯 Future Improvements

* Integrate external APIs (TMDB) for missing genre data
* Build interactive dashboards using Power BI or Streamlit
* Apply machine learning for popularity prediction

---

## 🙌 Acknowledgements

Dataset sourced from publicly available movie datasets (e.g., Kaggle / TMDB-inspired data).

---

## 📬 Contact

**Nikhil Dongare**
Aspiring Data Analyst / Data Science Student

---

⭐ If you found this project helpful, feel free to star the repository!
