## MSCS_634_Lab_1: Data Visualization, Data Preprocessing, and Statistical Analysis
### Purpose

The objective of this lab was to apply data visualization, preprocessing, and statistical analysis techniques to a real-world used car dataset using Python and Jupyter Notebook. Rather than working directly with raw data, the lab emphasized the importance of preparing data through cleaning, transformation, and reduction before performing analysis. This process provided an opportunity to examine how data quality influences the reliability of analytical results and insights.

### Key Insights

The scatter plot showed that vehicle prices generally declined with increasing age, suggesting that depreciation plays a significant role in determining market value. The histogram further demonstrated that most vehicles were concentrated in the lower- and mid-range price categories, while a smaller number of expensive vehicles skewed the distribution to the right.

The statistical analysis reinforced these observations. Measures of central tendency provided a useful estimate of typical vehicle prices, while dispersion measures highlighted substantial variability across listings. Correlation analysis showed that numerical attributes were not independent of one another, helping identify relationships that may influence vehicle pricing decisions.

### Challenges and Decisions

One challenge encountered during the preprocessing stage involved the kmDriven attribute. Although it represented numerical mileage information, the values were stored as text and included formatting characters such as commas and the "km" suffix. These values had to be cleaned and converted into a numerical format before calculations could be performed.

Several preprocessing decisions were made to improve data quality. Missing mileage values were replaced using the column mean to preserve observations while minimizing information loss. Outliers in asking price were identified using the Interquartile Range (IQR) method and removed to reduce the influence of extreme values on the analysis. In addition, less relevant attributes were removed during data reduction, and Min-Max scaling was applied to selected numerical variables to place them on a comparable scale. These steps resulted in a cleaner dataset, better suited for visualization and statistical analysis.
