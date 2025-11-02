
# Spotify Listening Insights Dashboard 🎧  
**An Advanced Power BI Project using DAX, Interactive Filters, and Dynamic Visuals**

---

## 📘 Project Overview  
This project focuses on analyzing **Spotify Listening Data** to identify user listening patterns, popular tracks, albums, and artists over time.  
The dashboard provides a complete, interactive view of user engagement and listening trends using advanced Power BI features such as **DAX calculations, grid view, drill-through functionality, and quadrant-based scatter plot analysis**.

---

## 🪜 Steps in Project  
✔️ Requirement Gathering / Business Understanding  
✔️ Data Walkthrough  
✔️ Data Connection (Power BI → Excel Dataset)  
✔️ Data Cleaning / Quality Check  
✔️ Data Modeling (Relationships, Hierarchies, Measures)  
✔️ Data Processing  
✔️ DAX Calculations (custom measures for metrics and trends)  
✔️ Dashboard Layout Design  
✔️ Chart Development and Formatting  
✔️ Dashboard / Report Development  
✔️ Insights Generation  

---

## 🎯 Business Requirements  

### 🎵 Albums Analysis  
- **Total Albums Played Over Time:** Track how album listening trends change across years.  
- **Number of Albums Listened by Year:** Identify annual listening habits (minimum and maximum albums per year).  
- **Albums Played on Weekday & Weekend:** Compare listening patterns on weekdays vs weekends.  
- **Top 5 Albums:** Identify the most played albums based on listening frequency.  

---

### 🎤 Artists Analysis  
- **Total Artists Played Over Time:** Visualize how artist engagement trends evolved across years.  
- **Number of Artists Listened by Year:** Explore artist diversity and user listening habits annually.  
- **Artists Played on Weekday & Weekend:** Study listening pattern differences by day type.  
- **Top 5 Artists:** Identify the most frequently listened artists.  

---

### 🎶 Tracks Analysis  
- **Total Tracks Played Over Time:** Understand track-level listening trends over years.  
- **Number of Tracks Listened by Year:** Explore how listening volume and diversity change each year.  
- **Tracks Played on Weekday & Weekend:** Compare listening frequency across weekdays and weekends.  
- **Top 5 Tracks:** Identify the most popular and most replayed songs.  

---

### ⏱️ Listening Patterns  
- **Listening Hours Analysis:** Identify **peak listening times** using a **Heat Map**, visualizing hours and days with color intensity.  
- **Average Listening Time (min) vs Track Frequency:** Implemented a **Scatter Plot with Quadrant Analysis** to classify tracks:  
  - 🎯 **High Frequency & High Listening Time** → Most engaging tracks  
  - 💎 **Low Frequency & High Listening Time** → Niche but impactful tracks  
  - ⚡ **High Frequency & Low Listening Time** → Short, frequently played tracks  
  - 🌙 **Low Frequency & Low Listening Time** → Less popular tracks  

---

### 📋 Details Grid  
An interactive **Grid View** was developed to display key details and support drill-down and export functionality.  

**Key Features:**  
1. **Grid View with Essential Fields:** Album Name, Artist Name, Track Name, and related metrics.  
2. **Drill Through Functionality:** Allows users to navigate from summary reports to detailed records for deeper insights.  
3. **CSV Export:** Users can export drilled-through data based on selected filters.  
4. **Hierarchical Navigation:** Supports drill up / drill down exploration to view different data layers dynamically.  

---

## 🧩 Technical Highlights  
- Data Source: **Spotify Streaming Data (Excel format)**  
- Tools: **Microsoft Power BI Desktop**  
- Key Techniques Used:  
  - Advanced **DAX** (custom measures for counts, rankings, and conditions)  
  - **Drill-through and Filter Interactions**  
  - **Heatmap and Scatter Chart Design**  
  - **Dynamic Grid Visualization using Matrix/Grill function**  
  - **Data Modeling with Relationships & Hierarchies**  

---

## 💡 Insights Generated  
- Users tend to listen more music during evenings and weekends.  
- Certain artists and albums show strong repeat engagement.  
- Scatter plot quadrant revealed high-engagement tracks and less popular ones clearly.  
- Drill-through grid allows easy exploration of detailed track-level statistics.

---

## 📁 Repository Structure  
| File | Description |  
|------|--------------|  
| `Spotify_Dashboard.pbix` | Power BI file containing dashboard |  
| `Spotify_Dataset.xlsx` | Dataset used for analysis |  
| `Spotify_Analysis_Explanation.docx` | Documentation of data fields & logic |  
| `Dashboard_Screenshots/` | Folder containing dashboard visuals |  
| `README.md` | Project documentation |  
| `LICENSE` | MIT License |

---

## 🎓 Learning Journey & Credits  
This project was developed as part of my Power BI learning journey.  
I learned step-by-step using YouTube tutorials (Data Tutorial & similar channels), experimenting with DAX and Power BI features to understand dashboard design, data modeling, and visual storytelling.

**Custom Work Includes:**  
- Implementing all DAX calculations manually.  
- Designing custom visuals (heatmap, scatter, grid).  
- Formatting and layout customization for storytelling.  
- Creating drill-through logic and export options.

---

## 🧠 Author  
👤 **Sunnny Yarramsetti**  
🎓 Master’s in Data Analytics, Technological University of Shannon  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/sunny-yerramesetti/)  

---

## 📝 License  
This project is licensed under the MIT License. See the `LICENSE` file for details.  
📂 GitHub Repo: [https://github.com/sunnnyyarramsetti/Spotify-Listening-Insights-PowerBI](https://github.com/sunnnyyarramsetti/Spotify-Listening-Insights-PowerBI)
