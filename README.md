## Handwritten Digit Recognition with KNN

## Description

This project implements a K-nearest neighbors (KNN) classifier to recognize handwritten digits from a dataset. It explores the impact of different K values on the model's performance and evaluates its effectiveness using various metrics.

## Requirements

- Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))
- pandas ([https://pypi.org/project/pandas/](https://pypi.org/project/pandas/))
- scikit-learn ([https://scikit-learn.org/stable/install.html](https://scikit-learn.org/stable/install.html))

## Usage

1. **Download the dataset:**
   - Ensure you have obtained the necessary dataset files, "train.csv" and "test.csv," in the same directory as this code.
2. **Run the script:**
   - Open a terminal or command prompt and navigate to the directory containing the Python script and dataset files.
   - Execute the script using `python script.py`. This will print the accuracy, confusion matrices, precision, recall, and F1 scores for each K value.

## Output

The script will output the following information for each K value:

1. **Accuracy:** The percentage of test samples correctly classified.
2. **Confusion Matrix:** A table illustrating the distribution of actual vs. predicted labels.
3. **Precision:** The fraction of predicted positives that are actually true positives.
4. **Recall:** The fraction of actual positives that are correctly identified by the model.
5. **F1 Score:** A harmonic mean of precision and recall, combining their measures into a single score.

## Understanding K Value

The script tests the model with different K values (3, 5, 7, 9, and 11). The optimal K value generally depends on the dataset and problem, and you may want to experiment with a wider range of values to find the best performing configuration.

## Additional Notes

- This is a basic implementation that can be further improved with techniques like feature scaling, hyperparameter optimization, or exploring different machine learning algorithms.
- Feel free to customize the script to fit your specific dataset and requirements.
