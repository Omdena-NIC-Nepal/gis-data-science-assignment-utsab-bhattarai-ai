# Climate Data Analysis for Nepal

## Objective

This project analyzes climate trends in Nepal using GIS data, focusing on temperature and precipitation variations from 2020 to 2050. The analysis includes data processing, visualization, and exploratory data analysis (EDA) to assess climate patterns and impacts.

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Install Dependencies

Ensure Python is installed, then install required libraries:

```bash
pip install geopandas rasterio matplotlib seaborn pandas numpy
```

## Data Sources & Processing

Data is sourced from [Desmondonam/Nepal_Climate_change](https://github.com/Desmondonam/Nepal_Climate_change):

- **Vector Data:** Administrative boundaries, rivers, glaciers.
- **Raster Data:** Temperature and precipitation projections for 2020 and 2050.

Processing:
- **Geospatial Data:** Read with `geopandas`.
- **Raster Data:** Processed with `rasterio`.

## Data Visualization

### 1. Administrative Map
- Visualizes Nepal’s geographical features.

### 2. Climate Trends (2020-2050)
- Heatmaps highlight temperature and precipitation changes.

## Exploratory Data Analysis (EDA)

- **Key Statistics:** Min, max, mean, and median for climate variables.
- **Trend Analysis:** Statistical summaries and visualizations.

## Key Findings

- **Temperature Increase:** Significant warming from 2020 to 2050.
- **Precipitation Variation:** Shifting rainfall patterns across regions.
- **Geospatial Insights:** Maps aid climate adaptation planning.

## Running the Analysis

Run the script:

```bash
python climate_analysis.py
```

For Jupyter Notebook:
- Open `.ipynb` and execute the cells sequentially.

## Conclusion

This analysis provides insights into Nepal’s climate changes, supporting mitigation and adaptation strategies. Future improvements may integrate more detailed climate models and socio-economic factors.

---