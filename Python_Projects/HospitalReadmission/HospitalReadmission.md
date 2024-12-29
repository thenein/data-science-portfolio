# Predicting Hospital Readmissions for Diabetic Patients

## Project Overview

This project uses machine learning techniques to predict hospital readmissions for diabetic patients. The dataset used for this analysis is the Diabetes 130-US Hospitals Dataset. The goal is to leverage various models to improve the accuracy of readmission predictions, providing valuable insights to healthcare providers to enhance patient care and reduce readmission rates.

## Objectives

- Develop predictive models to identify patients at risk of readmission.
- Compare the performance of Logistic Regression, Random Forest, and Gradient Boosting Machines (GBMs).
- Assess the impact of different features on model performance.
- Visualize key insights and findings through relevant plots and metrics.

## Milestones

### Milestone 1: Data Exploration and Preprocessing

- Load and clean the dataset.
- Perform exploratory data analysis (EDA) to understand data distribution and patterns.
- Handle missing values, outliers, and categorical variables.
- Feature engineering and selection.

### Milestone 2: Model Development

- Implement Logistic Regression, Random Forest, and GBMs.
- Perform hyperparameter tuning using grid search or random search.
- Evaluate models using cross-validation.

### Milestone 3: Results and Visualization

- Compare model performance based on accuracy, precision, recall, and F1-score.
- Generate ROC curves and confusion matrices.
- Identify the most important features contributing to predictions.
- Visualize results using Matplotlib and Seaborn.

### Milestone 4: Presentation and Reporting

- Create a comprehensive report summarizing findings and insights.
- Develop visualizations and charts to support the analysis.
- Present the final model and recommendations.

## Technologies and Tools

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Visualization Tools:** Matplotlib, Seaborn
- **Modeling Techniques:** Logistic Regression, Random Forest, Gradient Boosting

## Dataset

- **Name:** Diabetes 130-US Hospitals Dataset
- **Source:** Public dataset available on Kaggle
- **Description:** The dataset contains records of diabetic patients, including demographic information, lab results, and previous hospital encounters.

## Installation and Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/thenein/hospital-readmission-prediction.git
   ```
2. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook HospitalReadmission.ipynb
   ```
4. Run all cells in the notebook to preprocess data, train models, and visualize results.

## Results

- Model performance metrics will be presented in the final report.
- Key visualizations include feature importance plots, ROC curves, and confusion matrices.

## Future Work

- Incorporate additional features for improved prediction accuracy.
- Explore deep learning models.
- Deploy the best-performing model as a web application for real-time predictions.

## Contributors

- [Ehab Henein](https://github.com/thenein)

## License

This project is licensed under the MIT License.
