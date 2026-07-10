# 🌍 Earthquake EDA Analysis (2024-2025)

An Exploratory Data Analysis (EDA) project on global seismic activity from 2024 to 2025, using real-world earthquake data. This project applies advanced geospatial, statistical, and interactive visualizations to uncover patterns in earthquake frequency, magnitude, depth, and geographic distribution.

---

## 📊 Dataset

| Detail | Info |
|--------|------|
| **File** | `earthquake_dataset_2024_2025.csv` |
| **Size** | ~11MB |
| **Source** | Real-world seismic records (2024–2025) |
| **Key Columns** | `time`, `latitude`, `longitude`, `depth`, `mag`, `magType`, `place` |

---

## 🔍 Analysis Performed

### 1. 🗺️ Map Visualizations
- **Choropleth Map** - Compares average earthquake magnitude and frequency across countries
- **Bubble Map** - Global distribution of seismic events plotted on OpenStreetMap, highlighting the "Ring of Fire"
- **Density Heatmap** - Weighted by magnitude to show earthquake concentration hotspots

### 2. 📈 Aggregation Visualizations
- **Histogram + KDE** - Distribution of earthquake magnitudes; illustrates the **Gutenberg-Richter Law** (exponential drop in frequency as magnitude increases)
- **Box Plot** - Compares top 5 magnitude measurement types (`mb`, `ml`, `mww`, etc.) used in seismology

### 3. ⚡ Interactive Visualizations
- **3D Bubble Plot** - Depth vs. Magnitude by Continent; allows comparison of seismic structure across tectonic regions
- **Time-Series with Range Slider** - Full chronological view of seismic events with scrubbing, colored by depth

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Folium, Reverse Geocoder, Pycountry Convert
- **Environment:** Google Colab

---

## 📁 Files

| File | Description |
|------|-------------|
| `Earthquake_EDA_Analysis.ipynb` | Main Jupyter notebook with full analysis and visualizations |
| `earthquake_dataset_2024_2025.csv` | Earthquake dataset (2024–2025) |

---

## ▶️ How to Run

1. Clone this repo or download the files
2. Open `Earthquake_EDA_Analysis.ipynb` in **Google Colab** or **Jupyter Notebook**
3. Make sure the dataset CSV is in the same folder (or update the file path in Cell 3)
4. Install dependencies if needed:
```bash
pip install folium plotly reverse_geocoder pycountry_convert seaborn
```
5. Run all cells

---

## 💡 Key Findings
- Earthquake activity is heavily concentrated along the **Ring of Fire** (Pacific coast regions)
- The majority of seismic events fall below **magnitude 3.0**, consistent with the Gutenberg-Richter Law
- Deeper earthquakes tend to occur in **Asia and South America**, while shallow quakes dominate **North America and Europe**
- Magnitude measurement methods vary significantly by region and event type

---


