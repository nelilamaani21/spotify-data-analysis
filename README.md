# 🎵 Spotify Track Analytics Dashboard

Hi there! 👋 Welcome to my Spotify data analysis project. 

In this repository, I built an interactive Power BI dashboard to dig into over 8,500 Spotify tracks. The goal of this project is to uncover what actually drives a song's popularity, which genres are dominating, and how music release trends are shifting in the streaming era.

## 📁 The Data
All visualizations are based on the `spotify_data_clean.xlsx` dataset, which contains **8,582 tracks**. 
Some of the main columns I analyzed include track popularity, artist followers, genres, album type, and track duration.

## 🛠️ Tools & Methods
* **Power BI:** For building the interactive dashboard and visualizations.
* **Power Query:** Used to clean up the raw data, fix data types, and remove duplicates before the analysis phase.
* **DAX:** I wrote several custom measures to keep the dashboard dynamic. For instance, I used `CALCULATE` and `ALL` functions to make sure the "Album Type %" calculations stay accurate and don't break when users click on other filters.

## 💡 What I Found (Key Insights)
1. **The "Shrinking Song" Trend:** Songs are getting shorter! The average duration has dropped over the years and currently sits at **3.49 minutes**. It makes sense—shorter songs often get higher replay rates on streaming platforms.
2. **Pop & Country Rule:** These two genres heavily dominate the landscape, proving they have the most massive and stable listener bases compared to niche genres.
3. **Albums Aren't Dead:** Even in the "viral single" era, the majority of tracks (68.6%) are still released as part of a full Album. Singles (25.6%) mostly serve as promotional teasers.
4. **Followers ≠ Popularity:** Having the most followers (like Taylor Swift with 140M+) doesn't automatically mean holding the #1 most popular song. Today, a track's popularity relies heavily on playlist curation and viral trends, not just fanbase size.

## 🚀 How to View the Dashboard
If you want to interact with the dashboard:
1. Download the `Spotify_Dashboard.pbix` file from this repo.
2. Open it using **Power BI Desktop**.
3. Feel free to click around the charts to filter the data by genres, years, or release types!

---
**Created by:**
Nelil Amaani | Data Analyst
[Let's connect on LinkedIn!](https://www.linkedin.com/in/nelil-amaani-217201296)
