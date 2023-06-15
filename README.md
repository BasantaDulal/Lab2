# Breast Cancer Classification Models

This repository contains machine learning models for breast cancer classification using scikit-learn. The models are trained on the Breast Cancer Wisconsin (Diagnostic) dataset and provide a way to predict whether a tumor is malignant (cancerous) or benign (non-cancerous) based on its features.

## Dataset

The Breast Cancer Wisconsin (Diagnostic) dataset used in this project can be found at the following URL:
[Dataset Link](https://github.com/BasantaDulal/Lab2/blob/branch1/data.csv)

The dataset consists of several features computed from digitized images of breast mass, including mean radius, mean texture, mean perimeter, mean area, and more. Each sample is labeled as either malignant (M) or benign (B) based on the diagnosis.

## Models

### Decision Tree Model (Version 1)

The decision tree model is built using scikit-learn's `DecisionTreeClassifier`. It creates a flowchart-like tree structure of decisions based on the features to predict the class labels. This model provides interpretability and can be visualized to understand the decision-making process.

### Random Forest Model (Version 2)

The random forest model is built using scikit-learn's `RandomForestClassifier`. It combines multiple decision trees to create an ensemble model. Each tree is trained on a different subset of the data, and the final prediction is based on the majority vote of all the trees. Random forest models generally have higher accuracy and are less prone to overfitting.

## Usage

To use these models, follow these steps:

1. Clone the repository to your local machine:
2. Install the required dependencies:

3. Explore the provided Jupyter notebook or Python script to understand the model building process, feature engineering, and evaluation.

4. Run the notebook/script to train the models on the Breast Cancer dataset.

5. After training, you can make predictions on new breast tumor samples by providing the relevant features as input to the models.

## Evaluation and Performance

Both models are evaluated using common classification metrics such as accuracy, precision, recall, and F1-score. The evaluation results can be found in the notebook/script along with a confusion matrix to assess the model's performance.

## Contributing

Contributions to this repository are welcome. If you have any suggestions, improvements, or additional models for breast cancer classification, feel free to submit a pull request. Please ensure to follow the standard coding practices and provide a clear explanation of your contributions.

## License

This project is licensed under the [MIT License](LICENSE).
