# alzheimers-speech-detection
Machine learning models for early Alzheimer's detection from spontaneous speech using the ADReSSo21 dataset
# alzheimers-speech-detection

Machine learning models for early Alzheimer's disease detection using spontaneous speech transcripts.

This project evaluates classical NLP models on the ADReSSo21 dataset to classify Alzheimer's disease from speech transcripts.

## Dataset

ADReSSo21 Challenge Dataset  
https://luzs.gitlab.io/ADReSSo-2021/

The dataset contains speech recordings and transcripts from participants describing the Cookie Theft picture.

The task is binary classification:

Alzheimer's Disease (AD) vs Control (CN)

---

## Method

Text preprocessing
TF-IDF feature extraction
Classification models:

• Logistic Regression  
• Linear SVM  

Repeated cross-validation is used to obtain stable estimates of performance.

---

## Experiment Results

| Model | Balanced Accuracy |
|------|------------------|
| Logistic Regression | 0.735 |
| Linear SVM | **0.785** |

Results show that TF-IDF combined with Linear SVM provides strong baseline performance for Alzheimer's detection from speech transcripts.

---

## Repository Structure

```
alzheimers-speech-detection

notebooks/
data/
results/

README.md
requirements.txt
```
