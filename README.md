# 911 Calls Data Analysis Capstone Project

A comprehensive data science project analyzing 911 emergency call data from Montgomery County, Pennsylvania. This project demonstrates exploratory data analysis, time series analysis, and data visualization techniques to uncover patterns and trends in emergency response data.

## 📊 Project Overview

This capstone project performs an in-depth analysis of emergency call data to identify patterns in call types, temporal trends, and geographic distributions. The analysis provides insights that could be valuable for emergency services planning and resource allocation.

## 🗂️ Dataset Information

- **Source**: [Kaggle - Montgomery County 911 Calls](https://www.kaggle.com/mchirico/montcoalert)
- **Size**: ~100,000+ emergency call records
- **Time Period**: Historical 911 call data from Montgomery County, PA
- **Format**: CSV file (911.csv)

### Data Fields:
- `lat`: Latitude coordinates
- `lng`: Longitude coordinates  
- `desc`: Description of the emergency call
- `zip`: ZIP code
- `title`: Call title/category
- `timeStamp`: Date and time of call (YYYY-MM-DD HH:MM:SS)
- `twp`: Township
- `addr`: Address
- `e`: Dummy variable (always 1)

## 🔧 Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YashBondre04/911-calls-Data-Capstone-.git
   cd 911-calls-Data-Capstone-
   ```

2. **Install required dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open the main analysis file:**
   - Navigate to `911_Calls_Data_Capstone_Project.ipynb`

## 📈 Key Features & Analysis

### 1. Data Preprocessing
- Data cleaning and missing value handling
- Feature engineering (extracting time components)
- Data type conversions

### 2. Exploratory Data Analysis
- Call frequency analysis by category (EMS, Fire, Traffic)
- Geographic distribution analysis
- Statistical summaries and data profiling

### 3. Temporal Analysis
- **Hourly patterns**: Peak call times throughout the day
- **Daily patterns**: Day-of-week call distributions
- **Monthly trends**: Seasonal variations in call volume
- **Time series visualization**: Call volume over time

### 4. Emergency Call Categories
- **EMS (Emergency Medical Services)**: Medical emergencies
- **Fire**: Fire-related incidents
- **Traffic**: Traffic accidents and incidents

### 5. Advanced Visualizations
- Count plots for categorical analysis
- Time series line plots
- Heatmaps for temporal pattern analysis
- Cluster maps for correlation analysis
- Geographic distribution plots

## 📊 Sample Visualizations

The project generates various insightful visualizations:
- Emergency call frequency by type
- Hourly call patterns showing peak emergency times
- Day-of-week analysis revealing weekly patterns
- Monthly trends highlighting seasonal variations
- Heatmaps showing call patterns by day and hour
- Geographic distribution maps

## 📋 Project Structure

```
911-calls-Data-Capstone-/
│
├── README.md                               # Project documentation
├── 911.csv                                # Emergency calls dataset
└── 911_Calls_Data_Capstone_Project.ipynb # Main analysis notebook
```

## 🔍 Key Insights

The analysis reveals several important patterns:
- **Peak Hours**: Emergency calls peak during certain hours of the day
- **Day Patterns**: Different call types show varying patterns throughout the week
- **Seasonal Trends**: Call volumes vary by month and season
- **Category Distribution**: EMS calls dominate the dataset, followed by Traffic and Fire
- **Geographic Clusters**: Certain areas show higher call concentrations

## 🎯 Usage

1. **Data Loading**: The notebook loads and inspects the 911 calls dataset
2. **Data Cleaning**: Handles missing values and prepares data for analysis
3. **Feature Engineering**: Creates time-based features (hour, day, month)
4. **Visualization**: Generates comprehensive visualizations and insights
5. **Analysis**: Provides statistical analysis and pattern identification

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Fork the repository
- Create a feature branch
- Make your changes
- Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Dataset provided by [Kaggle](https://www.kaggle.com/mchirico/montcoalert)
- Montgomery County, PA for the emergency services data
- Data science community for inspiration and best practices

---

**Note**: This project is for educational and analytical purposes. The insights should be interpreted carefully and validated with domain experts before making operational decisions.
