
# 📧 Email Spam Detection using Zero-Shot Learning and BERT

This project presents an innovative approach to email spam detection by combining **Zero-Shot Learning** with advanced **Natural Language Processing (NLP)** techniques, specifically using **FLAN-T5** and **BERT**. The goal is to create a robust spam detection system that does **not rely on large labeled datasets** or **frequent retraining**, making it highly scalable and adaptable to evolving spam tactics.

## 🚀 Project Overview

Traditional spam detection models often struggle with:
- Class imbalance
- Data scarcity
- Rapidly evolving spam patterns

To address these limitations, this project introduces a **Zero-Shot Learning** framework using **FLAN-T5** for classification and **BERT** for email content preprocessing. This approach enhances adaptability and performance in unseen or adversarial email environments.

### 🛠️ Key Technologies
- `BERT` for feature extraction and semantic understanding
- `FLAN-T5` for Zero-Shot classification
- `Jupyter Notebooks` for experimentation and analysis

## 📂 Project Structure

```
📁 Email-Spam-Detection-ZeroShot
├── EDA.ipynb           # Exploratory Data Analysis
├── Model.ipynb         # Model building and evaluation
├── README.md           # Project documentation
└── spam_ham_dataset_csv.zip    # dataset
```

## 📊 Exploratory Data Analysis (`EDA.ipynb`)

This notebook includes:
- Dataset shape and structure overview
- Missing data checks
- Label distribution (spam vs. ham)
- Text length analysis
- Word clouds for spam and ham emails

## 🤖 Modeling and Evaluation (`Model.ipynb`)

This notebook covers:
- Preprocessing using **BERT**
- Classification using **FLAN-T5** in a **Zero-Shot Learning** setup
- Model evaluation and insights on performance

## 📌 Highlights

- ✅ No retraining required for new spam patterns  
- ✅ Reduced dependency on labeled data  
- ✅ Adaptable to dynamic spam environments  
- ✅ Scalable and lightweight approach for real-world applications  
## 📄 Project Report

You can read the full technical report of this project on arXiv:

**🔗 [Advancing Email Spam Detection: Leveraging
Zero-Shot Learning and Large Language Models
](https://arxiv.org/pdf/2505.02362)**

## 🛠️ Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/saeidshirazi/Email-Spam-Detection-zeroshot
   cd email-spam-detection-zeroshot
   ```



2. **Run the notebooks**:
   ```bash
   jupyter notebook
   ```

> 📌 **Note**: Ensure you have internet access to load the FLAN-T5 and BERT models from HuggingFace.

## 📬 Conclusion

This project demonstrates the potential of **Zero-Shot Learning** combined with **state-of-the-art NLP models** for scalable and efficient email spam detection. The integration of BERT and FLAN-T5 offers a flexible and data-efficient alternative to traditional supervised learning methods.

---

Feel free to contribute or raise an issue if you find improvements or bugs!
