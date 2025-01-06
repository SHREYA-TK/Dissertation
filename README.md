# Emotion Detection And Analysis of Differernt Mental Health Conditions

In recent years, the field of Natural Language Processing (NLP) has made significant advancements in understanding and analyzing human emotions from text. Emotion detection plays a crucial role in various applications, particularly in mental health analysis, where identifying emotional states from text-based interactions can provide valuable insights into an individual's psychological well-being. Given the increasing reliance on digital communication, accurately detecting and quantifying emotions in text is essential for applications such as sentiment analysis, mental health monitoring, and AI-driven psychological support systems.

Research question- "How effectively can deep learning models detect and quantify multiple emotions in text, and how do they compare to traditional machine learning models in terms of performance for emotion analysis in mental health-related contexts?"

This project focuses on detecting and quantifying multiple emotions from text using traditional machine learning and deep learning models. The GoEmotions dataset (58,000 Reddit comments with 27 emotions + neutral label) was used to evaluate model performance, particularly in mental health applications.

Preprocessing Techniques used: Tokenization, Lemmatization, Stopword Removal, TF-IDF (ML models), Class Weighting, Threshold Optimization

Models Implemented:


Traditional ML: Ridge Classifier, Logistic Regression

Deep Learning: BERT, DistilBERT (transformers-based models)

<img width="545" alt="image" src="https://github.com/user-attachments/assets/faccdd23-ffa8-407d-b4f1-b67ea1b09f56" />

Key insights:


✔ DistilBERT performed best with 0.55 F1-score, followed by BERT (0.51).

✔ Traditional ML models had lower precision, highlighting their limitations in emotion detection.

✔ Threshold tuning improved classification balance across emotions.


Applications & Future Work:

✔ AI Chatbots for Mental Health (e.g., Woebot, Wysa)

✔ Social Media Monitoring for Crisis Detection

✔ Fine-tuning transformer models for improved emotion detection

✔ Real-time sentiment analysis tools
