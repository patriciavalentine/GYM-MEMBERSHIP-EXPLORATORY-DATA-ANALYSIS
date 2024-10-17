# 📊 GYM MEMBERSHIP ANALYSIS

This project details the data analysis conducted on a Gym Membership Dataset, encompassing data cleaning, exploration, calculation of key metrics, and data visualization using `Microsoft Excel`. The [dataset}(https://www.kaggle.com/datasets/ka66ledata/gym-membership-dataset) obtained from `Kaggle`, contains crucial member details such as membership types, personal training status, gym attendance, and gym time, among other details.
> The objective of this analysis was to extract meaningful insights regarding gym usage patterns, demographics, and member behavior, which will assist in decision-making and enhancing gym services.

The EDA involved answering key questions, such as:
- How many members have personal trainers? What percentage of members attend group lessons?
- What is the total gym time for premium members versus standard members?
- Is there a correlation between the number of visits per week and the average time spent in the gym?
- What is the median age of the gym members?
- What is the standard deviation of gym visits per week?
- How many members attend the gym more than three times per week?
  
*...among others!*

## 📂 Project Files
1. [The Raw Dataset](https://github.com/patriciavalentine/GYM-MEMBERSHIP-ANALYSIS/blob/main/Raw%20Gym%20Membership%20Dataset.xlsx)
2. [The Analysed Excel File](https://github.com/patriciavalentine/GYM-MEMBERSHIP-ANALYSIS/blob/main/Gym%20Membership%20Analysis.xlsx)
3. [The Project Report](


## 🧑‍💻 Insights
Using `Excel formulas`, several key metrics were calculated to explore the dataset further and uncover trends in gym usage and membership characteristics.
Below are some of the insights gained.
- 518 members use personal trainers, showing strong demand for personalized fitness guidance.
- Premium and standard members have similar total gym time, with 49,589 hours and 52,011 hours, respectively.
- Both premium and standard members visit the gym about 2.68 times per week, indicating no significant difference in attendance based on membership type.
- The weak correlation (0.0659) between visit frequency and time spent in the gym suggests that frequent visitors don’t necessarily spend more time at the gym.
- 50.25% of members attend group lessons, making them a popular gym feature.
- The median age of gym members is 30 years, highlighting a predominantly young adult clientele.
- The standard deviation of 1.24 visits per week shows moderate variation in gym attendance frequency.
- 220 members visit the gym more than three times a week, indicating high engagement from a subset of the members.
- 145 members are under 18 years old, showing that the gym also attracts a younger demographic.
- Member Jamey visits the gym 3 times per week, slightly higher than the overall average attendance.
> For a detailed explanation into these insights, view the project report [here](


## 💻 Recommendations
1. The gym could enhance the value of premium memberships by offering more exclusive perks or incentivizing more frequent visits through loyalty programs or personalized experiences.
2. The gym should consider expanding the variety and schedule of group lessons to accommodate demand and attract more members to participate.
3. Promoting personal training services or offering discounted packages for new members could increase overall gym attendance and boost engagement.
4. Since the gym’s membership base skews young, with a median age of 30 and a significant portion of members under 35. The gym should continue tailoring its marketing strategies and services to appeal to this demographic, possibly incorporating more high-intensity workouts and fitness challenges that resonate with younger adults.


### Sample of the Dataset
![Gym Membership Dataset Sample](https://github.com/user-attachments/assets/1807951f-2df5-4d51-b03d-0a914791ebdb)

*The dataset includes key details such as member demographics (id, first_name, gender, birthday, and age), subscription type (abonoment_type), gym attendance metrics (visit_per_week, days_per_week, avg_time_in_gym), and additional features such as personal training and group lesson participation.*

## 🧑‍💻 THE PROJECT WORKFLOW
### 1. Data Cleaning and Preparation
The first step in the project involved thoroughly cleaning and preparing the dataset to ensure the integrity and quality of the analysis.
Key data cleaning tasks included:
1. **Duplicate Handling**: No duplicate entries were found in the dataset, ensuring the uniqueness of each member's data.
2. **Missing Data/Blanks**: There were no unnecessary missing values or blank entries, further reinforcing the dataset's reliability.
3. **Column Formatting**: The following columns were appropriately formatted to match their data types:
- `birthday` was formatted into a date format to accurately reflect members' birthdates.
- `avg_time_check_in` and `avg_time_check_out` were formatted into time formats to properly display gym check-in and check-out times.
- `Age`, `visit_per_week`, and `avg_time_in_gym` were formatted into number formats with zero decimal places for clarity in analysis.
4. **Conditional Formatting**: Applied to highlight:
- Members with premium memberships.
- Members with personal trainers.
5. **Addition of a Necessary Column - `Age Groups`**: An additional column was created to classify members into age groups, with the following categories: *Below 18, 18-25, 26-35, 36-45, Above 45*.

### Visualization:

> Visual insights are created using a range of Excel charts:

Bar and Column Charts visualize member distribution by gender, subscription type, and age group.

Pie Charts display the proportions of members attending group lessons or opting for personal training.

Line Charts show trends in check-in/check-out times across different days, while Stacked Column Charts compare attendance patterns across membership types.

Heatmaps generated through Conditional Formatting highlight areas like high-frequency gym visits or the most popular gym times.

An interactive Excel dashboard is developed using slicers, filters, and linked Pivot Tables/Charts to provide a dynamic reporting tool for stakeholders.


### Conclusion
This project leverages Excel’s advanced functionalities to transform raw membership data into a comprehensive analysis of gym usage, member behavior, and operational efficiency

The analysis of the Gym Membership Dataset provided key insights that showed how the gym is attracting a young and engaged audience, with half of the members participating in group lessons and a large portion visiting regularly.

The findings are visualized in an interactive dashboard, enabling data-driven decision-making to enhance the gym’s services and member engagement strategies.
