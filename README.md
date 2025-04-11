# 🎷 Spotify Listening Trends (EDA Project)

This project explores global Spotify listening trends from 2017–2022 using the full `charts.csv` dataset provided by [Kaggle](https://www.kaggle.com/datasets/sashankpillai/spotify-top-200-charts). The dataset includes every "Top 200" and "Viral 50" chart published globally by Spotify over several years.

🔍 Through Exploratory Data Analysis (EDA), I explored how music trends vary over **countries**, **seasons**, **time**, and **rankings** — uncovering insights about song longevity, regional preferences, and streaming behavior.

---

## 📁 Dataset Overview

- 🗕️ Time Range: 2017 - 2022
- 🌍 Countries: 70+
- 🎵 Columns: `track_name`, `artist`, `rank`, `date`, `region`, `streams`, etc.

---

## 📊 Key Analyses & Visuals

### 🏆 Top Songs by Country

- Identified the top 5 most streamed songs for each country.
- Plotted trends for individual countries like 🇺🇸 USA and 🇲🇽 Mexico.

### 👑 Most Streamed Artists

- Found the most streamed artist in each country.
- December consistently featured **Ariana Grande** as the top global artist! 🎄✨

### 📉 Streams vs Rank

- Investigated correlation between song streams and chart position.
- Found a **weak negative correlation (\~–0.13)** — lower rank means more streams, but not always!

### 🗖️ Seasonal Streaming Patterns

- December showed a **clear global spike** in stream volume across all years.
- Other months remained relatively stable.

### 🕒 Song Longevity

- Explored the longest-lasting songs on national and global charts.
- Visualized rank trends over time for legends like *Mr. Brightside*, *Crimen*, and *Me Rehúso*.

### 🌍 Regional Growth in Small Countries

- Tracked monthly Spotify growth in smaller markets like 🇲🇦 Morocco, 🇧🇬 Bulgaria, and 🇱🇺 Luxembourg.
- Morocco showed a **huge spike in 2021**, while Bulgaria steadily grew year-over-year.

### 🤖 Clustering Countries by Listening Behavior

- Used **K-Means Clustering** to group countries based on their monthly streaming patterns.
- Found 8 distinct listening trend groups, including:
  - Mature, high-streaming markets
  - Emerging markets with steady growth
  - Countries with flat or delayed adoption

---

## 🖼️ Visual Highlights

All visualizations can be found in the [`visualizations/`](./visualizations/) directory, including:

- `avg_streams_per_cluster.png`
- `streams_vs_rank.png`
- `top_artists_by_country.png`
- `monthly_growth_small_countries.png`
- `song_longevity_trends.png`



---

## 💡 Conclusion

Spotify’s global charts reveal fascinating insights into how people consume music around the world. Whether it’s **Ariana dominating December**, **Mr. Brightside never leaving the charts**, or **Morocco’s explosive growth in 2021**, this project shows how music brings data to life 🎶📊

---

## 🚀 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (for clustering)

---

## 📬 Contact

Reach out via [GitHub](https://github.com/BarraHarrison) or connect on [LinkedIn](https://www.linkedin.com/in/barraharrison20091997/).

---

