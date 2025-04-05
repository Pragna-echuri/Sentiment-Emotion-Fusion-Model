# Sentiment-Emotion-Fusion-Model
- Multi-Modal Emotion Recognition through Text and Facial Expression

 ### “What if AI could understand how you feel—not just by what you say, but how you look?”
EmotionFusion bridges the gap between what we express in words and what our face reveals, creating a smarter, more empathetic AI through a fusion of Natural Language Processing and Facial Emotion Recognition.
Think of it as an AI that not only listens to your words but watches your expressions, understands your mood, and learns how you feel—like your digital emotional diary.

- 🎭 **Facial Emotion Recognition** using CNN and pre-trained FER models
- 🧠 **Text-based Emotion Classification** using DistilBERT (or BERT)
- 📊 **Sentiment Trend Analysis** over time
- 🔁 **Real-time Detection** via webcam or input text
- 🧾 **Emotion Logging** and visualization (optional: AI diary format)

  
## 🧪 Model Training

### 1. **Text Emotion Model**
- Dataset: [GoEmotions](https://github.com/google-research/google-research/tree/master/goemotions)
- Preprocessing: Tokenization with HuggingFace tokenizer
- Model: DistilBERT fine-tuned for 6 core emotions

### 2. **Facial Emotion Model**
- Dataset: FER2013 or FER+  
- Preprocessing: Grayscale conversion, face cropping via Haar Cascades or MTCNN
- Model: Custom CNN or pre-trained FERNet model

---

## 📊 Outputs

- Emotion prediction labels with confidence scores
- Emotion trend graphs (day/week/month)
- Combined emotion state from both modalities

---

## 🧠 Core Emotions (6-Class)

- 😄 **Happy**
- 😢 **Sad**
- 😠 **Angry**
- 😨 **Fear**
- 😐 **Neutral**
- 😲 **Surprised**

---

## 📝 Future Work

- Add multilingual emotion detection
- Emotion-based recommendation engine
- Expand emotion classes (20+)
- Mobile app integration

---

## 🤝 Contributions

Feel free to open issues or submit pull requests. Let’s build an emotionally aware AI together!

---
