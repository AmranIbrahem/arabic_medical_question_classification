🧠 Arabic Medical Question Classification (AI + NLP)
<p align="center">
  <b>Building an intelligent system to classify Arabic medical questions using Machine Learning & Deep Learning</b>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/NLP-Arabic-blue"/>
  <img src="https://img.shields.io/badge/AI-Medical-red"/>
  <img src="https://img.shields.io/badge/Models-ML%20%2B%20DL-green"/>
  <img src="https://img.shields.io/badge/Dataset-84K-orange"/>
</p>
---
🚀 Overview
This project focuses on building a high-performance NLP system to classify Arabic medical questions into 16 specialized medical categories.
💡 The system is designed to be used in:
Medical chatbots
Telemedicine platforms
AI healthcare assistants
---
🏗️ System Pipeline
```mermaid
flowchart LR

A[Raw Arabic Question] --> B[Text Cleaning]
B --> C[Normalization]
C --> D[Tokenization]
D --> E[Feature Extraction]
E --> F[ML / DL Models]
F --> G[Predicted Category]
```
---
📊 Dataset
📌 Source: Hugging Face (Shifaa Dataset)
📦 Size: 84,422 questions
🧾 Categories: 16 medical specialties
🌍 Language: Arabic (MSA + Dialect)
---
⚙️ Models & Approaches
🔹 Traditional ML
Logistic Regression
SVM
Random Forest
Naive Bayes
🔹 Deep Learning
CNN
BiLSTM
CNN-BiLSTM
🔹 Transformer Model
AraBERT (Pretrained Arabic Model)
---
📈 Results
Model	Accuracy	F1 Score
Logistic Regression	XX%	XX
SVM	XX%	XX
CNN	XX%	XX
BiLSTM	XX%	XX
AraBERT	⭐ Best	⭐ Best
> 📌 AraBERT achieved the best performance across all evaluation metrics.
---
🔍 Key Challenges
⚠️ Class Imbalance
⚠️ Duplicate Data (~29K samples)
⚠️ Arabic text complexity (diacritics, dialects)
---
🧠 Key Contributions
✔️ Large-scale Arabic medical dataset processing  
✔️ Comparison between ML, DL, and Transformer models  
✔️ Handling real-world noisy Arabic data  
✔️ Building a scalable NLP pipeline
---
💡 Real-World Applications
🏥 Smart Medical Chatbots
📞 Automated Patient Support Systems
🧑‍⚕️ Medical Question Routing Systems
🤖 AI Diagnostic Assistants
---
🛠️ Tech Stack
Python
TensorFlow / Keras
Scikit-learn
HuggingFace Transformers
Pandas / NumPy
---
🚀 How to Run
```bash
pip install -r requirements.txt
```
```bash
jupyter notebook arabic_medical_question_classification.ipynb
```
---
🧬 Future Improvements
Fine-tune larger Arabic LLMs
Deploy as REST API (FastAPI / Laravel API bridge)
Integrate with chatbot systems
Build real-time inference system
---
👨‍💻 Author
Amran Ibrahem  
AI Engineer | NLP Specialist | Backend Architect
---
⚡ Final Note
> This project demonstrates real-world application of AI in healthcare using Arabic NLP.  
> It bridges the gap between research and production systems 🚀
