# 📊 GYM MEMBERSHIP ANALYSIS

This project analyzes a Gym Membership Dataset using `Microsoft Excel` to provide actionable insights into member behaviors and usage patterns within the gym.

The EDA involved answering key questions, such as:
- What is the average gym attendance per week for different membership types?
- What percentage of members attend group lessons, and what are their favorite group lessons?
- How does personal training affect gym attendance?
- What are the peak times for gym usage (check-in/check-out times)?
- What is the gender distribution of members across different membership types?


### Source of Data:
- [Kaggle](https://www.kaggle.com/datasets/ka66ledata/gym-membership-dataset)

### Sample of the Dataset:
![Gym Membership Dataset Sample](https://github.com/user-attachments/assets/1807951f-2df5-4d51-b03d-0a914791ebdb)

*The dataset includes key details such as member demographics (id, first_name, gender, birthday, and age), subscription type (abonoment_type), gym attendance metrics (visit_per_week, days_per_week, avg_time_in_gym), and additional features such as personal training and group lesson participation.*

## 🧑‍💻 THE PROJECT WORKFLOW:
### 1. Data Cleaning:

The dataset undergoes extensive data cleaning, including the removal of duplicates, handling of missing values, and correction of data types (e.g., ensuring dates are formatted correctly, and transforming personal_training into a binary format). Outlier detection and correction are performed to ensure data quality, and missing values are imputed using statistical methods like mean, median, or mode depending on the data type.

### 2. Data Transformation:

Additional columns are calculated to enhance the dataset, such as age derived from birthdate using Excel's DATEDIF function. Weekly attendance is calculated based on the number of visits per day. Age is categorized into meaningful groups (e.g., 18-25, 26-35) for deeper demographic analysis, and time values (e.g., check-in/check-out times) are formatted for readability.

### 3. Data Analysis:

> Using a variety of Excel functions and tools, in-depth analysis is conducted:

Pivot Tables summarize key metrics like average gym time by gender, or the distribution of members across different membership types.

Statistical Functions (e.g., COUNTIF, SUMIF, AVERAGEIF) explore relationships between variables such as the impact of personal training on attendance frequency or the favorite group lessons among different member segments.

Trend and Correlation Analysis is performed using Excel's FORECAST and CORREL functions to predict future gym attendance and explore relationships between variables like visit frequency and time spent in the gym.

### 4. Visualization:

> Visual insights are created using a range of Excel charts:

Bar and Column Charts visualize member distribution by gender, subscription type, and age group.

Pie Charts display the proportions of members attending group lessons or opting for personal training.

Line Charts show trends in check-in/check-out times across different days, while Stacked Column Charts compare attendance patterns across membership types.

Heatmaps generated through Conditional Formatting highlight areas like high-frequency gym visits or the most popular gym times.

An interactive Excel dashboard is developed using slicers, filters, and linked Pivot Tables/Charts to provide a dynamic reporting tool for stakeholders.

## Insights and Recommendations:

The project reveals significant insights such as the gym’s peak times, popular group lessons, the impact of personal training on member retention, and membership types that drive higher attendance. Based on the analysis, recommendations are provided, such as optimizing group lesson schedules, increasing staff during peak hours, or tailoring membership offers to attract specific age groups.

## Conclusion:
This project leverages Excel’s advanced functionalities to transform raw membership data into a comprehensive analysis of gym usage, member behavior, and operational efficiency. The findings are visualized in an interactive dashboard, enabling data-driven decision-making to enhance the gym’s services and member engagement strategies.
