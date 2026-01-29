# MIS-311
MIS 311 Personal Portfolio Assignment  

Dataset: Life Expectancy 

Student: Nguyen Ngoc Nha Thy

University: Eastern International University 

1. Data Overview:
   
The dataset focuses on life expectancy and mortality indicators across countries worldwide. It provides insight into how different types of mortality (infant, under-five, and adult mortality) relate to overall life expectancy, allowing for comparisons across regions. This dataset is commonly used in public health, demographic, and socio-economic analysis to understand global health patterns and disparities between countries and regions. 

Data Source

The data is derived from international health and demographic statistics, similar to those published by global organizations such as the World Health Organization (WHO) or the World Bank. These sources compile mortality and life expectancy indicators reported by individual countries.

Dataset Size and Structure

The dataset consists of 182 rows and 6 columns. Each row represents one country, and each column represents a specific demographic or health indicator.

Country (object): Name of the country

Region (object): Geographic region the country belongs to

Infant_deaths (numeric): Number of infant deaths per 1,000 live births

Under_five_deaths (numeric): Number of deaths of children under five per 1,000 live births

Adult_mortality (numeric): Adult mortality rate per 1,000 population

Life_expectancy (numeric): Average life expectancy at birth (in years)

<img width="761" height="285" alt="Screenshot 2026-01-29 at 08 53 23" src="https://github.com/user-attachments/assets/651649a8-da62-45c8-93ba-ffa0af0bc334" />

2. Data Cleaning
   
 2.1. Missing Data

Select the entire dataset by Ctrl A then click on Data -> Filter -> Click the filter arrow on each column -> Uncheck Select all -> Check Blank -> If no rows a appear that column has no missing value then delete the rows that have missing numerical data spaces. The data is then removed because missing records was minimal compared to the total dataset size and does not have a critical impact on the overall distribution. Furthermore, using imputation (e.g., using mean or median values) could distort real mortality–life expectancy relationships.

 2.2. Duplicate Data:
To identify duplicate data I need to select the entire dataset and go to Data -> Remove Duplicates then tick all colummns -> OK. Excel will tell How many duplicate rows were found and How many unique rows remain

<img width="275" height="233" alt="Screenshot 2026-01-29 at 20 11 33" src="https://github.com/user-attachments/assets/63019eee-c95f-4e56-9ab8-ac17cc6b52c7" />

3. Desceriptive Statistics

Descriptive statistics were calculated for life expectancy, adult mortality, and under-five mortality across 176 countries. Life expectancy has a mean of 69 years and a relatively low standard deviation of 9, indicating limited variation across countries and a concentration of higher values.

In contrast, adult mortality and under-five mortality show much greater variability, with large standard deviations (112.4 and 43 respectively) and right-skewed distributions. This indicates that a small number of countries with very high mortality rates strongly influence the global averages.

<img width="821" height="284" alt="Screenshot 2026-01-29 at 20 32 24" src="https://github.com/user-attachments/assets/ca03c6b1-9b66-4773-9b31-9049bed6393e" />

4. Insights

<img width="530" height="170" alt="Screenshot 2026-01-29 at 21 07 43" src="https://github.com/user-attachments/assets/eaa7ceda-ea21-4d0d-87bf-739e880e1c4e" />

PivotTables were used to calculate average life expectancy, infant mortality, and adult mortality by region. This approach enables meaningful regional comparisons and reveals clear disparities in health outcomes across different parts of the world.				


<img width="575" height="297" alt="Screenshot 2026-01-29 at 21 07 49" src="https://github.com/user-attachments/assets/b80f75d3-0e57-439c-8230-d9c511cdcadf" />

Insight 1: Regional Health Inequality					
					
The PivotTable shows that regions with higher average life expectancy tend to have significantly lower infant and adult mortality rates. In contrast, regions with lower life expectancy exhibit much higher mortality levels, highlighting strong regional disparities in healthcare access and living conditions.

Insight 2: Mortality as a Key Driver					
					
Regions with elevated infant and adult mortality rates consistently show lower life expectancy averages. This suggests that mortality indicators are a major contributing factor to regional differences in overall population health.
