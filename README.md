# 🎓 AI-Powered College Chatbot (PyTorch)

An intelligent contextual chatbot developed using PyTorch to assist students, staff, and faculty with real-time query handling in a college environment.

This chatbot uses Natural Language Processing (NLP) and a Feed Forward Neural Network to understand user queries and provide relevant responses efficiently.

---

## 🚀 Features

* 🤖 Context-aware chatbot using NLP techniques
* 📚 Handles academic and administrative queries
* ⚡ Fast and efficient response generation
* 🧠 Built using a Feed Forward Neural Network (2 hidden layers)
* 🔄 Easily customizable using `intents.json`
* 🖥️ Simple and user-friendly interaction system

---

## 🛠️ Technologies Used

* Python
* PyTorch
* Natural Language Processing (NLP)
* NLTK
* Machine Learning

---

## 🧠 Model Architecture

* Feed Forward Neural Network
* Input Layer → 2 Hidden Layers → Output Layer
* Bag-of-Words approach for text preprocessing

---

## 📂 Project Structure

```
├── train.py        # Model training script
├── chat.py         # Chatbot interaction script
├── model.py        # Neural network architecture
├── intents.json    # Training data (patterns & responses)
├── data.pth        # Trained model
```

---

## ⚙️ Installation & Setup

### 1️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 2️⃣ Activate Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install torch nltk
```

### 4️⃣ Download NLTK Data

```python
import nltk
nltk.download('punkt')
```

---

## ▶️ Usage

### Train the Model

```bash
python train.py
```

### Run the Chatbot

```bash
python chat.py
```

---

## 🎯 Objective

To streamline communication within the college ecosystem by automating responses to frequently asked questions and reducing manual workload.

---

## 📈 Outcome

* Improved response efficiency
* Reduced workload for staff
* Enhanced user experience through automation

---

## 🔧 Customization

Modify the `intents.json` file to:

* Add new query patterns
* Define chatbot responses
* Expand chatbot capabilities

After making changes, retrain the model:

```bash
python train.py
```

---

## 🔍 My Contribution

* Customized chatbot for college interaction system
* Designed real-world intents and responses
* Implemented NLP-based query handling using PyTorch
* Improved usability and response accuracy

---

## 🔮 Future Enhancements

* 🌐 Web-based chatbot interface
* 📱 Mobile application integration
* 🎤 Voice-based chatbot
* 🤖 Advanced deep learning models for better accuracy

---

## 🙋‍♀️ Author

**Manjusri K**

* Aspiring Software Developer | AI Enthusiast

🔗 GitHub: https://github.com/manjusrikesavan

