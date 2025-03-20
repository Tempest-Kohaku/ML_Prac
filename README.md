# ML Practice

This repository contains a collection of machine learning code samples and practice examples using Python. The examples in this project demonstrate several popular machine learning algorithms and techniques using built-in datasets from Seaborn and scikit-learn. The topics covered include:

1. **Linear Regression**  
   - Predicting tip amounts using the "tips" dataset.
   - Evaluation using Mean Absolute Error (MAE) and Mean Squared Error (MSE).
   - Plotting residual distributions.

2. **Logistic Regression**  
   - Classifying iris species using the Iris dataset.
   - Displaying accuracy, classification report, and confusion matrix.
   - Visualizing the confusion matrix with a heatmap.

3. **Decision Tree Classifier**  
   - Training a decision tree on the Iris dataset.
   - Visualizing the decision tree structure.
   - Evaluating performance with common classification metrics.

4. **K-Means Clustering**  
   - Unsupervised clustering on the Iris dataset.
   - Visualizing clusters with scatter plots.

5. **Perceptron**  
   - Using the Perceptron algorithm from scikit-learn on the Iris dataset.
   - Evaluating performance with accuracy, classification report, and confusion matrix.

6. **Support Vector Machine (SVM)**  
   - Training an SVM on a 2D projection (first two features) of the Iris dataset.
   - Plotting the decision boundary.
   - Evaluating with accuracy, confusion matrix, and a classification report.

7. **Naive Bayes Classifier**  
   - Using Gaussian Naive Bayes on the Iris dataset.
   - Optionally taking user input for predictions.
   - Reporting model accuracy.

8. **Apriori Algorithm**  
   - Finding frequent itemsets and generating association rules using the `mlxtend` library.
   - Applying Apriori on a sample transaction dataset.

9. **Voting Classifier**  
   - Combining multiple classifiers (Logistic Regression, Decision Tree, and K-Nearest Neighbors) using both hard and soft voting.
   - Evaluating the ensemble classifier's accuracy.

10. **Random Forest Classifier**  
    - Training and evaluating a Random Forest on the Iris dataset.
    - Visualizing the confusion matrix with a heatmap.

## Getting Started

### Prerequisites

Before running the code, ensure you have Python installed on your system. To check your Python version, open your command prompt or terminal and type:

```bash
python --version
```

### Required Libraries

The following Python libraries are required:

- **numpy**
- **seaborn**
- **matplotlib**
- **scikit-learn**
- **mlxtend**

You can install these libraries using one of the methods below:

#### Using pip

```bash
pip install numpy seaborn matplotlib scikit-learn mlxtend
```

#### Using Jupyter Notebook

In a Jupyter Notebook cell, run:

```python
!pip install numpy seaborn matplotlib scikit-learn mlxtend
```

#### Using Anaconda Prompt

```bash
conda install numpy seaborn matplotlib scikit-learn
pip install mlxtend
```

> **Note:** The `mlxtend` library may not be available through conda and might require pip installation.

## Repository Structure

- **README.md**: This file.
- **ML Practice (1).pdf**: PDF document containing the full code examples and outputs.
- **[Other files]**: Any additional scripts or notebooks can be placed here.

## Running the Code

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/ml-practice.git
   cd ml-practice
   ```

2. **Install Required Libraries** (see installation instructions above).

3. **Open and Run the Code Examples**

   Open the desired code file (or Jupyter Notebook) in your preferred Python IDE or editor and run the code to see the results.

## Contributing

Contributions are welcome! If you have improvements or additional examples to share, please fork this repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- [Seaborn](https://seaborn.pydata.org/) for the built-in datasets.
- [scikit-learn](https://scikit-learn.org/) for the machine learning algorithms.
- [mlxtend](http://rasbt.github.io/mlxtend/) for the Apriori and association rules implementation.
