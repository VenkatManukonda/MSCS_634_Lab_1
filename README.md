## MSCS_634_Lab_1: Data Visualization, Data Preprocessing, and Statistical Analysis

### Purpose
This lab focused on exploring a used car dataset using Python in Jupyter Notebook. The goal was to examine the data through visualization, preprocess it to improve quality, and apply statistical analysis techniques to better understand its patterns. Working through the preprocessing steps demonstrated how raw data often requires cleaning and transformation before meaningful analysis can be performed.

### Key Insights
The visualizations revealed a noticeable relationship between vehicle age and asking price. As vehicle age increased, asking prices generally declined, reflecting depreciation's impact on vehicle value. The price distribution also showed that most vehicles were concentrated in the lower- and mid-range price categories, while a smaller number of expensive vehicles skewed the distribution to the right.
The statistical analysis supported these observations. Measures of central tendency provided a view of typical vehicle pricing, while dispersion measures highlighted substantial variability across listings. Correlation analysis helped identify relationships among numerical attributes and showed that age and mileage were important factors influencing vehicle prices.

### Challenges and Decisions
One challenge was the kmDriven column, which stored mileage values as text, including formatting characters like commas and the "km" suffix. These values had to be cleaned and converted into a numerical format before missing values could be handled and statistical calculations could be performed.
To maintain data quality, missing mileage values were replaced using the column mean. Outliers were identified using the Interquartile Range method and removed to reduce the influence of unusually high-priced listings. Data reduction was performed by removing less relevant columns, while Min-Max scaling was applied to selected numerical attributes to place them on a comparable scale. These decisions helped produce a cleaner dataset better suited for analysis and visualization.

### Repository Contents
This repository contains the Jupyter Notebook used for the analysis, the original used car dataset, a screenshots folder containing all required screenshots, and supporting documentation. The screenshots folder includes dataset loading, visualizations, preprocessing steps, statistical calculations, and correlation analysis completed during the lab.
