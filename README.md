# Ethical Issues for AI

This repository contains a Jupyter notebook, which explores the topic of fairness in Machine Learning (ML) using a dataset related to HR practices.

## Notebook Overview

The notebook is titled "Ensuring Fairness: Ethical AI Practices in HR". It presents the process of data preprocessing, model training, fairness evaluation, and bias mitigation in the context of a machine learning application for HR practices.

## Key Steps

1. **Data Preprocessing**: The notebook starts with data preprocessing setup which includes importing necessary libraries and setting display options. 

2. **Data Loading and Overview**: The data is loaded into a pandas DataFrame, and then an initial exploration is conducted to understand the structure of the dataset. 

3. **Model Training**: A logistic regression model is trained using sklearn.

4. **Fairness Evaluation**: The fairness of the model is evaluated using metrics from the `holisticai` library. 

5. **Bias Mitigation**: Several bias mitigation techniques from `holisticai` are applied and evaluated.

## Libraries Used

- `pandas`
- `seaborn`
- `matplotlib`
- `numpy`
- `re`
- `sklearn`
- `holisticai`

## Installation

To run the notebook, you need to have Python installed, ideally through an Anaconda distribution. In addition, you need to have the following libraries: pandas, seaborn, matplotlib, numpy, re, sklearn, and holisticai. You can install these using pip:

```python
pip install pandas seaborn matplotlib numpy sklearn holisticai cvxpy
```

## Note

This is part of my Master's project for the 'Ethical issues for AI' course.

## License

See `LICENSE` for more information.
