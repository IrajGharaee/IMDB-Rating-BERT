#  IMDB Movie Rating Predictor using DistilBERT

## Overview
This project implements a **text regression model** using **DistilBERT** to predict a movie’s **numerical rating (1–10)** based on its user review text.  
Unlike traditional sentiment analysis that only classifies a review as positive or negative, this project performs **fine-grained rating prediction** — capturing subtle emotional and contextual signals in language.

---

## Key Features
- Built using **Hugging Face Transformers** and **DistilBERT**, a lightweight and efficient version of BERT.  
- Predicts **continuous IMDB ratings (1–10)** instead of binary sentiment.  
- Fine-tuned on the **IMDB review dataset**, with the rating as the regression target.  
- Uses **PyTorch** backend for training and evaluation.  
- Includes preprocessing steps like text cleaning, tokenization, and sequence padding.  

---
