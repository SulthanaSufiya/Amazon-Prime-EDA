# 📊 Amazon Prime EDA Capstone Project

A comprehensive exploratory data analysis (EDA) on Amazon Prime's TV Shows and Movies dataset to uncover patterns, trends, and actionable insights related to content type, ratings, genres, languages, and production regions.

---

## 📁 Dataset Information

Two datasets were used:

1. **titles.csv**  
   Contains information about each title on Amazon Prime including:
   - `title`, `type`, `release_year`, `runtime`, `genres`, `language`, `imdb_score`, `tmdb_score`, `age_certification`, `production_countries`, etc.

2. **credits.csv**  
   Contains cast and crew details for each title:
   - `name`, `character`, `role`, `person_id`

---

## 📌 Key Objectives

- Understand content diversity by type, genre, language, and country.
- Identify trends in ratings (IMDb, TMDB) and age certification.
- Evaluate the role of actors, directors, and production regions.
- Uncover release patterns and runtime distributions.
- Support data-driven decisions in content strategy and user engagement.

---

## 📈 Highlights of Analysis

- 🎬 **Movies dominate** Amazon Prime’s library, especially in Drama and Comedy genres.
- 🌍 **USA, India, and UK** are the leading production countries.
- ⭐ **IMDb and TMDB ratings** mostly range between 5–7, showing average audience reception.
- 🔞 **Majority of content** is for mature audiences (`TV-MA`, `R`).
- 🎭 **Frequent appearances** of certain actors/directors point toward franchise or exclusive deals.
- 📅 **Post-2015 surge** in content release aligns with global streaming growth.

---

## 🧠 Business Recommendations

1. **Content Acquisition**: Continue investing in popular genres (Drama/Comedy), and diversify into Sci-Fi, Family, or Kids content.
2. **Promotion Focus**: Boost high-rated titles in recommendations.
3. **Audience Expansion**: Introduce more PG and Family-rated content to balance maturity levels.
4. **Talent Strategy**: Leverage high-performing actors and directors through contracts/franchises.

---

## 📂 Repository Structure

```bash
├── Amazon Prime EDA.ipynb          # Jupyter Notebook with full code and insights
├── titles.csv                      # Amazon Prime Titles Dataset
├── credits.csv                     # Amazon Prime Credits Dataset
├── images/                         # Optional: folder for output charts
└── README.md                       # Project overview and documentation
```

---

## 🚀 Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab
- Exploratory Data Analysis (EDA)
- Data Cleaning & Visualization

---

## ✅ Conclusion

This EDA provides valuable insight into Amazon Prime's content strategy and viewer trends. The structured storytelling and data-backed suggestions can support better content curation, marketing, and recommendation decisions for a global audience.
