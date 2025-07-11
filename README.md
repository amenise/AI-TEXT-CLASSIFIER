# AI-TEXT-CLASSIFIER
# 🧠 AI Text Classifier

A lightweight NLP-powered web app that automatically classifies user-inputted text into topics like **Tech**, **Business**, **Health**, **Education**, and **Sports** using a trained machine learning model.

Built with 💡 Scikit-learn, 🧰 TF-IDF, and 🎨 Gradio — perfect for beginners learning AI + NLP!

---

## 🚀 Features

- 🌐 Web-based interface (no installation needed)
- 🧠 ML model trained on example sentences
- 🔤 Real-time text classification
- 📚 Customizable dataset and labels
- 💬 Built using Python, Scikit-learn, and Gradio

---

## 📊 Categories Supported

- Tech  
- Business  
- Health  
- Education  
- Sports  

You can easily expand it to include more topics like Entertainment, Finance, AI, etc.

---

## 🧪 Try It Online

[🔗 Launch the app](https://your-gradio-link.gradio.live) *(Replace with your link)*  
Paste a sentence like:  
- *"Python is great for AI development."* → **Tech**  
- *"Messi scored a goal last night."* → **Sports**

---

## 🛠️ How It Works

1. Preprocesses text using **TF-IDF vectorization**
2. Trains a **Naive Bayes classifier** on labeled examples
3. Uses **Gradio** for a simple, shareable web UI

---

## 🧰 Dependencies

```txt
gradio
scikit-learn
