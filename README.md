# Signature Verification: CNN vs. Random Forest

## Project Overview
This project compares traditional Machine Learning and Deep Learning approaches for automated signature verification. The goal is to distinguish between original signatures and forgeries using the Robinreni Signature Dataset.

## Dataset Details
- **Total Images:** 2149
- **Number of Classes:** 128
- **Preprocessing:** Images resized to 64x64 pixels and converted to grayscale.

## Methodology
1. **Random Forest:** Manual feature extraction using Histogram of Oriented Gradients (HOG).
2. **CNN:** Automated feature extraction using a Convolutional Neural Network architecture.

## Results & Performance
| Model | Accuracy | Precision |
| :--- | :--- | :--- |
| Random Forest | 72.33% | 68.95% |
| CNN | 71.16% | 74.86% |

**Conclusion:** Although Random Forest shows slightly higher accuracy, the CNN model provides superior precision, which is crucial for reducing false positives in forgery detection.