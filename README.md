## Rainfall Prediction & Climate Change Analysis: Time Series Segmentation

This repository contains the code and results of a research project focused on predicting precipitation and analyzing climate change dynamics using time series segmentation techniques. The study was specifically conducted in Marion County, KY, leveraging NASA'sdataset for high-resolution climate data analysis.

### Introduction:
Rainfall prediction is crucial for disaster management and resource planning, yet many underdeveloped regions lack the necessary infrastructure for accurate forecasts. This gap is being addressed through initiatives like NASA's  dataset, which provides high-resolution precipitation data using satellite imagery. Advanced techniques such as time series segmentation further enhance prediction accuracy, enabling better disaster preparedness and climate resilience in vulnerable communities.

### Research Objectives:
- **Precipitation Prediction:** Develop accurate rainfall prediction models for Marion County using machine learning and time series segmentation.
- **Climate Change Analysis:** Investigate how climate change has influenced precipitation patterns over time within the region.

### Dataset:
- **Nasa Dataset:** Utilized  high-resolution precipitation data (collected every 3 hours), enabling detailed analysis of local climate dynamics. it contains 34 climate variables which are all continuous from 2010 to 2020 with 32k samples which makes it a dataset with high resolution.

### Data cleaning:
- There are a few corrupt samples that are too large for the data which was validated from the web and removed. NA's are replaced with data from previous samples if more than three continuous samples are NA's data from previous year is considered.

### Key Methodologies:
<img src="Blank diagram.png">


- **Precipitation Prediction:**  This problem is approached from both regression and classification angles initial approach was Regression but the regression models performance was very low so it was converted to a classification problem which gave better results
- **Time Series Segmentation Algorithms:** Employed unsupervised algorithms (Prophet, ClaSP) to identify changes and breakpoints in precipitation patterns over time.
- **Time Series Forecasting:** Even though model performance has improved with classification it necessary to have models that can predict seasonality so monthly forcasting models are built
- **Seasonal Models:** To improve the classification efficiency i have split the model into summer and winter which has improved the classification performance 

### Findings:
- **Improved Prediction Accuracy:** Spliting model techniques enhanced precipitation prediction models, surpassing traditional statistical methods.
- **Localized Climate Insights:** Revealed how climate change has affected precipitation variability within Marion County.

### Results
- **Regression:** Performace is below average(Random Forest)
- **Classification:** When compared to regression the performance has significantly improved(XGB)
- **Seasonal Models:** By splitting annual  models into seasonal models there is some improvement in performance(XGB)
- **Monthly Forcast:** The model has MAE of 26 (FB Prophet)

### Repository Structure:
1. **Code:** Contains scripts for data preprocessing, segmentation algorithms, and model development.
2. **Data:** Includes datasets used for analysis (data, meteorological variables).
3. **Results:** Provides detailed outcomes of segmentation, model comparisons, and climate change impact analysis.


### Conclusion:
This research contributes to advancing precipitation prediction and climate change analysis at a local scale. By combining advanced modeling techniques with in-depth data segmentation, the study sheds light on climate dynamics and resilience-building strategies in Marion County and similar regions.

For more details, refer to the project documentation and results in this repository.

---
*This README summarizes the research project on rainfall prediction and climate change analysis conducted in Marion County, KY. For inquiries or access to detailed findings, please refer to the associated repository files.*
