# Youtube-Trending-Videos
Python-based EDA on YouTube Trending dataset using Pandas, Matplotlib, and Seaborn to analyze views, likes, comments, categories, and publishing trends.

# 📊 YouTube Trending Videos 2023 – Exploratory Data Analysis

### 🔍 Overview
This project explores the **YouTube Trending Videos dataset (2023)** to understand how videos gain popularity on YouTube. Through Exploratory Data Analysis (EDA), we examine user engagement behavior, category trends, and publishing patterns.

### 🎯 Problem Statement
Only a limited number of videos appear in YouTube’s **Trending section**, and the logic behind it is not publicly known. This project aims to answer:

**👉 What patterns, behaviors, and characteristics influence whether a video trends on YouTube?**

### 📌 Objectives
- Analyze engagement metrics (views, likes, comments)
- Identify the most successful video categories
- Understand publish time behavior (hour & weekday)
- Detect outliers in video performance
- Extract insights that explain video popularity

### 📊 Dataset Information
| Feature Type | Description |
|--------------|-------------|
| Basic Info | Title, Channel, Category, Tags |
| Engagement | Views, Likes, Comments |
| Upload Info | Publish Date & Time |
| Total Records | 10,001 trending videos (2023) |

### 🧹 Data Cleaning Performed
✔ Removed duplicate entries  
✔ Handled missing values  
✔ Converted datatypes (int, datetime)  
✔ Detected and treated outliers (IQR method)  
✔ Renamed and formatted columns where needed  

### 📈 Visualizations Performed
- Distribution of Views, Likes, Comments
- Category-wise count & engagement comparison
- Publish Hour & Weekday distribution
- Views vs Likes & Views vs Comments Relationship
- Correlation Heatmap & Pair Plot

### 💡 Key Insights
🔸 Engagement metrics are **highly skewed** → few videos go viral  
🔸 Categories dominating trending: **Entertainment, Music, People & Blogs**  
🔸 **4 PM – 7 PM** is the best time to publish  
🔸 Best days to post: **Monday, Wednesday, Friday**  
🔸 **Views and Likes are strongly correlated** → fast engagement matters  

### 🧠 Conclusion
✔ Trending videos receive fast user engagement  
✔ Video category and upload timing significantly influence performance  
✔ Popular categories consistently dominate trending  
✔ Engagement metrics (likes/comments) strongly predict video reach  

### 🗂 Files in this Repository
| File | Description |
|------|-------------|
| `YOUTUBE_TRENDING_VIDEOS_PROJECT.ipynb` | Full EDA Notebook |
| `YouTube PPT.pptx` | Presentation Slides |

### 👩‍💻 Author
**M. Poojitha**  
Batch 434  
📍 Telangana, India  
💡 Passionate about Data Science & Analytics  

---

If you like this project, consider giving it a ⭐ on GitHub! 😊🚀
