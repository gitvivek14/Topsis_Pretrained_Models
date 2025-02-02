<h1>TOPSIS-Based Evaluation of Pretrained Models for Sentence Similarity</h1>

Overview  
This project implements the TOPSIS method to rank pretrained models based on their performance in sentence similarity tasks.

Goal  
The objective is to identify the most effective pretrained model for sentence similarity, considering multiple factors such as:

- Accuracy (Cosine Similarity)
- Inference Time
- Model Size

Dataset & Evaluation  
Three commonly used pretrained models were tested on a set of sentence pairs:

1. BERT (bert-base-uncased)
2. RoBERTa (sentence-transformers/all-roberta-large-v1)
3. SBERT (sentence-transformers/all-MiniLM-L6-v2)

The models were evaluated against the following criteria:  
🔹 Cosine Similarity (A higher score is better)  
⏳ Inference Time (Faster is better)  
💡 Model Size (Smaller is better)

Implementation Steps  
1️⃣ Load the models using the sentence-transformers library  
2️⃣ Calculate sentence similarity scores  
3️⃣ Measure the models' inference time and size  
4️⃣ Normalize the collected data  
5️⃣ Apply the TOPSIS algorithm  
6️⃣ Rank the models based on their overall performance across the different metrics


#Ranking of Pretrained Models for sentence similarity
![output1](https://github.com/user-attachments/assets/14ebc725-b122-4f26-b1b0-c6fb172c79ab)


#Topsis_Ranking_Results.png
![output](https://github.com/user-attachments/assets/a3c9058e-2dd5-4712-8090-26a084f718e4)


Done by : Vivek Arora
Roll no : 102203778
Group : 3C42
