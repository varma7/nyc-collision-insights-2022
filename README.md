# nyc-collision-insights-2022
# 🚦 NYC Traffic Collisions Analysis (2022)

This project explores traffic collision data in New York City using Google BigQuery and visualizes key insights with Python in Google Colab. The aim is to identify high-risk factors, time patterns, and geographic hotspots for accidents using publicly available data.

---

## 📌 Project Highlights

- ✅ Queried over 100,000 collision records from BigQuery (2022 data)
- ✅ Cleaned and transformed data using Pandas
- ✅ Created impactful visualizations with Seaborn, Matplotlib, and Folium
- ✅ Built an interactive NYC map with clickable accident markers
- ✅ Exported and structured the project for sharing on GitHub

---

## 📊 Key Visualizations

- 🔹 **Top 10 Contributing Factors** to traffic accidents
- 🔹 **Collisions by Hour of Day**
- 🔹 **Accidents by Borough**
- 🔹 **Most Dangerous Streets**
- 🔹 **Interactive Map** of NYC accidents with detailed popups

<p align="center">
  <img src="images/top_contributing_factors.png" width="500"/>
  <img src="images/collisions_by_hour.png" width="500"/>
  <img src="images/borough_collision.png" width="500"/>
  <img src="images/top_dangerous_streets.png" width="500"/>
</p>

---
## 🗺️ Interactive Map

Explore an interactive map of 1,000 randomly sampled accidents in NYC. Each marker shows:

- Borough
- Street
- Contributing factor
- Vehicle type
- Number of injured/killed

👉 Open the map here: [nyc_collisions_map.html](nyc_collisions_map.html)

---

## 🛠️ Tools Used

| Tool           | Purpose                                  |
|----------------|------------------------------------------|
| **BigQuery**   | Querying NYC collision dataset (SQL)     |
| **Google Colab** | Python environment for analysis         |
| **Pandas**     | Data cleaning and manipulation           |
| **Seaborn & Matplotlib** | Data visualizations            |
| **Folium**     | Interactive map with location clustering |
| **GitHub**     | Project documentation and portfolio      |

---

## 📂 Project Structure
Traffic-Collision-Analysis/ ├── README.md ├── nyc_collision_analysis.ipynb ├── nyc_collisions_2022.csv ├── nyc_collisions_map.html ├── images/ │ ├── top_contributing_factors.png │ ├── collisions_by_hour.png │ ├── borough_collisions.png │ └── top_dangerous_streets.png
---

## 📎 Dataset Source

- **NYC Open Data - Motor Vehicle Collisions**  
  Dataset used from BigQuery:  
  `bigquery-public-data.new_york_mv_collisions.nypd_mv_collisions`

---

## 👨‍💻 Author

**Ravi Varma Pakalapati**  
📧 pakalapatiravivarma.99@gmail.com
🌐 [LinkedIn](https://www.linkedin.com/in/ravi-varma-pakalapati/)

---

## 📢 License

This project is for educational and portfolio use. Data used is publicly available from NYC Open Data.

