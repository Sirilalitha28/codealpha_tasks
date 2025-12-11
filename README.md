
# 1️⃣Language Translation Tool**

```markdown
# 🌐 CodeAlpha – Language Translation Tool

This project is developed as part of the **CodeAlpha Artificial Intelligence Internship**.

## 📌 Task Overview
The goal of this project is to build a **Language Translation Tool** that:
- Allows users to enter text
- Select source and target languages
- Translates the text using a translation API
- Displays translated output instantly

## 🧰 Tech Stack
- Python  
- Streamlit  
- deep-translator (Google Translate wrapper)

## 🚀 Features
- Multi-language translation support  
- Clean and simple UI  
- Edge case handling (empty text, same language selected)  
- Real-time translation  

## 📂 Project Structure
```

CodeAlpha_LanguageTranslationTool/
│── app/
│   └── main.py
│── src/
│   └── translator.py
│── requirements.txt
└── README.md

````

## ⚙️ Installation & Usage
```bash
pip install -r requirements.txt
streamlit run app/main.py
````

## 📝 How It Works

1. User enters text in the input box
2. User selects source and target languages
3. Backend uses `deep-translator` to perform translation
4. Output is displayed in the UI

# 2️⃣ FAQ Chatbot**

```markdown
# 🤖 CodeAlpha – FAQ Chatbot

This chatbot project is part of the **CodeAlpha Artificial Intelligence Internship**.

## 📌 Task Overview
The project aims to:
- Read FAQ data
- Preprocess questions using TF-IDF
- Match user queries using cosine similarity
- Return the best answer from the dataset

## 🧰 Tech Stack
- Python  
- Streamlit  
- Scikit-Learn  
- Pandas  
- NLTK  

## 🚀 Features
- Real-time query matching  
- Simple, intuitive chatbot interface  
- Accurate response retrieval using similarity scores  
- Lightweight and easy to deploy  

## 📂 Project Structure
````

CodeAlpha_FAQChatbot/
│── app/
│   └── main.py
│── src/
│   └── chatbot.py
│── data/
│   └── faqs.csv
│── requirements.txt
└── README.md

````

## ⚙️ Installation & Usage
```bash
pip install -r requirements.txt
streamlit run app/main.py
````

## 📝 How It Works

1. FAQ questions stored in CSV
2. TF-IDF vectorizer builds feature vectors
3. User query transformed and compared to all FAQs
4. Best match answer returned

---

# 3️⃣ Object Detection & Tracking**

```markdown
# 🎯 CodeAlpha – Object Detection & Tracking

This computer vision project is part of the **CodeAlpha Artificial Intelligence Internship**.

## 📌 Task Overview
Build a real-time system capable of:
- Detecting objects using YOLO  
- Displaying bounding boxes  
- Assigning unique tracking IDs  
- Running live on webcam feed  

## 🧰 Tech Stack
- Python  
- OpenCV  
- NumPy  
- (Supports YOLOv3 if weights are added)

## 🚀 Features
- Real-time object detection  
- Box rendering and label display  
- Simple ID tracking logic  
- Configurable to support full YOLO models  

## 📂 Project Structure
````

CodeAlpha_ObjectDetectionTracking/
│── app/
│   └── main.py
│── src/
│   └── detector.py
│── models/
│   ├── yolov3.cfg
│   ├── yolov3.weights (not included)
│   └── coco.names
│── requirements.txt
└── README.md

````

## ⚙️ Installation & Usage
```bash
pip install -r requirements.txt
python app/main.py
````

## 📸 How It Works

1. Webcam feed captured using OpenCV
2. YOLO model loads network layers
3. Frame-by-frame detection performed
4. Basic centroid/IOU tracking assigns IDs

```
