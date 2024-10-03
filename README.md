# IITM-IAARC Hackathon: Concrete Strength Prediction with Recycled Aggregates 🏗️🌍

##### Secured **second position** in the IITM-IAARC Hackathon for this project!! 🏆
##### [View the Hackathon Presentation](https://github.com/lem0n4id/IITM-IAARC-Hackathon/blob/main/Lenin%20Kennedy%20-%20Team%204%20-%20ISARC%20ppt.pdf) 📽️

## Overview

This project aims to predict the compressive strength of concrete made using recycled aggregates (RCA). Concrete is one of the most commonly used construction materials, and the incorporation of recycled aggregates can significantly reduce environmental impact. This study leverages various machine learning techniques to analyze data and predict concrete strength based on multiple factors. 📊🤖

## Accmplishments ⭐

- Conducted a comprehensive literature review on recycled concrete to support data analysis.
- Developed a robust machine learning model achieving significant predictive accuracy and valuable insights into concrete properties.

## Background 🌿

Concrete is a mixture of cement, water, sand, and natural aggregates (NA) like gravel or crushed stone. The use of Recycled Concrete Aggregates (RCA) can help lower waste and environmental impacts of construction. However, challenges remain in ensuring that the resulting concrete meets strength requirements. This project focuses on predicting compressive strength by examining factors such as cement-to-aggregate ratio, water absorption, and more.

## Data Description 📋

The dataset includes various tests and parameters that influence the compressive strength of concrete:

- **Compressive strength (f’c) (MPa)**: The compressive strength of hardened concrete.
- **Effective water-to-cement ratio**: Ratio of mass of water to mass of cement.
- **Aggregate-to-cement ratio (a/c)**: Ratio of mass of aggregate to mass of cement.
- **RCA replacement ratio (RCA %)**: Percentage of coarse aggregate replaced with RCA.
- **Parent concrete strength (MPa)**: Compressive strength of the original concrete used for RCA.
- **Bulk density of RCA (kg/m³)** and **NA (kg/m³)**: Mass of aggregates per unit volume.
- **Water absorption of RCA (%) and NA (%)**: Percentage of water absorbed by aggregates.
- **Los Angeles abrasion of RCA and NA**: Resistance to abrasion.
- **Density of hardened concrete (AD and SSD)**: Mass per unit volume in dry and saturated states.

## Results 📈

| Model Name                | Accuracy (R²) | RMSE |
|---------------------------|----------------|------|
| Linear Regression          | 0.31           | 9.62 |
| Random Forest Regressor    | 0.31           | 9.62 |
| Gradient Boosting Regressor | 0.63           | 7.09 |
| **XGBoost**                | **0.86**       | **5.65** |

- **Conclusion**: The XGBoost model outperformed others with 86% accuracy. Key factors influencing compressive strength were identified, including nominal maximum RCA size and effective water-to-cement ratio.

## Future Scope 🚀

- Implement better data interpolation/imputation algorithms for missing values in key features.
- Identify and remove outliers to enhance model accuracy.
- Explore deep learning approaches for improved predictions, given the complex nature of the dataset.

## Technologies Used 💻

- **Programming Language**: Python
- **Development Environment**: Jupyter Notebook
- **Libraries**: Pandas, Scikit-learn, XGBoost, Matplotlib, etc.



## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
