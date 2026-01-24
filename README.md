# AquaSentinel

AquaSentinel is an interactive web-based dashboard designed to monitor and visualize real-time IoT sensor data for water analytics. Featuring dynamic charts and tables, it provides an intuitive way to track metrics, analyze time-series trends, and work with raw datasets.

### ✨ Features
- 📊 **Interactive bar charts** for comparing metrics
- 📈 **Line charts** for time-series trend analysis
- 📑 Built-in **data views** for raw dataset inspection
- 🖼️ **Simple and clean** web-based interface
- 🌐 **Deployable on GitHub Pages** for instant access

### 🛠 Tech Stack
- **Frontend:** HTML, CSS
- **Visualization:** JavaScript (Chart.js/custom scripts)
- **Cloud Integration:** AWS (for fetching IoT sensor JSON feeds)
- **Deployment:** GitHub Pages

### 📡 Note on Live Data
Currently, the charts may appear empty because they rely on live data directly from IoT sensors. Here's how the system operates:

1. Sensor data → **sent to AWS Cloud**
2. AWS generates **JSON feeds**
3. AquaSentinel **fetches these JSON feeds** to update the charts in real-time

Since live sensor data is not active at the moment, the charts will remain unpopulated. This ensures the system only works with real-world sensor inputs and does not rely on static mock data.

### 🚀 Getting Started
#### Prerequisites
- Web browser
- Optional: AWS account for hosting and JSON feed testing

#### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mohanvamsi04/AquaSentinel.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AquaSentinel
   ```
3. Open `index.html` in your favorite browser to view the dashboard.

#### Deployment on GitHub Pages
1. Fork the repository to your account.
2. Go to the repository's Settings.
3. Enable GitHub Pages under the Pages section by selecting the branch containing the `index.html`.

### 📜 License
This project is licensed under the [MIT License](LICENSE).

### 🌟 Acknowledgments
- Thanks to Chart.js for data visualization support.
- AWS for seamless JSON feed integration.

### 💬 Contact
For feedback or inquiries, feel free to reach out via [GitHub Issues](https://github.com/mohanvamsi04/AquaSentinel/issues).
