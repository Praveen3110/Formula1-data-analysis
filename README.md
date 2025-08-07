
# 🏁 Formula 1 Data Analysis with Python

This project analyzes Formula 1 racing data to uncover trends in driver performance, race speeds, and GP wins across seasons. Using pandas, matplotlib, and seaborn, the notebook extracts meaningful insights from real F1 datasets.

## 🚀 Project Overview

Formula 1 is a sport where data plays a huge role in understanding performance. This project analyzes historical F1 data (lap times, race results, etc.) with the aim to:

- Identify the most successful F1 drivers based on race wins
- Track how car performance (via fastest lap speeds) has changed over the years
- Practice advanced data manipulation and visualization skills using Python

## 🧠 Key Learning Outcomes

- Grouping and aggregating data with `pandas`
- Filtering data using conditional logic
- Creating publication-style plots using `seaborn` and `matplotlib`
- Applying real-world data exploration practices
- Using Python functions like `lambda`, `.loc[]`, and `.groupby()` effectively

## 📁 Folder/Notebook Structure

- **Data Cleaning & Setup**:
  - Loaded the dataset using `pandas`
  - Cleaned missing or inconsistent data
  - Selected relevant columns for analysis

- **Driver Performance Analysis**:
  - Filtered data to identify winners (`positionOrder == 1`)
  - Grouped by driver and counted GP wins
  - Created a horizontal bar plot of top GP-winning drivers

- **Speed Trend Analysis (2004 Onwards)**:
  - Filtered seasons from 2004 onward
  - Grouped by GP name and year
  - Calculated mean fastest lap speeds per GP and plotted the trend

## 📊 Visualizations

- **Bar Plot**: Drivers with the highest number of GP wins (sorted descending)
- **Line Plot**: Trends in average fastest lap speeds from 2004 to recent seasons
- Clean and aesthetic plots using:
  - `sns.set_palette("Set3")`
  - `plt.rcParams["figure.figsize"] = (10,6)`

## 📦 Libraries Used

- `pandas` – for data handling
- `numpy` – for numerical operations
- `matplotlib` – for plotting
- `seaborn` – for statistical visualizations
- `openpyxl` – to handle Excel files (if any)

## ⚙️ How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/F1_DataAnalysis.git
cd F1_DataAnalysis
```

2. Install required packages

```bash
pip install pandas matplotlib seaborn openpyxl
```

3. Launch the Jupyter Notebook

```bash
jupyter notebook F1_DataAnalysis.ipynb
```

## ✅ Sample Output

![Sample Plot](https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Simple_bar_chart.svg/800px-Simple_bar_chart.svg.png)

## 📌 Future Work

- Include pit stop data and analyze strategies
- Integrate weather conditions to study impact on lap speeds
- Build predictive models for future GP results

## 👨‍💻 Author

Praveen S R  
*Mechanical Engineering  AI/ML | Data Analytics Enthusiast*

