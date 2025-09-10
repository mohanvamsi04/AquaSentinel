# 💧 AquaSentinel  
A lightweight **data visualization dashboard** for monitoring and analyzing datasets.  
Provides 📊 bar charts, 📈 line charts, and 📑 data views to help users track and understand metrics efficiently.  

👉 **[Live Demo](https://mohanvamsi04.github.io/AquaSentinel/)**  

---

## ✨ Features
- 📊 Interactive bar charts for comparing metrics  
- 📈 Line charts for time-series trend analysis  
- 📑 Data views for raw dataset inspection  
- 🖼️ Simple and clean web-based interface  
- 🌐 Deployable on GitHub Pages for instant access  

---

## 🛠 Tech Stack
- **Frontend:** HTML, CSS  
- **Visualization:** JavaScript (Chart.js / custom scripts)  
- **Cloud Integration:** AWS (for sensor data JSON feeds)  
- **Deployment:** GitHub Pages  

---

## 📡 Note on Live Data

- Currently, the charts may appear empty because they are designed to display live data from IoT sensors.

- Sensor data → sent to AWS Cloud

- AWS generates JSON feeds

- AquaSentinel fetches these JSON feeds to update the charts in real time

- Since sensor data is not being transmitted right now, the charts won’t populate.
- This ensures the system only works with real-world sensor inputs, not static mock data.

--- 

## ⚡ Installation / Usage
```bash
# Clone the repository
git clone https://github.com/mohanvamsi04/AquaSentinel.git
cd AquaSentinel
