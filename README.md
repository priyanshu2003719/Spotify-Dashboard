# Spotify Music Analysis(POWER BI DASHBOARD)


## 🟢 PROJECT DESCRIPTION: 
The Spotify Music Analysis project is a data-driven exploration of the most-streamed songs on the Spotify platform throughout 2023. This project leverages a comprehensive dataset of nearly 1,000 tracks to examine the relationship between a song’s technical musical attributes—such as tempo (BPM), energy, and danceability—and its commercial performance across global streaming charts (Spotify, Apple Music, Deezer, and Shazam). Through the use of advanced data visualization and Power BI modeling, the project transforms raw streaming figures into actionable insights regarding modern music trends.

## 🟢 PROJECT PURPOSE:
The purpose of this project is to identify the key drivers of global music popularity in the digital era. Specifically, it aims to:

1. Decipher "Hit" Characteristics: Determine if specific audio features (like high danceability or energy) correlate with higher stream counts.

2. Analyze Platform Synergy: Understand how presence in Apple Music or Deezer playlists affects a song’s overall performance on Spotify.

3. Identify Market Leaders: Highlight the artists and tracks that dominated the 2023 landscape (e.g., Taylor Swift and The Weeknd) to study their release patterns.

4. Optimize Release Timing: Examine temporal trends (months and days of the week) to pinpoint the most effective times for music launches based on historical streaming peaks.

## 🟢 PROJECT TECH STACK:
The workflow follows a standard data pipeline:

1. Data Source: Spotify 2023 Dataset.

 - <a href ="https://github.com/priyanshu2003719/Spotify-Dashboard/blob/main/Spotify%20All%20%20Dataset.xlsx"> Spotify Dataset</a>
   
2. ETL Layer: Power Query (Cleaning & Formatting).

3. Modeling Layer: Power BI DAX (Creating KPIs like "Avg Streams" and "Total Tracks").

4.  Presentation Layer: Power BI Dashboard (Charts and Interactive Slicers).

 - <a href ="https://github.com/priyanshu2003719/Spotify-Dashboard/blob/main/spotify.pbit">DASHBOARD</a>

## 🟢 PROJECT DATA SOURCE :
- <a href ="https://docs.google.com/spreadsheets/d/11eiH_HurRXnbymNc4pskPdKhnCtC79Tg/edit?gid=183885892#gid=183885892">DATASET SOURCE</a>

## 🟢 PROJECT FEATURES :
1. Business Problems:
   
a) Feature Correlation: "Does a high 'Danceability' or 'Energy' percentage directly correlate with a higher number of streams, or is song popularity independent of technical audio features?"

-> i)Analysis: The data shows a very weak negative correlation between streams and both Danceability ($-0.10$) and Energy ($-0.02$).
   
   ii)Solution: Song popularity is largely independent of these specific technical audio features. While a certain level of "danceability" is common, having a higher percentage does not guarantee more streams. Success is more likely driven by artist brand, marketing, and playlist placement rather than a specific audio "formula."

b)Platform Synergy: "Are tracks that perform well on Shazam (indicating discovery) more likely to reach the Top 10 on Spotify charts within the same month?"

-> i)Analysis: There is a strong positive correlation ($0.60$) between a track's rank on Shazam charts and its rank on Spotify charts.

  ii)Solution: Yes, tracks performing well on Shazam are highly likely to reach the Spotify Top 10. Shazam serves as an early discovery signal—when users "Shazam" a song in       the real world, it typically translates into Spotify streaming momentum within the same month.

c)Release Optimization: "Data shows high average streams for January releases—is this due to lower competition or a specific consumer behavior at the start of the year?"

-> i)Analysis: January releases have an average of 727 Million streams, which is significantly higher than most months (e.g., February at 353M).

   ii)Solution: This is likely due to lower competition. Fewer "blockbuster" albums are released in January, allowing individual tracks to capture a larger share of listener attention and hold top playlist positions for longer periods.

d)Artist Longevity vs. Viral Hits: "How much of the total stream share is held by 'Legacy' artists (tracks released before 2020) compared to new 'Viral' artists of 2023?"

-> i)Analysis:  Legacy Tracks (Pre-2020): Account for approximately 48.8% of total stream volume (approx. 238 Billion).

   ii)Viral 2023 Tracks: Account for roughly 5.3% of the total volume (approx. 25.8 Billion).

   iii)Solution: While 2023 hits generate massive "hype," the bulk of stream share is held by Legacy artists. This highlights the "long-tail" value of music—older hits continue to generate massive revenue long after their release year.

e)Playlist Impact: "What is the 'conversion rate' between being added to a Spotify playlist and actually appearing on the Apple Music or Deezer global charts?"

-> i)Analysis: There is a moderate correlation ($0.27$) between being in Spotify playlists and appearing on Apple Music charts.

  ii)Solution: Spotify playlisting is a gateway, but not a guarantee. While Spotify dominates in sheer volume, "conversion" to other platforms is selective. High performance on Apple Music or Deezer usually requires a track to first break a threshold of ~2,000+ Spotify playlists to gain enough global momentum.

f)Musical Trends: "Is there a dominant 'Key' (e.g., C# Major) or 'BPM' range that currently defines the top 100 tracks, and should new productions aim for these specifications?"

-> i)Analysis: Dominant Key: C# Major is the most frequent key among the Top 100 most-streamed tracks.

   ii) BPM Range: The average for top hits is 122 BPM, with a "sweet spot" between 100 and 140 BPM.

   iii) Solution: New productions should aim for C# Major or B Major and a tempo around 120 BPM. This range is universally effective for both casual mobile listening and radio/club play, maximizing the song's "reach" across different environments.


2. GOAL:

