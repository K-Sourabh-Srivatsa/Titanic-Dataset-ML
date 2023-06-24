# Titanic Survival Prediction Model

This repository contains an ML model that predicts whether a person survived or not based on the Titanic dataset.

## Execution Instructions

To run the model, follow these steps:

1. Create a Google Colab account and open Google Colab.
2. Upload the IPython Notebook (`Project_on_titanic_dataset.ipynb`) file to your Google Drive.
3. In Google Colab, open the uploaded IPython Notebook.
4. Upload the training dataset (`titanic_train.csv`) and the test dataset (`titanic_test.csv`) to Google Colab.
5. Select "Runtime" from the top menu and choose "Run All" to execute the notebook.

## Dataset Files

The following dataset files are required:

- `titanic_train.csv`: Training dataset containing features and survival labels.
- `titanic_test.csv`: Test dataset containing features for prediction.

## Usage

After running the notebook, you will obtain predictions for the survival status of passengers in the test dataset. The model's accuracy can be assessed by the weighted average of precision, recall, and F1-score.

## Accuracy

The model achieves an accuracy of 0.80 on the Titanic dataset, as measured by the weighted average.

## Additional Information

- Dependencies: The notebook requires Python 3 and the following libraries: NumPy, Pandas, matplotlib, Seaborn.
- Model Training: The model was trained using a Logistic Regression.
- Results and Evaluation: Further evaluation metrics, such as precision, recall, and F1-score, can be found in the classification report.

