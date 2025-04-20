# FUTURE_DS_03
# 🚗 Road Accident Data Analysis

This project performs an exploratory data analysis (EDA) on road accident data to uncover patterns and trends that can inform road safety policies and awareness.

## 📊 Objectives

- Clean and prepare road accident data for analysis.
- Explore temporal and environmental patterns contributing to accidents.
- Visualize insights by time of day, road type, vehicle type, and more.
- Identify possible factors associated with higher accident rates or severities.
- 
## 📁 Data source
The data is secondary data saved in an excel file.
The dataset is loaded from an Excel file:
```python
df = pd.read_excel("Road Accident Data.xlsx")
```
## 🛠️ Tools used

- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Plotly for interactive plots
- Jupyter Notebook as the development environment

## Data cleaning and Preparation
The steps for data preparation involves:
- Dropping duplicates,
- covertind data to the right format.
- checking for percentage of ,missing values.
- Dropping column with the highest percentage of missing values.
- Dropping missing values.
-Feature engineering to extract Hour, Month, and Year for time-based analysis

## Exploratory data analysis (EDA)
The exploration and discovering of patterns through answering the following questions:
- Which hours of the day does accidents mostly occur?
- Is there a change in the number of accident from the previous year?
- Which road type has the highest number of occuring accidents?
- which days of the week does accidents mostly occur?
- Which vehicle type has the highest record of accidents?

## Insights
- Most accidents occur during the rush hour.In the morning  around 0080 hrs and in the evening around 1700hrs.
- Urban areas have high record of accidents compared to the the rural areas.
- Single carriageway has the highest count of accidents compared to other road type and also high count of  casualties types.
- Car has the highest count of accidents.
- The number of accidents over the months has reduced compared to the previous year.

## Recommendations.
- Widen roads or upgrade critical sections to dual carriageways.
- Add median barriers where road widening is not feasible.
- Enforce overtaking rules and install warning signs at blind spots or curves.
- Run targeted awareness campaigns on defensive driving and seatbelt use.
- Incentivize the use of driver assistance systems (like automatic braking or lane assist) in vehicles.
- Consider periodic re-certification of driving skills for private car drivers.
- Continue or scale up existing road safety programs and enforcement strategies.
- Investigate which specific interventions contributed most to the decline.
- Don’t relax safety efforts—sustain or improve ongoing initiatives.
- Educate drivers that most accidents happen in normal conditions, not just in bad weather.
- Reinforce safe driving behavior at all times, not just during rain or fog.
- Encourage use of speed limiters and consistent road signage regardless of weather.

