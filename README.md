
# 🎬 IMDB Movie Data Analysis: Uncovering the Secrets of Cinema
An Exploratory Data Analysis (EDA) project investigating what makes a movie successful.

# 📌 Project Overview
This project analyzes a dataset of the top 1,000 movies on IMDB to identify trends in ratings, revenue, and genre popularity. Beyond basic statistics, this analysis explores the "disagreement" between critics and fans and evaluates the "Star Power" of lead actors.

# 🛠️ Tech Stack
Language: Python

Libraries: * Pandas (Data Manipulation)

Matplotlib & Seaborn (Data Visualization)

NumPy (Numerical Operations)


# 🧹 Data Cleaning Process (The "Phase 3" Heavy Lifting)
- Before analysis, the raw data was "noisy." Key cleaning steps included:
- Data Type Conversion: Converted Runtime (string to int) and Gross revenue (string to float).
- Handling Missing Values: Applied median imputation for missing Gross revenue to maintain a robust sample size.
- Feature Engineering: Created a Rating Gap metric to measure the difference between critic scores (Meta_score) and user ratings.

# 📊 Key Insights & Visualizations
1. The Revenue vs. Rating Myth
I discovered that while high-budget movies dominate the box office, they do not always correlate with the highest IMDB ratings.

2. Genre Profitability
While Drama is the most frequent genre, Sci-Fi and Animation consistently command the highest average revenue per movie.

3. The "Critic-Fan" Divide (Wildcard Insight)
I identified a subset of movies where critics and fans had a variance of over 20%. This suggests that certain genres (like Horror) are often "underrated" by professional critics compared to the general public.

# 🚀 How to Run
Clone this repository:

```
git clone https://github.com/yourusername/imdb-analysis.git
Install dependencies:
```

```
pip install pandas seaborn matplotlib
Run the Jupyter Notebook or Python script:
```

```
python main.py
```

# 💡 Future Work
1. Implement a Recommendation System based on genre and director.
2. Perform Sentiment Analysis on movie descriptions to see if "darker" descriptions lead to higher ratings.
