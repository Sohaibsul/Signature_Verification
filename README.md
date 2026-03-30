# Signature Verification: CNN vs. Random Forest

## Project Description
This project evaluates traditional Machine Learning and Deep Learning techniques for verifying handwritten signatures. It uses the Robinreni Signature Dataset to classify signatures as genuine or forged.

## Dataset Link
You can find the dataset used in this project here: 
[Robinreni Signature Dataset (Kaggle)](https://www.kaggle.com/datasets/robinreni/signature-verification-dataset)

## Methodology
- **Random Forest:** Uses HOG (Histogram of Oriented Gradients) for manual feature extraction.
- **CNN:** A Deep Learning model that automatically extracts spatial features from grayscale images.

## Results & Performance
Below is the visual representation of the model's performance:

![Model Results](./result.png)

| Model | Accuracy | Precision |
| :--- | :--- | :--- |
| Random Forest | 72.33% | 68.95% |
| CNN | 71.16% | 74.86% |

**Conclusion:** CNN provides superior precision, which is crucial for reducing false positives in forgery detection.

**Author:** Sohaib Sulman (24i-8068)
