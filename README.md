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
- **Time Series Segmentation Algorithms:** Employed unsupervised algorithms (e.g., Hidden Markov Model, ClaSP, BinSeg) to identify changes and breakpoints in precipitation patterns over time.
- **Multivariate Analysis:** Considered multiple variables (humidity, temperature, soil moisture, wind speed, air pressure) to understand their influence on precipitation.

### Findings:
- **Improved Prediction Accuracy:** Implemented segmentation techniques enhanced precipitation prediction models, surpassing traditional statistical methods.
- **Localized Climate Insights:** Revealed how climate change has affected precipitation variability within Marion County.

### Project Impact:
- **Bridge Resource Gap:** Potentially improves weather forecasting capabilities in resource-limited regions.
- **Inform Disaster Management:** Provides actionable insights for disaster preparedness and water resource management in underdeveloped areas.

### Repository Structure:
1. **Code:** Contains scripts for data preprocessing, segmentation algorithms, and model development.
2. **Data:** Includes datasets used for analysis (IMERG data, meteorological variables).
3. **Results:** Provides detailed outcomes of segmentation, model comparisons, and climate change impact analysis.
4. **Documentation:** Supplementary materials, including project overview, methodologies, and findings.

### Conclusion:
This research contributes to advancing precipitation prediction and climate change analysis at a local scale. By combining advanced modeling techniques with in-depth data segmentation, the study sheds light on climate dynamics and resilience-building strategies in Marion County and similar regions.

For more details, refer to the project documentation and results in this repository.

---
*This README summarizes the research project on rainfall prediction and climate change analysis conducted in Marion County, KY. For inquiries or access to detailed findings, please refer to the associated repository files.*
