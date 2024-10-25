
# Tobacco Use Survey Data Analysis

## Dataset Description

The dataset provides insights into tobacco usage across various states in the United States over multiple years. It contains information segmented by demographic factors such as age, race, gender, and education level, and measures tobacco usage (e.g., smoking status, user status) among different groups. Key fields include:
- `YEAR`: The year the data was collected.
- `LocationAbbr` & `LocationDesc`: Abbreviated and full state names.
- `TopicType` & `TopicDesc`: General and specific topic categories (e.g., “Tobacco Use – Survey Data” and “Cigarette Use (Youth)”).
- `MeasureDesc`: Description of the measured variable, such as “Smoking Status”.
- `Response`: The type of response, such as "Ever," "Current," etc.
- `Data_Value_Unit` & `Data_Value_Type`: The unit and type of the data value (e.g., "Percentage").
- `Gender`, `Race`, `Age`, and `Education`: Demographic details.
- `DisplayOrder`: Numeric order for display purposes.

## Summary of Findings

- The data highlights trends in tobacco usage across different demographic groups over several years.
- Key patterns include fluctuations in smoking rates by age and educational attainment, and geographic differences in tobacco use among states.
- Detailed visualizations and models reveal significant insights into how demographics influence tobacco use rates.

## Data Preprocessing

1. **Data Cleaning**: Removed any unnecessary columns or rows with missing values to enhance the dataset's usability.
2. **Standardization**: Unified categories across demographic fields for consistency in analysis.
3. **Transformation**: Transformed certain columns (e.g., converting percentages to numeric values for analysis).
4. **Encoding**: Encoded categorical variables for model compatibility.

## Exploratory Data Analysis

The exploratory data analysis (EDA) provided a foundation for understanding patterns in the dataset, including:
- **Frequency Analysis**: Counted occurrences across categories such as gender, race, and age.
- **Correlation Analysis**: Evaluated relationships between demographic variables and tobacco use metrics.
- **Trend Analysis**: Identified temporal trends across years, helping in understanding changes in tobacco usage.

## Visualization

1. **Trends in Tobacco-Related Measures Over Time (Line Chart)**:
   ![Trends Over Time](images/trends_over_time.png)
   - This line chart illustrates changes in tobacco-related measures (e.g., "Smoking Status," "User Status") across the years. The lines for each measure reveal patterns or shifts over time, indicating trends in smoking behaviors or tobacco use within the population.

3. **Breakdown of Tobacco Use by Age (Bar Plot)**: 
   - This bar plot illustrates the demographic breakdown of tobacco use across different age groups. The x-axis represents various age categories, while the y-axis indicates the count of tobacco-related measures for each age group. Each bar is color-coded according to different measure descriptions, providing insights into how tobacco use varies among demographics.

4. **Heatmap of Data Values by Education and Topic (Heatmap)**: 
   - This heatmap shows the relationship between educational attainment and various tobacco-related measures across topics. Each cell's color intensity indicates the average value of the tobacco-related measures for each educational level, helping visualize how education may impact engagement with tobacco issues.

5. **Combined Analysis of Tobacco Use Trends by Gender Over Time (Facet Grid)**: 
   - This facet grid shows tobacco use trends over time, with separate histograms for each gender. Each subplot represents either male or female, and the stacked bars display the annual distribution for each tobacco measure, revealing any notable gender differences in smoking behaviors over the years.

## Model Development

The following machine learning models were developed to predict tobacco usage likelihood based on demographic factors:

- **Logistic Regression**: Used to model binary tobacco use outcomes.
- **Decision Tree**: Developed to capture complex interactions among demographic factors.
- **Random Forest**: An ensemble model providing robust predictions with reduced overfitting.

## Model Evaluation

Each model was evaluated using metrics such as accuracy, precision, recall, and F1-score:

1. **Logistic Regression**:
   - **Evaluation**: Achieved an accuracy of X%, indicating baseline effectiveness.
2. **Decision Tree**:
   - **Evaluation**: With an accuracy of Y%, this model was effective at capturing interactions.
3. **Random Forest**:
   - **Evaluation**: Provided the highest accuracy at Z%, balancing bias and variance.

## Conclusion

This analysis demonstrates significant insights into tobacco usage patterns across demographic groups and locations. Models reveal strong predictors of tobacco use, and visualizations underscore key trends over time.

## Contributors

- Mike Fernando Bunag
- Mitch

