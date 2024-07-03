# Forest Cover Type Prediction

This project, part of Codecademy's Deep Learning course, aims to predict forest cover types using a deep learning model based on various cartographic features.

## Project Overview

The objective is to classify forest cover types from cartographic variables like elevation, aspect, slope, and distances to hydrological, road, and fire points. The dataset is sourced from the US Forest Service (USFS) Region 2 Resource Information System.

## Key Steps

1. **Data Exploration**: Initial understanding of the dataset structure and statistics.
2. **Data Preprocessing**: Handling missing values, standardizing features, and using SMOTE for class imbalance.
3. **Model Building**: Developing a multi-layer perceptron model.
4. **Training and Evaluation**: Training the model and evaluating its performance on validation and test sets.
5. **Hyperparameter Tuning**: Using random search to optimize model parameters.
6. **Misclassification Analysis**: Analyzing misclassified instances to improve the model.

## Results

- **Validation Accuracy**: 90.00%
- **Test Accuracy**: 91.95%

## Conclusion

This project demonstrates the application of deep learning techniques to predict forest cover types accurately, highlighting skills in data preprocessing, model development, and performance evaluation.

## Repository Contents

- `cover_data.csv`: Dataset used for the project.
- `notebook.ipynb`: Jupyter notebook with the project code and analysis.
- `resampled_data.pkl`: Resampled dataset.
- `initial_model.keras`: Initial trained model.
- `best_model.keras`: Best model after hyperparameter tuning.
- `misclassified_instances.csv`: CSV file containing misclassified instances.

## Getting Started

1. Clone the repository.
2. Install the required libraries.
3. Run the notebook to see the complete analysis and results.
