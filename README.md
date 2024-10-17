# Red Wine Quality Prediction with Random Forest


## 1. Project Overview

This project implements a Random Forest Classifier to predict the quality of red wine based on various chemical properties. The dataset includes features such as acidity, residual sugar, pH, alcohol content, and more. The goal is to predict the wine quality on a scale (e.g., from 3 to 8), which has been simplified into a classification problem (e.g., "low" and "high" quality).


## 2. Dataset Source

https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009


## 3. Features
- **Data Preprocessing**:  cleaning, normalization, and splitting into training and testing sets.
- **Model Training**: Training a Random Forest Classifier using scikit-learn to predict wine quality.
- **Model Evaluation**: Evaluating the performance of the model using metrics such as accuracy, precision, recall, and F1-score.


## 4. Project Structure
    ├── winequality-red.csv         # Dataset file 
    ├── wine_quality.ipynb          # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/wine_quality.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook wine_quality.ipynb
```
## 6. Usage

Open the wine_quality.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the winequality-red.csv and perform necessary preprocessing.
- **Model Training**: ain a Random Forest Classifier with adjustable hyperparameters like n_estimators, max_depth, and max_features to optimize performance.
- **Model Evaluation**: Evaluate the model using metrics like accuracy, precision, recall, F1-score for a better understanding of the model's predictions.


## 7. Results in Test
| Metric    |  Value |
|-----------|--------|
| Accuracy  |  93%   |
| Precision |  88%   |
| Recall    |  77%   |
| F1 Score  |  82%   |

## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.







