# Spam Detection Model

This repository contains a Python script for building a simple spam detection model using Natural Language Processing (NLP) techniques. The model is implemented using the scikit-learn library and utilizes the Multinomial Naive Bayes algorithm.

## Prerequisites

Before running the code, make sure you have the following libraries installed:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `nltk`
- `scikit-learn`

## Dataset

The code assumes the presence of a dataset file named spam.csv containing SMS messages labeled as "ham" (non-spam) or "spam." You can replace this dataset with your own, making sure it has two columns: v1 for labels and v2 for text messages.

## Usage
1. Clone this repository:
`
git clone https://github.com/your-username/spam-detection.git <br>
`
`
cd spam-detection
`
2. Run the Python script:
`
python spam_detection.py
`
3. The script will load the dataset, preprocess it, train the spam detection model, and display performance metrics such as accuracy, confusion matrix, and classification report. The trained model will be saved as model.sav.

## Results

After running the script, you will see the following output:
1. Model train score
2. Model test score
3. Confusion matrix heatmap
4. Classification report