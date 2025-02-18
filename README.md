# Automated-Bangla-Question-Answering-System-for-Admission-Test-Helpline-in-Bangladesh

A **natural language processing (NLP)** project that enables **question answering (QA) in Bengali (Bangla)** using deep learning models. This system processes text passages and extracts or generates accurate answers to user queries in Bengali.

## Features
* Supports extractive question answering (finding answers from a given text).
* Utilizes pre-trained transformer models such as mBERT, BanglaBERT, or T5.
* Implements tokenization, text preprocessing, and embedding techniques for Bengali.
* Fine-tuned on Bengali QA datasets for improved accuracy.
* Provides an interactive interface or API for testing queries.

## Tools and Libraries
- **Programming Language:** Python
- **NLP Frameworks:** Hugging Face Transformers, TensorFlow/PyTorch
- **Libraries:** NumPy, Pandas, Scikit-learn, NLTK
- **Pretrained Models:** BanglaBERT, mBERT, T5

## How It Works
1. Input: User provides a question and a reference text (context).
 
2. Processing:
  * The model tokenizes and processes the text.
  * It uses transformer attention mechanisms to find relevant parts.
    
3. Output: The system returns the most probable answer span or generates an answer.
