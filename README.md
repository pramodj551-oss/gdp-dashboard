# 🌎 GDP Dashboard

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-red?logo=streamlit)
![Plotly](https://img.shields.io/badge/Charts-Plotly-purple)
![License](https://img.shields.io/badge/License-Apache%202.0-green)

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gdp-dashboard-template.streamlit.app/)

An interactive Streamlit dashboard to visualize and compare **GDP data across countries** worldwide — with time-series trends, country comparisons, and growth rate analysis.

---

## ✨ Features

| Feature | Detail |
|--------|--------|
| 🌍 Country Comparison | Compare GDP of multiple countries side-by-side |
| 📈 Time-Series Analysis | Track GDP trends over decades |
| 📊 Interactive Charts | Plotly-powered — zoom, hover, filter |
| 🔍 Country Filter | Select any country from the sidebar |
| 💡 Growth Rate View | See year-on-year GDP growth percentages |

---

## 📁 Project Structure

```
gdp-dashboard/
├── streamlit_app.py      # Main Streamlit application
├── requirements.txt      # Dependencies
├── data/                 # GDP dataset (CSV)
├── .devcontainer/        # GitHub Codespaces config
├── .github/              # GitHub Actions workflows
├── .gitignore
├── LICENSE               # Apache 2.0
└── README.md
```

---

## ⚙️ Prerequisites

- Python 3.10+
- pip

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/pramodj551-oss/gdp-dashboard.git
cd gdp-dashboard
```

### 2. Create Virtual Environment

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
streamlit run streamlit_app.py
```

Open browser → `http://localhost:8501`

---

## 🌐 Live Demo

👉 **[Open in Streamlit Cloud](https://gdp-dashboard-template.streamlit.app/)**

---

## 📊 About the Data

The dashboard uses **World Bank GDP data** (`data/` folder) containing:
- GDP (current US$) per country
- Annual data across multiple decades
- 190+ countries covered

---

## 🐛 Troubleshooting

| Problem | Solution |
|---------|----------|
| Streamlit not found | Run `pip install streamlit` |
| Port already in use | Run `streamlit run streamlit_app.py --server.port 8502` |
| Data not loading | Check `data/` folder has the CSV file |

---

## 🚧 Planned Improvements

- [ ] Add GDP per capita view
- [ ] Add choropleth world map
- [ ] Add download button for filtered data
- [ ] Deploy on Streamlit Cloud with auto-refresh

---

## 🤝 Contributing

1. Fork → `git checkout -b feature/add-gdp-map`
2. Commit → `git commit -m 'Add choropleth world map'`
3. Push → `git push origin feature/add-gdp-map`
4. Open a Pull Request

---

## 📝 License

This project is licensed under the **Apache 2.0 License** — see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

**Pramod** · IIT Patna Applied AI & ML Program  
GitHub: [@pramodj551-oss](https://github.com/pramodj551-oss)

> ⭐ Star this repo if it helped you!
