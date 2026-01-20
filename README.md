# 🏏 IPL Match Data Analysis (2008–2024)

This repository contains a comprehensive **Exploratory Data Analysis (EDA)** project on Indian Premier League (IPL) match data from **2008 to 2024** (total **1095 matches** and **20 features**).

The objective of this project is to transform raw IPL match records into meaningful insights by applying:
- Data cleaning and preprocessing
- Aggregation and feature transformation
- Visualization of trends and patterns
- Interpretation of analytical results

This analysis highlights patterns in team performance, season growth, match venues, city hosting trends, toss impact, and result distributions.

---

## 📋 Project Details

The dataset includes match-level information such as:
- Teams (`team1`, `team2`, `winner`)
- Match outcomes (`result`, `result_margin`)
- Toss decisions and results (`toss_winner`, `toss_decision`)
- Venue and city details
- Match specifics (target runs, overs, method used)

This project is designed to demonstrate real-world data analysis skills using Python and common data science tools.

---

## 📊 Key Insights

1. **Most Matches Played**  
   - *Mumbai Indians* have played the most matches in IPL history (261).

2. **Most Matches Won**  
   - *Mumbai Indians* lead with 144 wins, followed by:
     - Chennai Super Kings (138)
     - Kolkata Knight Riders (131)

3. **Venue Distribution**  
   - *Wankhede Stadium* (Mumbai) hosted the most IPL matches overall.
   - Only 2 matches were played at:
     - OUTsurance Oval
     - Dr. Y.S. Rajasekhara Reddy ACA-VDCA Stadium (Visakhapatnam)

4. **City Hosting Trends**  
   - *Mumbai* is the most frequent IPL host city.

5. **Toss Impact**  
   - Out of 1095 matches:
     - Toss winners won 554 matches
     - Toss winners lost 536 matches
   - Winning the toss shows only a small advantage.

6. **Season Growth**  
   - The number of matches per season indicates expansion and scheduling changes over the years.

---

## 🛠 Tools & Libraries Used

The analysis was completed using:

- **Python**
- **Pandas** – Data manipulation and transformation
- **Matplotlib** – Graphical visualization

---

## 🧹 Data Cleaning & Preprocessing

Preprocessing steps include:

- Converting `date` column from object to datetime
- Handling missing data:
  - `method` → replaced missing values with “Normal”
  - `city` → replaced missing values with “Unknown”
- Normalizing team names across columns
- Ensuring no duplicate rows exist

---

## 📈 Visualizations Included

- Matches played by team (bar chart)
- Matches won by team (bar chart)
- Matches per season (line chart)
- City-wise match distribution (bar chart)
- Toss impact on match results (pie chart)
- Additional team comparisons

Each chart includes interpretation notes to explain trends clearly.

---

## ⚠ Limitations

The current dataset has the following constraints:

- No ball-by-ball details are available
- Player-level performance metrics are not included
- External game factors (weather, pitch reports, injuries) are not reflected

---

## 🚀 Future Scope

Future enhancements could include:

- Adding **ball-by-ball data** for deeper analysis
- Combining player statistics for individual performance evaluation
- Building **ML models** to:
  - Predict match winners
  - Estimate win probabilities
- Creating an **interactive dashboard** (e.g., using Streamlit)
- Applying regression and classification techniques after further learning

---

## 🧾 Conclusion

This project demonstrates end-to-end data analysis skills using a real-world sports dataset. It reflects the ability to clean, explore, visualize, and interpret complex data using Python — a core foundation for data science and machine learning workflows.

---
