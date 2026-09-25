# spam-email-classifier
Spam classifier using Naive Bayes and SVM
# Spam Email Classifier

A machine learning project that detects spam messages using Naive Bayes and SVM.

## What it does
Takes a message (SMS or email text) and predicts whether it is **spam** or **ham** (normal).

## How it works
1. Text is converted into numbers using **TF-IDF**.
2. Two models are trained and compared: **Naive Bayes** and **Support Vector Machine (SVM)**.
3. The better model (SVM) is used for predictions.

## Results
| Model | Accuracy | Spam Recall |
|---|---|---|
| Naive Bayes | 98% | 84% |
| SVM | 99% | 93% |

## Tech used
- Python
- pandas
- scikit-learn
- Gradio (for the demo app)

## Dataset
[SMS Spam Collection Dataset](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)

## How to run
1. Open `spam_classifier.ipynb` in Google Colab.
2. Run all cells in order.
3. Try your own messages in the last cell.
