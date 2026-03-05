 ABUSIVE-TEXT-DETECTION-FOR-WOMEN-USING-MACHINE-LEARNING-AND-DEEP-LEARNING
 DRAVIDIAN_NLP
Classification of Offensive Tamil Text Targeting Women Using Machine Learning and BERT Models

This repository contains the implementation of the research work submitted to the **DravidianLangTech Workshop at ACL 2026**.

The project focuses on detecting **abusive Tamil text targeting women on social media** using traditional Machine Learning models and transformer-based models.



 📌 Problem Statement

Online platforms often contain abusive and misogynistic comments directed toward women.  
Manual moderation is difficult due to the large volume of social media text.

This project aims to automatically classify Tamil comments into:
Abusive
Non-Abusive



 📊 Dataset

Dataset used in this work:

Abusive Tamil Text Targeting Women on Social Media  
DravidianLangTech Shared Task 2026.

Each comment is annotated as:

1 - Abusive  
0 - Non-Abusive



 ⚙️ Methods Used

### Traditional Machine Learning Models
- Logistic Regression
- Support Vector Machine (SVM)
- Multinomial Naïve Bayes
- Random Forest
- Decision Tree

### Deep Learning Model
- BERT (Bidirectional Encoder Representations from Transformers)

---

## 🧹 Text Preprocessing

The following preprocessing steps are applied:

- Removal of emojis
- Removal of special characters
- Text normalization
- Tokenization

---

## 🔎 Feature Extraction

We used **TF-IDF (Term Frequency – Inverse Document Frequency)** to convert text into numerical feature vectors.

---

## 📈 Evaluation Metrics

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🖥 Implementation

Programming Language:
- Python

Libraries Used:
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Transformers (HuggingFace)
- Google Colab

---

## 📊 Results

| Model | Accuracy |
|------|------|
| Logistic Regression | 73% |
| SVM | 76% |
| Random Forest | 73% |
| Naive Bayes | 74% |
| Decision Tree | 65% |
| BERT | **82%** |

BERT achieved the best performance because it captures contextual information in Tamil text.

---

## 📷 Confusion Matrices

Confusion matrices for all classifiers are included in the repository.

---

## 📄 Paper

The research paper is included in this repository.

---

## 👩‍💻 Authors

**Bhuvaneshwari R**  
Department of Computer Science and Engineering  
Kongu Engineering College  

**Dhanushree C**  
Department of Computer Science and Engineering  
Kongu Engineering College  

---

## 📜 License

This project is intended for research and academic purposes.
