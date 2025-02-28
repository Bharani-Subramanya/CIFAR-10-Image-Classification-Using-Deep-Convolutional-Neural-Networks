 CIFAR-10 Image Classification Using Deep Convolutional Neural Networks

📌 Overview

This project presents an optimized Deep Convolutional Neural Network (CNN) architecture for image classification on the CIFAR-10 dataset. The model incorporates multiple convolutional and pooling layers, followed by fully connected layers to extract hierarchical features and improve classification accuracy.

The key challenge of overfitting is mitigated using data augmentation and dropout regularization, ensuring better generalization across unseen data.

📂 Dataset

The CIFAR-10 dataset consists of 60,000 color images (32×32 pixels) divided into 10 classes:

✈️ Airplane

🚗 Automobile

🐦 Bird

🐱 Cat

🦌 Deer

🐶 Dog

🐸 Frog

🐴 Horse

🚢 Ship

🚛 Truck



🔥 Model Architecture

The deep CNN model follows a structured pipeline:
1️⃣ Convolutional Layers – Feature extraction2️⃣ Pooling Layers – Dimensionality reduction3️⃣ Batch Normalization – Stabilizes training4️⃣ Dropout Regularization – Prevents overfitting5️⃣ Fully Connected Layers – Classification output

DEEP CNN Model 
![image](https://github.com/user-attachments/assets/af27723b-bdb8-41a9-a96d-4fe9581a7515)


📊 Results

Our deep CNN model outperforms traditional machine learning methods such as SVM, KNN, and HOG-based classifiers on CIFAR-10.

Model Testing      Accuracy        Test Loss

SVM (Linear)        36%             44

SVM (Polynomial)    40%             42

HOG                 40%             50

KNN                34%              66

CNN                74.7%            0.7

TRAINING ACCURACY OF DEEP CNN
![image](https://github.com/user-attachments/assets/3b8853ec-6f3e-431c-88f5-73bebd477a45)

CONFUSION MATRIX OF DEEP CNN
![image](https://github.com/user-attachments/assets/48186ab1-6b48-4340-bcba-223591c59277)



🔗 Google Colab Notebook

Run the model in Google Colab using the link below:👉 [Colab Notebook](https://colab.research.google.com/drive/14VUqJWKRyRvIl22bidvB6_gzy-KfjWC0#scrollTo=d3WPWaF1Iqc9)

## 📄 Research Paper
The full paper detailing this work is available here:  
👉 [**Download Paper (PDF)**](CIFAR10_DeepCNN_Paper.pdf)

