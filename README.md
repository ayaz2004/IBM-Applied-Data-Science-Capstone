# IBM Applied Data Science Capstone - SpaceX Analysis

## 📋 Project Overview

This capstone project analyzes SpaceX launch data to predict the success of Falcon 9 first stage landings. The ability to reuse the first stage makes SpaceX launches more cost-effective compared to other providers. By predicting landing success, we can estimate launch costs and provide competitive insights for companies bidding against SpaceX.

## 🎯 Objectives

- Collect SpaceX launch data using APIs and web scraping
- Wrangle and prepare data for analysis
- Perform exploratory data analysis (EDA) using SQL and data visualization
- Analyze launch site locations and proximity factors
- Build machine learning models to predict landing success
- Create an interactive dashboard for data exploration

## 📁 Project Structure

```
├── jupyter-labs-spacex-data-collection-api.ipynb      # Data collection via SpaceX API
├── jupyter-labs-webscraping.ipynb                      # Web scraping Falcon 9 launch data
├── labs-jupyter-spacex-Data wrangling.ipynb           # Data cleaning and preparation
├── jupyter-labs-eda-sql-coursera_sqllite.ipynb        # SQL-based exploratory analysis
├── jupyter-labs-eda-dataviz.ipynb                     # Visual exploratory data analysis
├── lab_jupyter_launch_site_location.ipynb             # Geographic analysis of launch sites
├── SpaceX_Machine_Learning_Prediction_Part_5.jupyterlite.ipynb  # ML models
├── spacex_dash_app.py                                  # Interactive Dash dashboard
├── spacex_launch_geo.csv                               # Launch site geographic data
└── README.md                                           # Project documentation
```

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Pandas & NumPy**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **Folium**: Interactive map visualization
- **Plotly Dash**: Interactive web dashboard
- **Scikit-learn**: Machine learning models
- **SQL (SQLite)**: Database queries and analysis
- **BeautifulSoup**: Web scraping
- **Jupyter Notebook**: Development environment

## 📊 Methodology

### 1. Data Collection
- **API Collection**: Retrieved launch data from SpaceX API
- **Web Scraping**: Extracted historical Falcon 9 launch records from Wikipedia

### 2. Data Wrangling
- Cleaned and processed raw data
- Handled missing values
- Created derived features
- Standardized data formats

### 3. Exploratory Data Analysis
- **SQL Analysis**: Queried data to extract insights on launch outcomes, sites, and payloads
- **Data Visualization**: Created charts to identify patterns and trends
- Analyzed success rates by launch site, orbit type, and payload mass

### 4. Geographic Analysis
- Mapped launch site locations
- Analyzed proximity to coastlines, cities, and railways
- Visualized launch success/failure patterns geographically

### 5. Machine Learning
- Built and evaluated multiple classification models
- Performed hyperparameter tuning
- Compared model performance metrics
- Selected best model for landing prediction

### 6. Interactive Dashboard
- Created Dash web application for data exploration
- Interactive filters for launch sites and payload ranges
- Real-time visualization updates

## 🚀 Key Findings

*Add your key findings and insights from the analysis here*

## 📈 Results

*Add your model performance metrics and conclusions here*

## 🔧 Installation & Setup

### Prerequisites
```bash
Python 3.7+
pip
```

### Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn plotly dash folium scikit-learn beautifulsoup4 requests sqlalchemy
```

### Run Jupyter Notebooks
```bash
jupyter notebook
```

### Run Dashboard Application
```bash
python spacex_dash_app.py
```

Then navigate to `http://127.0.0.1:8050` in your web browser.

## 💡 Usage

1. Start with the data collection notebooks to understand data sources
2. Follow the data wrangling notebook to see data preparation steps
3. Explore the EDA notebooks for insights and patterns
4. Review the geographic analysis for location-based insights
5. Examine the machine learning notebook for predictive modeling
6. Launch the Dash app for interactive exploration

## 🤝 Contributing

This is a capstone project for the IBM Applied Data Science Professional Certificate. Feedback and suggestions are welcome!

## 📝 License

This project is part of the IBM Data Science Professional Certificate program.

## 👤 Author

*Add your name and contact information here*

## 🙏 Acknowledgments

- IBM Skills Network for the project structure and guidance
- SpaceX for making their data publicly available
- Coursera for hosting the IBM Data Science Professional Certificate

---

**Course**: IBM Applied Data Science Capstone  
**Platform**: Coursera  
**Date**: January 2026
