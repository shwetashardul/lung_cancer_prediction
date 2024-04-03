# Lung Cancer Prediction

## Project Overview
This project aims to leverage machine learning algorithms to predict lung cancer risk based on patient data. Through rigorous data analysis and model development, our goal is to provide insights that could lead to early detection and intervention, potentially saving lives.

## Dataset
The dataset consists of patient records with various features, including demographic information, smoking history, family cancer history, and medical records. 

## Exploratory Data Analysis (EDA)
Our EDA process involved the following steps to understand the dataset better and prepare it for modeling:

- **Data Cleaning**: Addressing missing values, removing duplicates, and correcting data types.
- **Feature Engineering**: Creating new features that could better represent the underlying patterns related to lung cancer risk.
- **Statistical Analysis**: Analyzing distributions, correlations, and other statistical properties of the data.

### Insights from EDA
- Smoking history shows a strong correlation with lung cancer risk.
- Patients with a family history of cancer have a higher likelihood of lung cancer.
- [Insert other significant insights here.]

## Data Visualization
To visualize our findings and the relationships between features, we used several types of plots:

- **Histograms** for distribution of age, smoking years, etc.
- **Scatter plots** to observe relationships between continuous variables.
- **Correlation heatmaps** to identify the correlation between different features.
- **Box plots** to visualize the statistical summaries of various features.

![Correlation Heatmap](https://github.com/shwetashardul/lung_cancer_prediction/blob/master/correlation_heatmap.png)
*Correlation heatmap showing the relationship between features.*



## Machine Learning Models
We experimented with several machine learning models to predict lung cancer risk:

- **Decision Trees**: Achieved the highest accuracy of [100]%.
![Decision tree plot.](https://github.com/shwetashardul/lung_cancer_prediction/blob/master/decision_tree_plot.png)
*Decision tree generated for lung cancer dataset.*

![Confusion Matrix for Decision Tree Classifier.](https://github.com/shwetashardul/lung_cancer_prediction/blob/master/confusion_matrix_Decision_Tree.png)
*Confusion Matrix for Decision Tree Classifier.*

- **Logistic Regression**: Showed [86]% accuracy.
![Confusion Matrix for Logistic Regression Classifier.](https://github.com/shwetashardul/lung_cancer_prediction/blob/master/confusion_matrix_LR.png)
*Confusion Matrix for Logistic Regression Classifier.*

- **Support Vector Machines (SVM)**: Provided a baseline for performance [92]% on the test set.
![Confusion Matrix for SVM Classifier.](https://github.com/shwetashardul/lung_cancer_prediction/blob/master/confusion_matrix_svm.png)
*Confusion Matrix for SVM Classifier.*

## Model Evaluation
Our evaluation criteria included accuracy, precision, recall, and F1 score. The Decision Tree model showed the best performance across these metrics, making it our chosen model for this project.

## Installation
Instructions on setting up the project environment and running the code.

## Usage
Steps to execute the code, including how to run the model and interpret the results.

## Contributing
Guidelines for contributing to the project.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments
- Data provided by [Data Source].
- Inspired by the work on early cancer detection research.



## Technologies Used
- Python: For all backend processing and machine learning implementation.
- Libraries: Pandas, NumPy, Scikit-Learn for data manipulation, analysis, and model building.
- Data Visualization: Matplotlib and Seaborn for visualizing the data and results.

## Getting Started

### Prerequisites
- Ensure you have Python installed on your machine. You'll also need the following libraries:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn


### Installation
1. Clone the repository:
git clone <https://github.com/shwetashardul/lung_cancer_prediction>

2. Navigate to the project directory and install the required packages: cd Lung Cancer Prediction


## Usage
To run the prediction model: python lung_cancer_predictor.py

Follow the prompts to input patient data and receive a risk prediction.

## Contributing
We welcome contributions! Please feel free to fork the repository, make changes, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments
- Data provided by [Kaggle].
- Inspired by the work on early cancer detection research.


