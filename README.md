### About Me  
Data Analyst | Product Analytics | Dashboard Development | A/B Testing | Python & BI

I analyze product, user and business data and translate it into clear insights and dashboards.  
Experienced with Power BI, SQL, Python, API integration, and analytics for digital products.

**Location:** Budapest, Hungary  
**Connect:** [LinkedIn](https://www.linkedin.com/in/dariya-baigereyeva-772820261/)

# Project Portfolio  

# Sentiment Analysis on IMDb Reviews (NLP Project with BERT)

This project demonstrates a complete NLP (Natural Language Processing) workflow using a transformer-based model (DistilBERT) to classify the sentiment of movie reviews from the IMDb dataset.  
It was implemented using Python, HuggingFace Transformers, Pandas, and Matplotlib in Google Colab.

## Project Overview
The goal of the project was to:

- Load and explore the IMDb movie reviews dataset  
- Preprocess and truncate text to meet BERT’s token limit  
- Run sentiment predictions using the **DistilBERT** model  
- Visualize sentiment distribution  
- Evaluate model accuracy  

## Dataset
- **Dataset:** IMDb Movie Reviews  
- **Total size:** 50,000 reviews  
- **Train distribution:**  
  - 12,500 negative reviews  
  - 12,500 positive reviews  
- **Labels:**  
  - `0` = Negative  
  - `1` = Positive  

A random subset of **300 reviews** was selected for inference.

## Model Used

I used **DistilBERT**, a lightweight and efficient version of the BERT transformer model, fine-tuned for sentiment analysis:
The model was applied using the HuggingFace `pipeline()`.

## Technologies Used
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Transformers-000000?style=for-the-badge&logo=huggingface&logoColor=yellow" />
  <img src="https://img.shields.io/badge/DistilBERT-0A0A0A?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-0C63CE?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white" />
</p>

## Methodology
### Load IMDb dataset  
Using the `datasets` library.
### Create a 300-review sample  
For fast and meaningful inference.
### Truncate long reviews  
To avoid BERT’s 512-token limit.
### Run sentiment analysis  
Using the DistilBERT pipeline.
### Visualize predictions  
A bar chart showing sentiment distribution.
### Evaluate accuracy  
Compared predictions with true labels.  
**Final accuracy:** **82.6%**

<img width="378" height="446" alt="Снимок экрана 2025-11-16 в 22 00 48" src="https://github.com/user-attachments/assets/b29ae9b7-d588-424b-a53a-fa8b392c8eed" />

## Reproducibility

Random seed: 42  
Train/Validation split: 80/20 (stratified)  
---

### Project : A/B Testing — P2P Banner Conversion Experiment

A full A/B test validation analyzing whether introducing a promotional banner increases conversion to P2P money transfers.

The analysis includes:
- Pre-test homogeneity validation  
- Statistical testing (z-test, significance validation, confidence intervals)  
- Conversion lift calculation  
- Segment analysis and customer personas  
- Actionable product recommendations  

**Key Insights**
- Test group (banner) showed a higher conversion rate than control.  
- Statistical significance confirmed with 95% confidence.  
- Most responsive segments: high-activity users and frequent P2P senders.  
- New users showed lower sensitivity to the banner.

**Technologies Used**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Scipy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
<img src="https://img.shields.io/badge/Statistics-4B8BBE?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/A%2FB_Testing-6E4EAF?style=for-the-badge&logo=scikit-learn&logoColor=white" />


**Source Code**  
[Visit Repo](https://github.com/DariyaB01/Python-projects/blob/main/Baigereyeva_Dariya_P3%20AB%20testing.ipynb)

**Presentation**  
[Download PDF](https://github.com/user-attachments/files/23547029/conversion.and.banner.project.pdf)
<img width="671" height="354" alt="Снимок экрана 2025-11-14 в 13 26 32" src="https://github.com/user-attachments/assets/661188eb-8055-4d6f-9ee5-684c5c1f313c" />
<img width="694" height="384" alt="Снимок экрана 2025-11-14 в 13 26 46" src="https://github.com/user-attachments/assets/14798b33-4016-484d-8a58-179b9b26217f" />

---

## Project : Disneyland Review Sentiment Classification (TF-IDF + PyTorch ANN)

A research-oriented NLP project comparing Logistic Regression and a shallow PyTorch ANN on TF-IDF features for sentiment classification.

Source Code: [disneyland_sentiment_classification](https://github.com/DariyaB01/disneyland_sentiment_classification)

### Key Highlights

- Binary sentiment classification (NEGATIVE / POSITIVE)
- TF-IDF feature engineering (10,000 features, 1–2 ngrams)
- Logistic Regression baseline vs PyTorch ANN
- Class imbalance handling (~83% positive)
- Quantitative evaluation (Macro F1, Confusion Matrix)
- Overfitting analysis

### Technologies Used

`Python` `PyTorch` `Scikit-learn` `HuggingFace Datasets`


## Training Curve

<img width="485" height="352" alt="Снимок экрана 2026-02-28 в 17 31 06" src="https://github.com/user-attachments/assets/30d646dd-04e9-497d-8b21-3a4897761ba1" />




