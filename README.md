# 📺 Netflix EDA Project

Welcome to the **Netflix Dataset Exploratory Data Analysis (EDA)** project.

This project performs an end-to-end exploratory analysis on the Netflix titles dataset. The goal is to uncover insights into the type of content available on Netflix, content distribution over the years, popular genres, countries, and more.

---

## 📌 Dataset

The dataset used is [`netflix_titles_with_duplicates.csv`](https://github.com/yashwanth4621v/Netflix-Dataset-EDA/blob/main/netflix_titles_with_duplicates.csv), which contains information about movies and TV shows available on Netflix as of 2021.

### Columns Included:

- `show_id`: Unique ID for every show.
- `type`: Movie or TV Show.
- `title`: Title of the show.
- `director`: Director of the show.
- `cast`: Cast involved in the show.
- `country`: Country of production.
- `date_added`: Date it was added to Netflix.
- `release_year`: Release year of the content.
- `rating`: TV rating.
- `duration`: Duration of the show.
- `listed_in`: Genre.
- `description`: Short summary.

---

## 🧠 Objective

- Perform data cleaning and handle missing values.
- Extract new features (`year_added`, `month_added`).
- Visualize distribution of content by type, year, country, and genre.
- Summarize key insights using statistical and graphical techniques.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab

---

## 🔍 Key Operations Performed

- Dataset loading and inspection (`df.head()`, `df.info()`, `df.describe()`)
- Handling missing values using **median** (for numerical) and **mode** (for categorical)
- Removing duplicate records
- Extracting `year_added` and `month_added` from `date_added`
- Count plots and pie charts using `seaborn` and `matplotlib`
- Feature engineering on multi-valued columns like `country`, `listed_in`, `cast`
- Summary dictionary for reporting major insights

---

## 📊 Visualizations Included

- Content added by year (bar plot)
- Top countries producing content (bar plot)
- Most common genres (bar plot)
- TV Show vs Movie distribution (pie chart)
- Missing value heatmap

---

## 📌 Summary of Insights

- Most content was added between 2018–2020.
- The United States contributes the most to Netflix’s content.
- Dramas, International Movies, and Comedies are the most common genres.
- The platform has a higher number of Movies than TV Shows.
- Many missing values were successfully handled using central tendency measures.

---

## 📝 How to Run

1. Clone this repository or open it in Google Colab.
2. Upload the `netflix_titles_with_duplicates.csv` dataset.
3. Run all the cells in the notebook from top to bottom.
4. View graphs and summaries to understand the content distribution.

---

## 🤝 Acknowledgements

- Dataset source: [Kaggle - Netflix Movies and TV Shows](https://github.com/yashwanth4621v/Netflix-Dataset-EDA/blob/main/netflix_titles_with_duplicates.csv)
- Tools used: Google Colab, Jupyter, Python libraries.

---
