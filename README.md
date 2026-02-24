# Multimodal-Fake-News-Detection
Text and Image based Fake News Detection using DistilBERT, ELECTRA and ResNet

# Multimodal Fake News Detection using Text and Image Fusion

## 📌 Project Overview
This project focuses on detecting fake news by combining both textual and visual information.
Text embeddings are extracted using DistilBERT and ELECTRA, while image embeddings are obtained using ResNet architectures.
The fused features are classified using a Multi-Layer Perceptron (MLP).

## 🧠 Models Used
- Text: DistilBERT, ELECTRA
- Image: ResNet18, ResNet34, ResNet50
- Classifier: MLP (Dense Neural Network)
- Dimensionality Reduction: PCA (300 components)

## 📊 Dataset
- ~30,000 multimodal samples
- Features reduced using PCA for efficiency

## 📈 Results
- Best Accuracy: **99.88%**
- Best Model: **ELECTRA + ResNet34 + MLP**

## 🛠 Tools & Technologies
- Python
- TensorFlow / Keras
- Scikit-learn
- CUDA GPU
- Google Colab / Jupyter Notebook

## 👨‍💻 Contributor
- ** Pothuri Indraneel ** – MLP implementation, training, evaluation

## 🚀 Future Work
- End-to-end multimodal transformers
- Real-time fake news detection system
