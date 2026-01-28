# -Olympic-Games-Data-Analytics-ETL-Project
Project Overview

As a Data Analyst for the International Federation of Athletica (IFA), I was tasked with transforming 120 years of historical Olympic data into an interactive executive dashboard. This project demonstrates a complete ETL (Extract, Transform, Load) workflow, moving from raw, inconsistent data to a polished Business Intelligence tool designed for executive decision-making.

🛠️ Technical Skills & Tools

Category	Tools & Techniques Used
Data Cleaning	IF, TRIM, ISBLANK, Standardizing "NA" values, Handling duplicates
Data Enrichment	XLOOKUP, VLOOKUP, Named Ranges, LEFT/MID text parsing
Analysis	Pivot Tables, Advanced Aggregations (AVERAGEIF), Logical Testing
Visualization	Interactive Dashboards, Slicers, Pivot Charts, Sparklines, Trendlines
Storytelling	Executive Summary Reporting, Data-Driven Business Insights
🚀 ETL Process Deep-Dive

1. Extract & Clean (The "T" in ETL)

Numeric Standardization: Handled inconsistent "NA" entries for Age, Height, and Weight using logical formulas to ensure statistical accuracy in averages.

Text Parsing: Created an Initials column and Decade identifiers using LEFT, MID, and FLOOR functions to enable more granular time-series analysis.

2. Transform & Enrich

Relational Mapping: Merged external Country Info tables with the core athlete dataset using VLOOKUP and Named Ranges to provide geographic context.

Dynamic Scaffolding: Categorized sports into Team vs. Individual groups using IF(OR(...)) logic to answer complex performance questions.

3. Load & Visualize (The Dashboard)

Built a high-fidelity dashboard featuring a dark-mode UI for better data readability.

Implemented Report Connections across multiple Slicers (Season, Sex, Sport Category) to allow for real-time, interactive data exploration.

📈 Key Business Insights

Long-Term Participation Trends: Female participation in the games has reached a total of 3,747 Gold Medals, showing a consistent upward trajectory over the last century.

Athlete Longevity: Trendline analysis indicates that the average age of medalists is steadily increasing, likely due to advancements in sports science and training.

Dominant Nations: Identified the USA, URS, and GER as the top 3 global leaders in Gold medal accumulation.

📂 Project Structure

/Raw_Data: Original "NA" heavy athlete events and country codes.

/Cleaned_Data: Processed Excel files with enriched columns and named ranges.

/Dashboard: Final .xlsx file containing the interactive visual interface.

Summary_Report.pdf: 1-page executive briefing.
