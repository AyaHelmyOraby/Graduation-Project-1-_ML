# Near-Earth Object (NEO) Hazard Classification

## Overview
This project analyzes Near-Earth Objects (NEOs) to determine their potential hazard risk. Using data preprocessing, feature engineering, and machine learning models, we classify whether an asteroid is hazardous or not based on various attributes.

## Dataset
The dataset contains information about NEOs, including:
- **absolute_magnitude**: Brightness of the object
- **estimated_diameter_min/max**: Size range in kilometers
- **orbiting_body**: The celestial body the NEO orbits
- **relative_velocity**: Speed relative to Earth
- **miss_distance**: Distance from Earth
- **is_hazardous**: Target variable (True/False)

## Data Preprocessing
- **Handling Missing Values**: Imputed missing data using mean for numerical columns.
- **Feature Scaling**: Normalized numerical features using StandardScaler.
- **Encoding Categorical Data**: Used Label Encoding for categorical variables.
- **Handling Imbalanced Classes**: Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.

## Exploratory Data Analysis (EDA)
We conducted thorough data visualization using **Matplotlib**, **Seaborn**, and **Plotly** to identify trends:
- Heatmaps to examine correlations between features.
- Scatter plots and histograms to visualize distributions.
- Box plots to detect outliers.

## Model Training and Evaluation
We trained multiple machine learning models:
1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Gradient Boosting Classifier**
4. **Support Vector Machine (SVM)**

### Performance Metrics:
- **Accuracy**
- **Precision & Recall**
- **F1-Score**
- **ROC-AUC Score**

The **Random Forest Classifier** performed best with an F1-score of **X.XX** and an AUC-ROC of **X.XX**.

## Key Findings
- **Larger asteroids tend to be more hazardous**.
- **Relative velocity has a moderate correlation with hazard classification**.
- **Miss distance alone is not a strong predictor of hazard risk**.

## Next Steps
- Experiment with deep learning models (Neural Networks).
- Explore additional feature engineering.
- Deploy the best-performing model as a web service.


## Contributors
- **[Aya Oraby]** – Data Science & Machine Learning

## License
This project is licensed under the MIT License.

