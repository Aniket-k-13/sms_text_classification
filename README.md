# 📩 SMS Spam Detector — Neural Network Text Classifier

This project uses a TensorFlow neural network to classify SMS messages as:
- **Ham** → normal message
- **Spam** → promotional or fraud message

Part of the **FreeCodeCamp Machine Learning Certification** ✅

---

## 🧠 Model Capabilities
✔ Tokenizes and pads SMS text  
✔ Learns spam patterns from training data  
✔ Returns:
- Spam probability (0 → ham, 1 → spam)
- Predicted label

#colab NoteBook 
https://colab.research.google.com/drive/1landsR_8ufPF-aty5jLpwMO0yhxpXH99?usp=sharing
---

## ✅ Required Function
```py
predict_message("hello")
→ [0.03, "ham"]
All FreeCodeCamp tests passed successfully ✅
```

🔧 Data
Provided in the project:

train-data.tsv → for model training

valid-data.tsv → for testing predictions

🛠 Tech Stack
TensorFlow / Keras

Pandas

NumPy

Tokenizer + Word Embedding

Neural Network classifier

🔒 Model Performance
High accuracy on unseen test messages ✅
Robust against common spam word tricks ⚡

👤 Author
Aniket Khandare


