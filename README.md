# cnn-image-classifier
# CNN Image Classification with Keras + Gradio

An end-to-end deep learning project that builds a Convolutional Neural Network (CNN) for image classification using TensorFlow/Keras and deploys it through an interactive Gradio web interface for real-time inference.

This project demonstrates a practical ML workflow — from preprocessing and model training to deployment and user interaction.

---

## 🚀 Features

* CNN-based image classification pipeline
* Training and validation workflow
* Real-time prediction interface
* Clean preprocessing pipeline
* Modular and reproducible structure

---

## 🧠 Project Overview

The system trains a CNN to learn visual features and classify images. The trained model is wrapped in an inference pipeline and exposed through a Gradio interface, allowing users to upload images and instantly receive predictions.

This simulates a lightweight production-style ML deployment.

---

## 🏗 Architecture

The model uses a sequential CNN design:

* Convolution layers → feature extraction
* Max pooling → dimensionality reduction
* Dense layers → classification
* Softmax output → probability predictions

Input normalization ensures stable training and consistent inference behavior.

---

## 📦 Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Gradio

---

## ⚙ Installation

### 1. Clone repository

```bash
git clone https://github.com/your-username/cnn-image-classifier.git
cd cnn-image-classifier
```

### 2. Create virtual environment (recommended)

```bash
python -m venv venv
```

Activate environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶ Usage

### Train the model

```bash
python train.py
```

This will:

* Load dataset
* Preprocess inputs
* Train CNN
* Save trained model

---

### Launch Gradio interface

```bash
python app.py
```

Then open the provided local URL in your browser.

Upload an image → receive classification prediction in real time.

---


## 🎯 Learning Outcomes

* CNN architecture design
* Deep learning training workflow
* Computer vision preprocessing
* Model deployment fundamentals
* ML-to-application integration

---

## 🔮 Future Improvements

* Custom dataset support
* Model versioning
* Performance optimization
* Cloud/container deployment
* Extended evaluation metrics

---

## 🤝 Contributing

Contributions and improvements are welcome. Feel free to fork the repo and submit pull requests.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## ⭐ Acknowledgment

Built as a practical deep learning deployment project to bridge model development and interactive AI systems.
