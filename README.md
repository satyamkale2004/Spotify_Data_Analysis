# Spotify Data Analysis (Interactive Dashboard Creation Using MS Excel)
## Project Overview
To analyze user listening behavior on Spotify using raw data and transform it into meaningful insights through data cleaning, analysis, and visualization. This project aims to identify trends such as popular artists, albums, platforms used, playback habits, and skip behavior, visualized interactively using Microsoft Excel.
## DataSet Used
- <a href="https://github.com/satyamkale2004/Spotify_Data_Analysis/blob/main/spotify_history.csv.xlsx"> DataSet </a>
## Questions(KPI's) - Key Performance Indicators

1) Which are the top 10 most played artists and albums?
2) What is the count of plays by each start reason (e.g., track selection, autoplay, notification)?
3) How is the music consumption distributed across weekdays?
4) How frequently is the shuffle feature used?
5) What is the skip rate percentage?
6) Which platform (Android, iOS, Web) is most used for streaming?
7) What is the total number of unique plays (URIs)?

- Dashboard Interaction <a href="https://github.com/satyamkale2004/Spotify_Data_Analysis/blob/main/Spotify_Dashboard.png">View Dashboard <a/>
## Process Followed:
i) Data Collection
- Obtained raw Spotify streaming data (CSV/Excel format).
  
ii) Data Cleaning
1) Removed duplicates
2) Handled missing/null values
3) Standardized date and time columns
4) Extracted month and day from date fields
5) Normalized text formatting

iii) Data Analysis
1) Grouped and summarized data using pivot tables
2) Performed time series and categorical analysis
3) Derived metrics for skips, shuffles, start reasons, etc.
   
iv) Data Visualization in Excel
1) Built interactive slicers for Year and Month
2) Created bar, pie, and donut charts for KPI visualization
3) Applied professional formatting for clean UI presentation

## Dashboard
<img width="1853" height="610" alt="Spotify_Dashboard" src="https://github.com/user-attachments/assets/54682f1a-8022-46e0-99cc-46dcf3d7fec9" />

## Project Insights:
1) Most music starts were initiated manually through track selection.
2) Tuesday had the highest number of plays, suggesting user engagement early in the week.
3) Shuffle mode was used in 21% of plays, indicating preference for sequential listening.
4) 83% of songs were played completely, while 17% were skipped.
5) Users primarily streamed music through the Android platform.
6) A total of 1449 unique track plays were recorded.

## Final Conclusion:
This project effectively highlights how data analytics can be used to understand personal or user listening behavior on platforms like Spotify. By leveraging Excel for data transformation and dashboarding, this analysis provides clear and interactive insights into habits and trends — valuable for both users and music platform strategists.
