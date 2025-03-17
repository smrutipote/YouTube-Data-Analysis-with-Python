
# YouTube Data Analysis with Python

## 📌 Project Overview
This project analyzes YouTube video data using Python to extract insights into trends, engagement, and performance metrics. The analysis includes data processing, visualization, and categorization of video attributes such as duration, views, likes, and comments.

## 📊 Features & Analysis
- **Data Collection:** Extracting YouTube video data using the YouTube API.
- **Data Cleaning & Processing:** Handling missing values, converting duration from ISO 8601 format to seconds.
- **Exploratory Data Analysis (EDA):**
  - Distribution of video views, likes, and comments.
  - Categorization of videos based on duration.
  - Analysis of engagement metrics.
- **Data Visualization:** Using `Seaborn` and `Matplotlib` to create insightful charts.
- **Trend Analysis:** Identifying patterns in video popularity.

## 🔧 Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `pandas` (data manipulation)
  - `numpy` (numerical operations)
  - `matplotlib` & `seaborn` (visualization)
  - `isodate` (duration parsing)
  - `googleapiclient` (YouTube API integration)

## 📂 Project Structure
```
YouTube Data Analysis with Python/
│-- YouTube Data Analysis with Python.ipynb  # Jupyter Notebook with analysis
│-- README.md           # Project documentation```

## 📈 Example Visualizations
Sample visualizations generated from the analysis:
- **View Count Distribution:**
  ```python
  sns.histplot(trending_videos['view_count'], kde=True)
  ```
- **Average View Count by Category:**
  ```python
  sns.barplot(y=categorical_viewcount.index, x=categorical_viewcount.values, palette='viridis')
  ```

## 🤝 Contributing
Contributions are welcome! Feel free to submit pull requests or open issues for improvements


