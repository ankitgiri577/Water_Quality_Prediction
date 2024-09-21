# Water Quality Analysis

## Dataset Overview:

Access to safe and clean drinking water is crucial for maintaining good health and well-being. It is recognized as a basic human right. Ensuring the availability of clean water is important not only for individual health but also for economic development, as improvements in water quality can reduce healthcare costs and boost economic productivity. In some areas, upgrading water supply systems brings significant financial advantages by minimizing negative health outcomes.

## Data Attributes:

**Input features** derived from various chemical and physical assessments of water quality:
1. **pH**: Acidity/alkalinity level of water.
2. **Hardness**: Water's ability to react with soap, measured in mg/L.
3. **Total Dissolved Solids (Solids)**: Represents the concentration of dissolved substances, expressed in ppm.
4. **Chloramine Content**: The level of chloramines in water, in ppm.
5. **Sulfates**: Concentration of sulfate ions, recorded in mg/L.
6. **Conductivity**: The water's ability to conduct electricity, given in μS/cm.
7. **Organic Carbon**: Amount of carbon-based compounds present, in ppm.
8. **Trihalomethanes**: The concentration of trihalomethanes in water, given in μg/L.
9. **Turbidity**: Water's transparency measured through its light-scattering properties (Nephelometric Turbidity Units, NTU).

**Output feature** based on sensory testing:
10. **Potability**: A binary variable indicating whether the water is deemed safe for consumption.

## Dataset Source:
You can find the dataset [here](https://www.kaggle.com/adityakadiwal/water-potability).

## Required Libraries:
- `pandas` for data manipulation.
- `matplotlib` and `seaborn` for data visualization.
- `plotly` for interactive plots.
- `scikit-learn` and `xgboost` for machine learning models.

## Machine Learning Algorithms Used:
- **Logistic Regression**
- **K-Nearest Neighbors**
- **Support Vector Machine**
- **Decision Tree**
- **Random Forest**
- **XGBoost**

## Best Model Performance:
The highest accuracy achieved by any model so far is 70%.
