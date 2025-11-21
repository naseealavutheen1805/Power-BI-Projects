# 📊 Google Play Store App Insights – Power BI Project

This Power BI project analyzes Google Play Store app data to understand what drives app performance. The dashboard explores ratings, reviews, installs, app categories, price type, app size, and update trends.

## 🚀 Objectives
- Identify high-performing app categories
- Compare free vs paid apps
- Explore the relationship between installs, ratings, and reviews
- Understand how app size and updates influence performance

## 🧹 Data Cleaning (Power Query)
- Removed duplicates & blanks
- Cleaned **Installs** column (removed “+”, commas → numeric)
- Cleaned **Price** (removed `$` → numeric)
- Standardized **Size** column and handled “Varies with device”
- Converted **Last Updated** to date
- Fixed data types & standardized text

## 📊 Dashboard Highlights
- **Free vs Paid Apps** (Doughnut Chart)
- **Category-wise Average Rating**
- **Top Installed Apps**
- **Rating vs Reviews Scatter**
- **Installs by Category**
- **App Size Distribution**
- **Update Trend by Year**
- Interactive filters (Category, Type, Content Rating, Genres)

## 💡 Key Insights
- Most apps are **free**, leading to higher user engagement.
- Categories like **Education & Productivity** show stronger ratings.
- **App size has weak relation** with installs or ratings.
- Recently updated apps tend to perform better.

