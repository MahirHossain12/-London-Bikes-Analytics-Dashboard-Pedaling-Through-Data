# 🚴‍♀️ London Bikes Analytics Dashboard | Pedaling Through Data

[![Python](https://img.shields.io/badge/python-v3.10+-blue.svg)](https://www.python.org/downloads/)
[![Pandas](https://img.shields.io/badge/pandas-1.5.0+-green.svg)](https://pandas.pydata.org/)
[![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange.svg)](https://prod-apsoutheast-b.online.tableau.com/t/mahihossain114-e534c1701f/views/finallondon/Dashboard).
[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF.svg)](https://www.kaggle.com/datasets/kalacheva/london-bike-share-usage-dataset)

> **Transforming London's bike-sharing data into actionable insights through interactive visualizations**

An end-to-end data analytics project that takes raw London bike-sharing data from Kaggle and transforms it into a stunning, interactive Tableau dashboard. Discover weather patterns, seasonal trends, and usage behaviors that drive London's cycling culture!

## 🎯 Project Overview

This project demonstrates a complete data analytics pipeline:
- **Data Acquisition**: Automated download from Kaggle API
- **Data Processing**: Comprehensive cleaning and transformation with Python/Pandas
- **Data Visualization**: Interactive dashboard creation in Tableau
- **Insights Generation**: Meaningful patterns and trends analysis

## 📊 Dashboard Highlights

🌤️ **Weather Impact Analysis**: How temperature, humidity, and weather conditions affect bike usage  
📅 **Seasonal Trends**: Cycling patterns across spring, summer, autumn, and winter  
⏰ **Time-based Insights**: Peak usage hours and day-of-week variations  
🏖️ **Holiday Effects**: Weekend vs weekday cycling behavior  
🌧️ **Weather Code Breakdown**: Usage distribution across different weather conditions

## 🛠️ Tech Stack

- **Python 3.10+**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Kaggle API**: Automated dataset acquisition
- **Tableau**: Interactive dashboard creation
- **Jupyter Notebook**: Development environment

## 📁 Project Structure

```
london-bikes-analytics/
├── london_bikes.ipynb          # Main analysis notebook
├── london_bikes_final.xlsx     # Processed data for Tableau
├── london-bike-sharing-dataset.zip  # Raw data from Kaggle
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies
```

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Kaggle account and API key
- Tableau Desktop/Public

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/MahirHossain12/london-bikes-analytics.git
   cd london-bikes-analytics
   ```

2. **Install dependencies**
   ```bash
   pip install pandas zipfile kaggle openpyxl
   ```

3. **Configure Kaggle API**
   - Download your `kaggle.json` from your Kaggle account
   - Place it in `~/.kaggle/` directory
   - Run: `chmod 600 ~/.kaggle/kaggle.json`

4. **Run the analysis**
   ```bash
   jupyter notebook london_bikes.ipynb
   ```

## 📈 Data Pipeline

### 1. Data Acquisition
- Automated download of London bike-sharing dataset via Kaggle API
- Dataset contains 17,414 hourly records from 2015-2017

### 2. Data Transformation
- **Column renaming**: Meaningful names for better understanding
- **Data type conversions**: Proper formatting for analysis
- **Value mapping**: Converting coded values to readable labels
- **Percentage normalization**: Humidity values standardized
- **Categorical encoding**: Weather codes and seasons mapped to descriptions

### 3. Data Quality
- ✅ No missing values
- ✅ Consistent data types
- ✅ Logical value ranges
- ✅ Proper categorical mappings

## 🔍 Key Insights Discovered

- **Peak Usage**: Summer months show highest bike-sharing activity
- **Weather Dependency**: Clear weather drives 35% more usage than rainy conditions
- **Time Patterns**: Rush hours (8-9 AM, 5-6 PM) show maximum utilization
- **Weekend Effect**: Different usage patterns on weekends vs weekdays

## 📊 Dashboard Features

The Tableau dashboard includes:
- **Interactive filters** for time periods, weather conditions, and seasons
- **Dynamic charts** showing usage trends and patterns
- **Heatmaps** for temporal analysis
- **Weather impact visualizations**
- **Seasonal comparison tools**

## 🎨 Visualization Samples

<img width="1706" height="959" alt="Image" src="https://github.com/user-attachments/assets/f2e6d1ba-886d-468e-8bea-c6429be0bb32" />

<img width="1277" height="722" alt="Image" src="https://github.com/user-attachments/assets/e8978c0c-1b02-483a-94a3-cb96a4e6ae61" />

<img width="1918" height="908" alt="Image" src="https://github.com/user-attachments/assets/64cc0229-e5e2-4383-92e0-3c1a084a9fad" />

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Kaggle**: For providing the London bike-sharing dataset
- **Transport for London**: Original data collection
- **Tableau Community**: Inspiration for visualization techniques

## 📞 Contact

**Your Name** - [mahihossain114@gmail.com](mailto:mahihossain114@gmail.com)

Project Link: [[https://github.com/MahirHossain12/-London-Bikes-Analytics-Dashboard-Pedaling-Through-Data](https://github.com/MahirHossain12/-London-Bikes-Analytics-Dashboard-Pedaling-Through-Data)]

---
⭐ **Star this repo if you found it helpful!** ⭐
