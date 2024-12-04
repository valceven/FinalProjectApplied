# **Traffic Collision Analysis Project**

## **Project Overview**
This project aims to analyze road traffic collision data to uncover relationships and patterns using regression and the Apriori algorithm. By investigating various factors such as casualties, driver demographics, vehicle factors, environmental conditions, and incident details, we aim to gain insights into traffic collision causes and effects.

## **Dataset Details**
- **Source**: [Road Traffic Collision Dataset](https://www.kaggle.com/datasets/salmankhaliq22/road-traffic-collision-dataset?select=vehicle_data.csv)
- **Data Size**: 
  - Total Rows: 5,603 (Filtered and cleaned from 10k initial rows by removing duplicates and irrelevant accident IDs)
- **Main Columns**: 
  - `Number_of_Casualties`
  - `Sex_of_Driver`, `Age_Band_of_Driver`, `Journey_Purpose_of_Driver`
  - `Engine_Capacity_.CC.`, `Model`, `Age_of_Vehicle`, `Speed_limit`
  - `Weather_Conditions`, `Road_Surface_Conditions`, `Junction_Location`
  - `Day_of_Week`, `Time`, `Number_of_Vehicles`

## **Team Roles and Responsibilities**
### **1. Casualties Analysis**
- **Assigned To**: Alec
- **Columns**: `Number_of_Casualties`, `Speed_limit`, `Time`, `Weather_Conditions`, `Road_Surface_Conditions`
- **Tasks**:
  - Analyze the impact of speed limits, weather, and road surface on the number of casualties.
  - Identify time trends related to casualty rates.
- **Visualizations**: Scatter plots, bar charts for weather conditions.

### **2. Driver Demographics**
- **Columns**: `Sex_of_Driver`, `Age_Band_of_Driver`, `Journey_Purpose_of_Driver`
- **Tasks**:
  - Examine differences in accident severity across driver age groups and genders.
  - Investigate correlations between journey purposes and accident occurrences.
  - Analyze trends based on day of the week and time.
- **Visualizations**: Pie chart for gender distribution, bar charts for age groups.

### **3. Vehicle Factors**
- **Columns**: `Engine_Capacity_.CC.`, `Model`, `Age_of_Vehicle`, `Speed_limit`
- **Tasks**:
  - Analyze the effect of engine capacity and vehicle age on accident severity and casualties.
  - Explore accident frequency based on vehicle models.
- **Visualizations**: Heatmap for correlations, scatter plots for engine capacity.

### **4. Environmental Factors**
- **Columns**: `Weather_Conditions`, `Road_Surface_Conditions`, `Junction_Location`
- **Tasks**:
  - Study how weather and road surface conditions influence accident severity.
  - Analyze junction locations and their role in accidents.
- **Visualizations**: Stacked bar chart for weather and severity.

### **5. Incident Details**
- **Columns**: `Day_of_Week`, `Time`, `Number_of_Vehicles`
- **Tasks**:
  - Investigate relationships between time of day and number of vehicles involved.
  - Identify trends based on the day of the week.
- **Visualizations**: Line chart for accident frequency over hours.

## **Workflow**
1. **Data Cleaning**:
   - Handle missing values, duplicates, and inconsistencies.
2. **Individual Analysis**:
   - Team members analyze assigned columns and generate visualizations.
3. **Collaborative Review**:
   - Share findings and consolidate insights.
4. **Final Integration**:
   - Merge analyses for regression and Apriori algorithm application.
5. **Visualizations**:
   - Create comprehensive charts and graphs for presentation.

## **Tools and Libraries**
- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` for data manipulation.
  - `matplotlib`, `seaborn` for visualizations.
  - `scikit-learn` for regression.
  - `mlxtend` for Apriori.

---