# 📰 News Topic Classifier Using BERT

## Objective
Fine-tune a BERT model to classify news headlines into four categories using the AG News dataset.

## Dataset
- **Source**: [AG News (Hugging Face)](https://huggingface.co/datasets/ag_news)
- **Classes**: World, Sports, Business, Sci/Tech

## Methodology
- Tokenized text using `bert-base-uncased`
- Fine-tuned BERT model using Hugging Face Transformers
- Evaluated with accuracy and F1-score
- Trained on GPU for faster convergence

## Results
- **Accuracy**: ~95%
- **Model**: BERT fine-tuned for 3-5 epochs

## How to Run
1. Install dependencies:
   ```bash
   pip install transformers datasets scikit-learn
