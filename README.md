# 🥗 Food Recognition and Calorie Estimation using Vision Transformers (ViT)

## 📌 Overview

This project implements a **Food Recognition and Calorie Estimation System** using **Vision Transformers (ViT)**. Leveraging the power of transformer-based architectures, the model classifies food images into their respective categories and estimates calorie values based on the predicted food item.

The project demonstrates the effectiveness of transfer learning using pretrained Vision Transformer models for image classification tasks and showcases an end-to-end deep learning pipeline for food recognition.

---

## 🎯 Problem Statement

Food recognition is an important computer vision task with applications in healthcare, nutrition tracking, and dietary monitoring. Traditional CNN-based approaches often struggle to capture long-range relationships within images. This project explores the use of **Vision Transformers (ViT)** to improve food classification performance and estimate calorie content automatically.

---

## 🚀 Features

- 🥗 Food image classification using Vision Transformers (ViT)
- 🤖 Transfer learning with pretrained transformer models
- 📷 Image preprocessing and augmentation
- 🔍 Prediction on unseen food images
- 🔥 Calorie estimation based on predicted food category
- 📊 Model evaluation using classification metrics

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Torchvision
- NumPy
- Matplotlib
- OpenCV
- Google Colab

---

## 🧠 Model Architecture

The project fine-tunes a pretrained **Vision Transformer (ViT)** model for food image classification.

Key stages include:

- Image Preprocessing
- Data Augmentation
- Transfer Learning
- Vision Transformer Fine-tuning
- Food Classification
- Calorie Estimation

---

## 🔄 Project Workflow

```text
Food Image
      │
      ▼
Image Preprocessing
      │
      ▼
Image Augmentation
      │
      ▼
Vision Transformer (ViT)
      │
      ▼
Food Classification
      │
      ▼
Predicted Food Category
      │
      ▼
Calorie Database Mapping
      │
      ▼
Estimated Calories
```

---

## 📊 Sample Prediction

Example Output:

```
Food Item: Pizza
Estimated Calories: 2248 kcal
```

---

## 📈 Skills Demonstrated

- Computer Vision
- Vision Transformers (ViT)
- Transfer Learning
- Deep Learning
- Image Classification
- PyTorch
- Hugging Face Transformers
- Model Fine-tuning
- Computer Vision Pipelines

---

## 📌 Why Vision Transformers?

Compared to traditional CNNs, Vision Transformers:

- Capture long-range dependencies within images.
- Leverage self-attention mechanisms for feature extraction.
- Achieve state-of-the-art performance on image classification tasks.
- Benefit significantly from transfer learning on pretrained models.

---

## 💡 Future Improvements

- Improve performance using larger food datasets
- Deploy as a web/mobile application
- Portion size estimation using object detection
- Nutritional breakdown (Protein, Carbohydrates, Fats)
- Real-time food recognition using live camera feeds

---

## 📚 Learning Outcomes

This project helped me gain hands-on experience with:

- Vision Transformer architecture
- Transfer Learning
- Hugging Face Transformers
- PyTorch-based model training
- Computer Vision workflows
- Model evaluation and inference
- AI-powered nutrition applications

---

| Model        | CNN                          | Vision Transformer                  |
| ------------ | ---------------------------- | ----------------------------------- |
| Architecture | Convolutional Neural Network | Vision Transformer                  |
| Framework    | TensorFlow/Keras             | PyTorch + Hugging Face              |
| Learning     | Local feature extraction     | Self-attention                      |
| Strength     | Efficient and lightweight    | Better global context understanding |
