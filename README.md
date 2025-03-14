# Tuberculosis Classification using Machine Learning

## Project Overview
This project implements machine learning models to classify tuberculosis (TB) cases. The models used include **Support Vector Classifier (SVC)**, **Logistic Regression** and **Naive Bayes**.

## Problem Statement
Tuberculosis is a serious infectious disease that requires early and accurate diagnosis. Machine learning can help in automating the classification process,improving efficiency in medical diagnosis in resource-constraint locations in Nigeria.

## Approach
1. Data preprocessing, including handling missing values and feature scaling.
2. Exploratory Analysis: Visualizing distributions of age, gender, TB types, and geographic factors.
3. Model selection and training using:
   - Support Vector Classifier (SVC)
   - Logistic Regression
   - Gaussian Naive Bayes
4. Evaluation using performance metrics like accuracy, precision, recall, and F1-score.

## Technologies & Libraries Used
- Python
- Pandas (Data manipulation)
- NumPy (Numerical operations)
- Scikit-Learn (ML models: SVM, Logistic Regression, Naive Bayes)
- Matplotlib & Seaborn (for visualization)
- Google Colab (Notebook execution)

## Results & Insights
- The trained models were evaluated using standard classification metrics.
- Key demographic trends (e.g., age distribution, gender disparities).
- Feature importance analysis highlighting critical diagnostic markers.
- Model performance comparisons (accuracy, confusion matrices).

## How to Run the Notebook
1. **Setup**:
   - Upload the `TB-Dataset.csv` to your Google Drive under `/content/drive/MyDrive/`.
   - Ensure the following libraries are installed:
     ```
     pandas, numpy, matplotlib, seaborn, scikit-learn
     ```

2. **Open in Google Colab**:
   - Upload the notebook `tuberculosis-classification-ml.ipynb` to Colab.
   - Mount Google Drive when prompted:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

3. **Run the Notebook**:
   - Execute cells sequentially to load data, preprocess, visualize, and train models.
   - Adjust model hyperparameters for experimentation.

4. **Data Path**:
   - Ensure the dataset path in the notebook matches your Drive location:
     ```python
     file_path = r"/content/drive/MyDrive/TB-Dataset.csv"
     ```

## Author
James Bode Emiade
