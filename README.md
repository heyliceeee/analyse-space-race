# 🚀 Space Missions Analysis

## 📘 Overview
This project analyzes global space missions from **1957 to 2020**, covering the entire **Space Race** era and beyond. The dataset, scraped from *NextSpaceFlight*, includes every recorded launch since the dawn of space exploration — from the Cold War rivalry between the **USA** and **USSR** to the rise of modern commercial and Asian space agencies.

---

## 🧠 Objectives
- Explore historical trends in space launches.  
- Compare launch performance between major nations and organizations.  
- Evaluate mission success rates and technological progress over time.  
- Visualize spending patterns and cost evolution in space programs.  

---

## 🧰 Tools & Libraries
- **Python**  
- **NumPy**, **Pandas** — data cleaning and manipulation  
- **Plotly**, **Matplotlib**, **Seaborn** — interactive and static visualizations  
- **iso3166** — country code standardization  
- **Datetime** — time-based analysis  

---

## 🧹 Data Preparation
- Removed duplicates and columns with excessive missing values.  
- Cleaned country names and standardized them to ISO Alpha‑3 codes.  
- Converted dates to proper datetime format for temporal analysis.  
- Preserved essential fields like *Price* and *Mission_Status* for deeper insights.  

---

## 📊 Key Analyses
| Topic | Description | Insight |
|-------|--------------|----------|
| **Launches by Organisation** | Count and visualize missions per agency. | USSR dominated early space activity. |
| **Rocket Status** | Compare active vs retired rockets. | Most rockets are retired, showing historical decline. |
| **Mission Success Rate** | Distribution of mission outcomes. | ~90% success rate overall. |
| **Launch Costs** | Histogram of launch prices. | Majority under \$50 M; few exceed \$200 M. |
| **Launches by Country** | Choropleth map of global activity. | USA, Russia, and China lead globally. |
| **Failures by Country** | Map of failed missions. | Failures concentrated in major space powers. |
| **Spending by Organisation** | Total and average cost per launch. | NASA spends the most; SpaceX and ISRO are cost‑efficient. |
| **Launches Over Time** | Yearly and monthly trends. | Peaks in 1960s–70s and resurgence after 2010. |
| **Cold War Space Race** | USA vs USSR comparison. | USSR led ~76% of launches before 1991. |
| **Failure Percentage Over Time** | Reliability evolution. | Failures dropped from 60% to <10%. |
| **Launch Leaders by Year** | Identify yearly dominant organisations. | RVSN USSR ruled 1970s–80s; CASC leads since 2018. |

---

## 💡 Conclusions
- The **USSR** led global launches during the Cold War, while the **USA** focused on high‑value missions.  
- **China’s CASC** emerged as the modern leader after 2018.  
- **Mission reliability** improved dramatically, and **launch costs** fell due to reusable technology.  
- Space exploration evolved from **state competition** to **global collaboration and commercialization**.