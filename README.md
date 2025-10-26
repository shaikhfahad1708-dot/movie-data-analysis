# 🎬 IMDb Movie Analysis

This project explores the IMDb dataset (1000 movies) to understand patterns in **ratings, revenue, and critic metascores** using Python and Pandas.

---

## 📊 Steps in Analysis
1. **Data Cleaning**
   - Handled missing values in `Revenue` and `Metascore`
   - Checked datatypes and column distributions

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics (`.describe()`)
   - Value counts for `Rating` and `Metascore`
   - Identified outliers (like *Nine Lives* with worst critic score)

3. **Visualization**
   - Histplot (distribution of Ratings)
   - Boxplots (Revenue by Genre)
   - Correlation Heatmap (Rating, Votes, Revenue, Metascore)

4. **Simple Machine Learning**
   - Logistic Regression to classify high vs low-rated movies
   - Evaluated with accuracy score & confusion matrix
   - Checked feature importance (which variables matter most)

---

## 🔑 Key Insights
- Most movies score between **6.0–8.0**
- Genres like **Action** and **Drama** dominate
- **Votes** and **Metascore** show strongest correlation with Ratings
- Critics vs audience scores sometimes diverge (*Nine Lives* is a clear example)

---

## 🛠️ Tech Stack
- Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/shaikhfahad1708-dot/movie-data-analysis.git
## 📓 View the Full Notebook
👉 [Open the Analysis on NBViewer](https://nbviewer.org/github/shaikhfahad1708-dot/movie-data-analysis/blob/main/IMDb_Movie_Analysis.ipynb.ipynb)
