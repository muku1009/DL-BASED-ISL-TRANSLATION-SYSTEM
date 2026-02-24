

# 🤟 Deep Learning–Based Indian Sign Language (ISL) Translation System

An AI-powered real-time **Indian Sign Language (ISL) Translation System** that bridges the communication gap between the hearing-impaired community and the general public using **Computer Vision** and **Deep Learning**.

This system recognizes ISL hand gestures through a webcam feed and translates them into readable text, with optional speech output for enhanced accessibility.

---

## 📌 About the Project

Indian Sign Language (ISL) is widely used across India, yet digital accessibility tools supporting ISL remain limited. This project aims to build a:

* ⚡ Real-time
* 🎯 Accurate
* 📈 Scalable
* 💡 User-friendly

gesture recognition system capable of identifying:

* ISL Alphabets (A–Z)
* Numbers (0–9)
* Predefined words
* Emergency gestures (help, doctor, pain, stop, etc.)

The system leverages a **Convolutional Neural Network (CNN)** for gesture classification.

---

## 🔍 System Overview

The working flow of the system is:

1. Capture live video input from webcam
2. Detect and extract hand region
3. Preprocess image (resize, normalize, background filtering)
4. Feed processed frame into trained CNN model
5. Predict gesture class
6. Convert prediction into text (and optional speech output)

---

## 🚀 Key Features

* ✅ Real-time webcam gesture recognition
* 🧠 CNN-based deep learning model
* 🖼 Image preprocessing & normalization
* 🔤 Support for alphabets and numbers
* 🚨 Emergency gesture recognition
* 🔊 Optional text-to-speech output
* 🖥 Clean and user-friendly interface
* 📈 Easily scalable to add new gestures

---

## 🧠 Technologies Used

* **Python**
* **TensorFlow / Keras**
* **OpenCV**
* **NumPy**
* **Matplotlib**
* (Optional) **Flask** for deployment

---

## 📂 Dataset

The dataset consists of labeled ISL gesture images.

### Example Dataset Structure

```
dataset/
│
├── A/
├── B/
├── C/
├── 0/
├── 1/
└── emergency/
```

### Dataset Sources

* Custom-collected dataset
* Kaggle ISL datasets
* Self-recorded gesture images

---

## 🧠 Model Training Details

* 🔁 Data Augmentation applied
* 🧱 CNN architecture for classification
* 📉 Loss Function: Categorical Cross-Entropy
* ⚙️ Optimizer: Adam
* 📊 Evaluation Metric: Accuracy

Trained model is saved as:

```
model.h5
```

---

## 📊 Results

* 📈 Training Accuracy: ~98%
* 📊 Validation Accuracy: ~92%
* ⚡ Real-time prediction with minimal latency

The system performs efficiently under normal lighting conditions.

---

## 🎯 Applications

* Assistive communication tool for hearing & speech impaired individuals
* Educational tool for learning ISL
* Smart accessibility systems
* Integration in hospitals, banks, and government offices
* AI-powered public service kiosks

---

## 🏗 Project Structure

```
│── app.py
│── train_model.py
│── model.h5
│── dataset/
│── static/
│── templates/
│── requirements.txt
│── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone <repository-link>
cd <project-folder>
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
python app.py
```

### 4️⃣ Open in Browser (if Flask-based)

```
http://127.0.0.1:5000
```

---

## 🔮 Future Enhancements

* 📝 Sentence formation using NLP
* 🔊 Advanced speech synthesis integration
* 📱 Mobile application deployment
* 🔁 Continuous sign recognition using LSTM
* 🤖 Transformer-based sequence modeling
* 📊 Larger dataset training for improved accuracy
* 🌍 Multi-language translation support

---

## 🤝 Contributing

Contributions are welcome!

To contribute:

1. Fork the repository
2. Create a new branch

```
git checkout -b feature-name
```

3. Commit your changes

```
git commit -m "Add feature"
```

4. Push to your branch

```
git push origin feature-name
```

5. Create a Pull Request

---

## 👩‍💻 Authors

* Muskan
* Srishti Kaur

---

## 📜 License

This project is for academic and research purposes.
You may modify and use it with proper attribution.

---

## 🌟 Final Note

This project demonstrates the practical implementation of **Deep Learning in Accessibility Technology**, promoting inclusive communication through AI-driven solutions.

---

