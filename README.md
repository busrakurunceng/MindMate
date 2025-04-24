# 🧠 MindMate: AI-Powered Mental Health Companion

**MindMate** is an AI-based mental health project designed to support psychological well-being through intelligent analysis of textual, behavioral, and biometric data. Developed as a graduation project in Computer Engineering, MindMate focuses on the detection and classification of depression, anxiety, and their subtypes using state-of-the-art NLP and machine learning techniques.

---

## 🚀 Project Goals

- Detect and classify mental health conditions using AI.
- Analyze social media data, wearable signals, and time-based behaviors.
- Explore Zero-Shot Learning and Large Language Models for emotion and diagnosis prediction.
- Recommend personalized content like meditation and blogs based on mental state.

---

## 🧩 Features

- **Multilingual Dataset**  
  Curated and labeled Turkish and English text data from Reddit, YouTube, and Ekşi Sözlük. Includes:
  - 2,745 depression entries
  - 830 panic attacks
  - 866 social anxiety
  - 43 agoraphobia
  - 65 phobias
  - 40 dysthymia
  - 118 general anxiety
  - 70k+ sentences from YouTube, filtered to 55k

- **Language Models Used**  
  - **LLaMA** for text classification
  - **GPT-4o** for meta-prompting and structured diagnosis
  - **Med-Gemini** for healthcare-specific insights
  - **Helsinki-NLP** for English to Turkish translation

- **Zero-Shot & Structured Prompting**  
  Uses Zero-Shot Learning to classify texts into anxiety subtypes (social anxiety, panic, phobia, agoraphobia, selective mutism) without task-specific training.  
  Structured prompts based on **DSM-5** criteria guide LLM responses.

- **Wearable Data Integration**  
  Achieved up to **93% accuracy** in detecting mental health conditions using data from heart rate, sleep, and activity sensors.

- **Time & SAT Data**  
  Behavioral patterns across time and subjective assessment tests are being integrated to improve user modeling.

- **Emotion Analysis (In Progress)**  
  Planned support for analyzing emotions from text, audio, and video sources.

---

## 🧪 Models and Techniques

- Classification Models: Logistic Regression, Decision Tree, Random Forest, SVM, TabNet, XGBoost, Neural Networks
- NLP Techniques: Sentiment analysis, LLM classification, multilingual processing
- Tools: PyTorch, Hugging Face, LangChain, OpenAI, Kaggle

---

## 📂 Dataset Overview

| Source        | Language | Type     | Data Count |
|---------------|----------|----------|------------|
| Reddit        | EN       | Text     | ~10,000+   |
| YouTube       | TR       | Comments | 70,000 → 55,000 |
| Ekşi Sözlük   | TR       | Posts    | ~4,700+    |
| Kaggle        | EN       | Wearable | Public     |

Data labeling used LLaMA and Med-Gemini. English datasets were translated to Turkish using Helsinki NLP.

---

## 📌 Status

This repository is **actively under development**.  
🔧 **Codes will be included partly in GitHub soon.**  
Stay tuned for updates on Zero-Shot applications, chatbot integration, emotion detection, and more.

---

## 🤝 Acknowledgments

This project builds on open-source tools and public datasets. Special thanks to the contributors of LLaMA, Hugging Face, OpenAI, Kaggle, and Helsinki NLP.

---

## 📬 Contact

For collaboration, mentorship, or questions, feel free to open an issue or connect via GitHub.

---