The goal of the Spotify Music Analysis project is to transform raw streaming data into strategic insights that decode the "formula" for global music success.

By analyzing the top-streamed tracks of 2023, the project aims to:

i)Decode Musical DNA: Identify if specific technical attributes like BPM (120 range), Key (C# Major), and Danceability are consistent drivers of high stream counts.

ii)Bridge the Platform Gap: Quantify how cross-platform presence (Spotify, Apple Music, Deezer, and Shazam) accelerates a song’s growth and total reach.

iii)Optimize Commercial Strategy: Pinpoint the most effective release windows—such as identifying why January and Fridays yield higher average engagement—to maximize a track's market impact.

iv) Differentiate Artist Performance: Compare the steady, long-term revenue of Legacy Tracks (pre-2020) against the high-velocity, short-term peaks of 2023 Viral Hits.

Ultimately, the project serves as a Data-Driven Roadmap for artists and record labels to move from intuitive guessing to informed, strategic decision-making in the digital streaming era.

3. Key Insights :

Based on the dashboard and data analysis, here is a brief walkthrough of the five key insights that define the 2023 music landscape:

i). The "Scale of Success" (KPIs)
The dataset reveals a massive total of 489 Billion streams across 952 tracks. On average, a "top-tier" song in this dataset generates approximately 514 Million streams, setting a high bar for what constitutes a global hit.

ii). Artist Dominance: The "Swift" Effect
Taylor Swift is the clear leader in market share, with 34 tracks in the most-streamed list. This highlights a shift in the industry where "superstar" artists occupy more chart real estate than ever before, driven by loyal fanbases and frequent high-quality releases.

iii). The "Shazam" Predictor
There is a strong 60% correlation between Shazam chart rankings and Spotify success.

Insight: Shazam acts as an early warning system. When a song starts being "discovered" via Shazam, it almost always translates into a massive surge in Spotify streams shortly after.

iv). Timing is Everything (The January Peak)
While most songs are released in May or during the summer, the highest average streams occur for songs released in January (727M).

Insight: Releasing during the "quiet" month of January allows a track to face less competition and dominate playlists for a longer period, leading to higher cumulative totals.

v). The "Hit" Formula: C# Major at 120 BPM
Analysis of the Top 100 tracks shows a recurring pattern in musical theory:

Key: C# Major is the most successful key.

Tempo: The "sweet spot" for engagement is 120 BPM.

Vibe: High Danceability (67%) is a baseline requirement, though not a guarantee of success on its own.

Summary: Success on Spotify is less about "viral luck" and more about a combination of technical specs (120 BPM), platform synergy (Shazam discovery), and strategic timing (January releases).


4. Business Impact & Insights:

The **Spotify Music Analysis** project translates complex streaming data into a strategic framework. Below are the core business insights and their direct impact on stakeholders like record labels, independent artists, and music marketers.

---

### **1. Key Business Insights**

* **The "Silent" Success of January:** While the industry focuses on summer hits, data shows that **January releases average 727M streams**, significantly higher than the mid-year average. This is due to a "blue ocean" strategy—releasing when major competitors are quiet.
* **Shazam as a Fortune Teller:** A **0.60 correlation** between Shazam and Spotify charts confirms that Shazam is a reliable "early warning" system. A track trending on Shazam is a high-probability candidate for upcoming viral success on Spotify.
* **The Blueprint of a Hit:** Global hits gravitate toward a **tempo of 120 BPM** and the **key of C# Major**. While these don't guarantee a hit, they represent the "sonic comfort zone" for the majority of global listeners.
* **Stability of the "Long-Tail":** Nearly **50% of total stream volume** comes from legacy tracks (released before 2020). This proves that while new hits drive hype, catalog management drives long-term financial stability.



---

### **2. Business Impact**

#### **A) Strategic ROI and Revenue Maximization**
By shifting major releases to high-performing months like **January or September**, labels can achieve higher visibility and a better return on marketing spend (ROMI). Instead of fighting for playlist space in crowded months, they capture a larger share of the audience's attention.

#### **B) Targeted Marketing (Risk Mitigation)**
Instead of spending millions on every new release, labels can use **Shazam discovery data** as a filter. They can wait for a track to "ping" on Shazam charts before committing large-scale global marketing budgets, effectively reducing the risk of "flops."



#### **C) A&R and Creative Direction**
For producers and songwriters, understanding that **120 BPM** and **Major keys** dominate the Top 100 provides a "safe harbor" for commercial projects. It allows creative teams to align their output with proven consumer listening habits without relying solely on "gut feeling."

#### **D) Catalog Valuation**
The data on **Legacy vs. Viral** tracks has a direct impact on the valuation of music catalogs. Investors and labels can see that "old" music is not a declining asset but a massive revenue engine that accounts for half of all streaming activity, justifying higher acquisition prices for classic catalogs.

---

### **Summary Table: From Data to Action**

| Business Problem | Data Insight | Strategic Action |
| :--- | :--- | :--- |
| **High Competition** | Jan/Sep have highest avg streams. | Schedule "A-List" releases in off-peak months. |
| **High Marketing Risk** | Shazam leads Spotify growth. | Use Shazam data to "greenlight" ad spend. |
| **Commercial Uncertainty** | 120 BPM / C# Major are dominant. | Optimize track technicals for mass-market appeal. |
| **Revenue Volatility** | 48% of streams are from Legacy tracks. | Focus on "evergreen" playlisting for older catalog items. |

By implementing these insights, a music organization moves from a **reactive** culture to a **proactive, data-driven powerhouse**, maximizing both cultural impact and financial growth.

## 🟢 PROJECT DASHBOARD:

![DASHBOARD PREVIEW](https://github.com/priyanshu2003719/Spotify-Dashboard/blob/main/Spotify%20dashboard.png).
