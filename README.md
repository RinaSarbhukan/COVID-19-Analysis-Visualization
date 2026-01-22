# COVID-19 Data Analysis

A comprehensive data analysis and visualization project exploring global COVID-19 trends, statistics, and patterns using Python and interactive visualizations.

## 📊 Project Overview

This project provides in-depth analysis of COVID-19 data across different countries and regions, featuring interactive visualizations to explore:
- Total cases, deaths, and recoveries by country and continent
- Testing statistics and patterns
- Time-series analysis of pandemic progression
- Geographic distribution using choropleth maps
- Health condition correlations with COVID-19 mortality

## 🔍 Key Features

- **Interactive Visualizations**: Plotly-based interactive charts and maps
- **Multi-Dataset Analysis**: Combines multiple COVID-19 datasets for comprehensive insights
- **Geographic Analysis**: Choropleth maps showing global pandemic spread over time
- **Statistical Comparisons**: Cross-country and continental comparisons
- **Time-Series Tracking**: Daily progression of cases, deaths, and recoveries
- **Word Cloud Analysis**: Visual representation of co-occurring health conditions

## 📁 Datasets

The analysis uses three primary datasets:

1. **covid.csv** - Country-level aggregated statistics
   - Total Cases, Deaths, and Recoveries
   - Testing data
   - Population-normalized metrics (Tests/1M pop)
   - Continental classifications

2. **covid_grouped.csv** - Time-series data
   - Daily confirmed cases
   - Daily deaths and recoveries
   - New cases tracking
   - WHO region classifications
   - ISO country codes

3. **coviddeath.csv** - Comorbidity data
   - Health conditions associated with COVID-19 deaths
   - Condition groupings

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Plotly** - Interactive visualizations
  - Plotly Express
  - Plotly Graph Objects
  - Plotly Offline
- **Matplotlib** - Static visualizations
- **WordCloud** - Text visualization

## 📈 Visualizations

### Bar Charts
- Top 15 countries by total cases
- Deaths and recoveries comparison
- Testing statistics by country
- Horizontal bar charts by continent

### Scatter Plots
- Cases vs Deaths correlation
- Tests vs Cases relationship
- Continental distribution
- Logarithmic scale comparisons

### Choropleth Maps
- Animated global confirmed cases progression
- Deaths distribution over time
- Recoveries by country with temporal animation

### Line Charts
- US-specific case trends
- Daily new cases
- Recovery and death trends over time

### Word Clouds
- Co-occurring health conditions
- Condition groups analysis

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib plotly wordcloud
```

### Installation

1. Clone this repository
```bash
git clone https://github.com/yourusername/covid-data-analysis.git
cd covid-data-analysis
```

2. Install required packages
```bash
pip install -r requirements.txt
```

3. Update dataset paths in the notebook to match your local directory structure

### Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook Covid_Data_Analysis.ipynb
```

2. Run cells sequentially to generate visualizations

3. Interactive plots will appear in your browser

## 📊 Analysis Highlights

- **Geographic Trends**: Identify hardest-hit regions and countries
- **Testing Efficiency**: Correlation between testing rates and case detection
- **Temporal Patterns**: Track pandemic waves and peaks
- **Recovery Rates**: Compare recovery statistics across nations
- **Health Correlations**: Understand pre-existing conditions impact

## 📝 Key Insights

The notebook explores:
- Which countries had the highest case counts
- Testing capacity vs. infection rates
- Recovery patterns across different regions
- Time-based progression of the pandemic
- Impact of various health conditions on COVID-19 mortality

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Rina Sarbhukan**

## 🙏 Acknowledgments

- Data sources: [Kaggle]
- Plotly for interactive visualization capabilities
- The data science community for inspiration and tools

## 📞 Contact

For questions or feedback, please open an issue in this repository.

---

**Note**: This analysis is for educational and informational purposes. Please refer to official health organizations for medical guidance and latest COVID-19 information.
