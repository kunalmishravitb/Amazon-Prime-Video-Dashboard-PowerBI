# 📊 Amazon Prime Video Dashboard - Power BI

This repository contains an interactive Power BI dashboard that provides comprehensive insights into Amazon Prime Video titles, including movies and TV shows, spanning from the year 1920 to 2021. The dashboard was built using data analytics best practices to visualize key metrics such as genre distribution, ratings, release year trends, content type proportions, and country-wise availability.

## 🔍 Dataset

- **Source:** [amazon_prime_titles.csv](amazon_prime_titles.csv)
- **Total Titles:** 9,655
- **Time Period:** 1920 to 2021
- **Key Columns:**
  - `title`
  - `type` (Movie / TV Show)
  - `release_year`
  - `rating`
  - `genre`
  - `country`
  - `director`

## 📌 Dashboard Features

The dashboard includes the following visualizations and KPIs:

### 🔢 KPIs (Top Metrics)
- **Total Titles:** 9,655
- **Total Ratings:** 25 distinct rating categories
- **Total Genres:** 519 unique combinations
- **Total Directors:** 5,771 unique directors
- **Start Date:** 1920
- **End Date:** 2021

### 📈 Visual Insights

#### 1. **Ratings by Total Shows**
   - Shows categorized by rating groups (13+, 16+, 18+, etc.)
   - Highest count: **13+ rating** with 2.1K shows.

#### 2. **Genres by Total Shows**
   - Top genres include:
     - **Drama (986)**
     - **Comedy (536)**
     - **Drama, Suspense (399)**
     - And more...

#### 3. **Movies and TV Shows Distribution**
   - **TV Shows:** 7.81K (80.82%)
   - **Movies:** 1.85K (19.18%)

#### 4. **Total Shows by Country**
   - Visual representation of where the shows are produced or available.
   - Key contributing countries include USA, UK, India, and others.

#### 5. **Total Shows by Release Year**
   - Trendline showing exponential growth in content, especially post-2000.
   - Spike in recent years.

## 🛠 Tools Used

- **Power BI Desktop**
- **Microsoft Excel (for cleaning and preprocessing)**
- **Data Source:** Custom CSV dataset

## 📁 File Structure

```bash
📆 Amazon-Prime-Dashboard/
🗃️ amazon_prime_titles.csv         # Dataset used for the dashboard
📸 dashboard_screenshot.png        # Screenshot of the Power BI dashboard
📁 PowerBI_Dashboard.pbix          # (Optional) Power BI report file if publishing
📄 README.md                        # This file
```

## 🧐 Insights & Takeaways

- Drama and Comedy are the most popular genres on Amazon Prime Video.
- Most titles are suitable for ages 13+ or 16+.
- There is a rapid increase in the number of titles post-2000.
- Majority of content available are TV Shows rather than Movies.

## 📌 How to Use

1. Clone the repository.
2. Open `amazon_prime_titles.csv` in Power BI or Excel.
3. Use the `.pbix` file to view or customize the dashboard further.
4. Dashboard is also suitable for web publishing via Power BI Service.

## 📬 Contact

For questions or suggestions, feel free to connect via GitHub Issues or Discussions.

---

⭐️ *If you found this helpful, don’t forget to star the repository!*

