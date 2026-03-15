# Multi-Task-News-Intelligence-System


Multi-Task NLP System using ML, Deep Learning and Transformers
Abstract
This project presents a Multi‑Task Natural Language Processing (NLP) system capable of performing
three major NLP tasks: Text Classification, Named Entity Recognition (NER), and Text Summarization.
The system integrates Machine Learning, Deep Learning, and Transformer‑based models within a single
application using a Streamlit interface. Users can input text, select the NLP task, and choose the model
family. The system processes the text and produces predictions or summaries in real time.
Introduction
Natural Language Processing enables computers to understand and process human language.
With the growth of digital text data, automated text analysis has become essential. This project
demonstrates how multiple NLP techniques can be integrated into a unified system to handle different
text analysis tasks such as classification, entity recognition, and summarization.
Objectives

• Build a multi‑task NLP application
• Implement classification, NER, and summarization tasks
• Compare ML, Deep Learning, and Transformer models
• Develop an interactive Streamlit interface
• Log system usage and predictions

Technologies Used

Python – Programming language
Streamlit – Web interface
PyTorch – Deep learning models
Transformers (HuggingFace) – Pretrained NLP models
Scikit‑Learn – Machine learning algorithms
Pandas & NumPy – Data processing

System Architecture
The system contains five main components: User Interface, Model Selection Layer,
NLP Processing Layer, Model Inference Layer, and Logging System. The user logs into the application,
selects the NLP task and model type, enters input text, and receives results produced by the selected model.
Model Implementation
Machine Learning Models:
TF‑IDF + Logistic Regression for classification, rule‑based patterns for NER,
and TF‑IDF extractive summarization.

Deep Learning Models:
BiLSTM classifier for text classification, BiLSTM sequence tagging for NER,
and Seq2Seq LSTM for summarization.

Transformer Models:
BERT for classification and NER, and BART for abstractive summarization.
Results
The system successfully performs classification, entity recognition, and summarization tasks.
Transformer models generally produce better contextual understanding and more accurate results compared
to traditional models.
Conclusion
This project demonstrates the integration of multiple NLP models into a single platform.
The system allows users to compare different modeling techniques and perform various NLP tasks in real time.
Future improvements may include multilingual support, improved datasets, and cloud deployment.
