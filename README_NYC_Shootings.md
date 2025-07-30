
# NYC Shootings Cluster Analysis 🔫🗺️

## 📊 Project Overview

This project analyzes shooting incidents in New York City using clustering techniques. By applying unsupervised machine learning, it identifies spatial patterns and potential hotspots to aid law enforcement and public safety efforts.

## 📁 Dataset Description

The dataset includes data points related to shooting incidents in NYC, such as:

- **Date and Time**
- **Location (Latitude & Longitude)**
- **Borough**
- **Victim Demographics**
- **Weapon Type**
- **Crime Status**

## ✅ Objectives

- Identify spatial and temporal patterns in NYC shootings.
- Use clustering algorithms to detect high-risk zones.
- Visualize hotspots and trends.
- Provide actionable insights for law enforcement and policy planning.

## 🛠️ Tools & Technologies

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn, Plotly** – Data visualization
- **Scikit-learn** – Clustering algorithms
- **Folium** – Interactive map visualizations
- **Jupyter Notebook** – Development environment

## 🧩 Installation

To set up the project locally, follow these steps:

1. **Clone the repository** (or download the `.ipynb` file):
   ```bash
   git clone https://github.com/your-username/nyc-shootings-cluster-analysis.git
   cd nyc-shootings-cluster-analysis
   ```

2. **Create a virtual environment (optional but recommended)**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

   If there's no `requirements.txt`, install manually:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn folium jupyter
   ```

4. **Run the notebook**:
   ```bash
   jupyter notebook
   ```

## 📌 Key Steps

1. **Data Preprocessing**
   - Handle missing values
   - Normalize location data

2. **Clustering Analysis**
   - Apply KMeans and DBSCAN algorithms
   - Evaluate clustering performance using silhouette scores

3. **Visualization**
   - Heatmaps and cluster overlays using Folium
   - Temporal plots to show trends

4. **Insights**
   - Identify boroughs and times with high shooting frequency
   - Detect stable and emerging crime hotspots

## 📈 Visualization Highlights

- Interactive cluster maps with Folium
- Heatmaps for incident density
- Temporal line charts by borough and victim demographics

## 💡 Conclusion

The clustering analysis reveals valuable spatial trends in NYC shooting incidents. These insights can help in better allocation of policing resources and improving urban safety strategies.

## 📄 Recommendations

- Deploy predictive monitoring tools in detected hotspots.
- Conduct deeper analysis using demographic and socioeconomic overlays.
- Promote community awareness and targeted safety initiatives in high-risk zones.
