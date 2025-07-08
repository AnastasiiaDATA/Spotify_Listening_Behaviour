# Spotify Listening History Analysis

This project explores personal Spotify listening history data using Python and popular data science libraries. It showcases skills in data cleaning, time-based analysis, feature engineering, visualization, and behavioral analytics.

---

## 📁 Dataset

**Source:** [Kaggle - Top Spotify Listening History Songs in Countries](https://www.kaggle.com/datasets)  
The dataset contains nearly 150,000 rows of listening events with attributes such as:
- Track name, artist, album
- Timestamp of play
- Platform used (Android, iOS, Web, etc.)
- Skip behavior, shuffle status
- Start/end reasons (click, autoplay, etc.)

---

##  Tools Used

- `Pandas`, `NumPy` – data manipulation
- `Matplotlib`, `Seaborn` – static visualizations
- `Plotly` – interactive charts
- `Jupyter Notebook` – analysis environment

---

## 🔍 Analysis Sections

### 1. Data Cleaning & Feature Engineering
- Converted timestamps to datetime
- Extracted hour, day, month, year
- Created `minutes_played`, skip flags, etc.

### 2. Time-Based Listening Behavior
- Heatmap: Listening frequency by day of week and hour
- Monthly/yearly trends
- Evening hours had highest listening activity

### 3. Play Duration & Skip Behavior
- Most sessions under 3 minutes
- Skip rate fluctuates over time
- Shuffle increases skip likelihood

### 4. Top Artists & Tracks
- Identified most-played artists and tracks
- Bar charts for top 10

### 5. Platform Usage
- Android dominates usage
- Web/iOS/mac used less frequently

### 6. Session Start Reasons
- Autoplay and "trackdone" are common start reasons
- Manual clicks result in higher skip rates

---

## Visualizations

- Heatmap of activity by day/hour
- Distribution of play durations
- Skip rate over time
- Pie chart of platform usage

---

## Key Insights

- Evening is the most active listening period
- Skip behavior is influenced by how the song started
- Autoplay leads to more complete plays vs. manual play
- Users are less likely to skip when not shuffling
