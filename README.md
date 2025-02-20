# Document Chunk Classification using Gemini & DistilBERT

## 📌 Project Overview
Classifying document chunks using **Gemini** and **DistilBERT**, followed by performance evaluation.

## 🏗️ Workflow
1. **Data Preprocessing**: Extract document chunks and map them to categories.
2. **Classification**:
   - DistilBERT: Use `DistilBertForSequenceClassification`.
   - Gemini: Use Gemini API for classification.
3. **Evaluation**: Compare accuracy

## 🛠️ Installation & Setup
### Prerequisites:
```bash
pip install torch transformers pandas numpy matplotlib seaborn gemini-api-sdk
