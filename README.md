# Fine--Tuning-BERT-on-Kaggle-Dataset🤖

## Project Overview
This project demonstrates how to build a **text classification model** using **pre-trained BERT** (`bert-base-uncased`) on a real-world Kaggle dataset.  
The workflow includes **data preprocessing, tokenization, model building, fine-tuning, and evaluation**. 📝

## Dataset 📂
- **Source:** Kaggle  
- **Used:** IMDB Movie Reviews / Twitter Sentiment Analysis / News Category Dataset / Jigsaw Toxic Comment Classification  
- Already split into **train, validation, and test** sets.

## Key Steps ⚡
1. **Data Preprocessing**  
   - Cleaning text and handling missing values.

2. **Tokenization**  
   - Using `bert-base-uncased` tokenizer.  
   - Texts converted into input IDs and attention masks for BERT.

3. **Model Building**  
   - Using `AutoModelForSequenceClassification`.  
   - Dataset wrapped in a PyTorch Dataset class.

4. **Fine-Tuning**  
   - `Trainer` API with `AdamW` optimizer.  
   - Learning rate: 2e-5, batch size: 16, epochs: 1. 🔧

5. **Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1 Score.  
   - Confusion Matrix visualization. 📊

## Key Learnings 🌟
- Text preprocessing and data cleaning techniques.  
- Tokenization with BERT and input formatting.  
- Fine-tuning pre-trained transformer models for classification.  
- Evaluating model performance using metrics and confusion matrix.

## How to Run ▶️
1. Clone this repository:
   ```bash
   git clone <your-repo-link>
