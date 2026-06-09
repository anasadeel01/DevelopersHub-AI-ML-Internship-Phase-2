# AI/ML Engineering Internship Tasks

## About This Repository

This repository contains my solutions for the AI/ML Engineering Advanced Internship Tasks assigned by DevelopersHub Corporation.

I completed these projects to gain practical experience in Natural Language Processing, Machine Learning Pipelines, and Retrieval-Augmented Generation (RAG) systems. The focus was not only on building models but also on understanding the complete workflow from data preprocessing to deployment.

---

# Task 1 – News Topic Classification using BERT

## Objective
The goal of this project was to classify news articles into different categories using a transformer-based model.

## Dataset
AG News Dataset

## Approach
- Loaded and explored the dataset
- Applied text tokenization using BERT tokenizer
- Fine-tuned the `bert-base-uncased` model
- Evaluated performance using Accuracy and F1 Score
- Built a simple Gradio interface for testing predictions

## Learning Outcome
This task helped me understand transfer learning, transformer architectures, and text classification workflows.

---

# Task 2 – Customer Churn Prediction Pipeline

## Objective
To develop a reusable machine learning pipeline that predicts whether a customer is likely to churn.

## Dataset
Telco Customer Churn Dataset

## Approach
- Data cleaning and preprocessing
- Handling missing values
- Feature scaling and encoding
- Building Scikit-learn Pipelines
- Training Logistic Regression and Random Forest models
- Hyperparameter tuning using GridSearchCV
- Exporting the final pipeline using Joblib

## Learning Outcome
This project strengthened my understanding of production-ready machine learning workflows and model deployment practices.

---

# Task 4 – Context-Aware Chatbot using RAG

## Objective
To create a chatbot capable of retrieving information from documents while maintaining conversation context.

## Approach
- Document loading and chunking
- Generating embeddings
- Creating a vector database using ChromaDB
- Implementing retrieval-based question answering
- Adding conversation memory
- Building a simple Streamlit interface

## Learning Outcome
This project provided hands-on experience with LangChain, vector databases, embeddings, and Retrieval-Augmented Generation (RAG).

---

# Technologies Used

- Python
- Scikit-learn
- Hugging Face Transformers
- PyTorch
- LangChain
- ChromaDB
- Streamlit
- Gradio
- Pandas
- NumPy

---

# Repository Structure

Task1_BERT_News_Classifier.ipynb

Task2_Customer_Churn_Pipeline.ipynb

Task4_RAG_Chatbot.ipynb

README.md

requirements.txt

---

# Final Remarks

These projects were completed as part of the AI/ML Engineering Internship assignment. Throughout the process, I focused on understanding the concepts, implementing the required techniques, and documenting the workflow clearly.

The work helped me gain practical experience in machine learning, natural language processing, and modern AI application development.
