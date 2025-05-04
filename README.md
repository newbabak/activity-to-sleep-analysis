# Activity to Sleep Analysis

This project analyzes Garmin wearable data to explore how daily activity, stress levels, and health metrics influence sleep quality.

## 📊 Project Goals
- Merge and clean Garmin datasets (Activity, Stress, Sleep)
- Engineer features to enhance predictive power
- Visualize relationships between metrics and sleep
- Build ML models (Random Forest, XGBoost with SMOTE)
- Identify key factors that contribute to better sleep

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- SMOTE (imbalanced-learn)

## 🔍 Key Insights
- Increased sleep duration and earlier bedtimes improve sleep quality
- Daily physical activity and elevated heart rate are positively associated with better sleep
- While stress isn't fully controllable, healthy habits can help mitigate its impact

## 📁 Project Structure


# Activity to Sleep Analysis

This project analyzes Garmin data from Activities.csv, Sleep.csv, and Stress.csv to explore potential relationships between daily activity levels and sleep quality using the `GarminAnalyseApril2025.ipynb` Jupyter Notebook.

## Project Files
* `GarminAnalyseApril2025.ipynb`: The main Jupyter Notebook for analysis.
* `Activities.csv`: Exported activity data.
* `Sleep.csv`: Exported sleep data.
* `Stress.csv`: Exported stress data.
* `merged_cleaned_data_final.csv`: Processed data output.

## How to Run
1.  Ensure you have Python, pandas, and Jupyter Notebook installed.
2.  Clone or download this repository.
3.  Open `GarminAnalyseApril2025.ipynb` using Jupyter Notebook or Jupyter Lab.
4.  Run the cells sequentially.
