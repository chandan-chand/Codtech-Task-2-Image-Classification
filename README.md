# Codtech-Task-2-Image-Classification
This project develops an image classification model using a Convolutional Neural Network (CNN) with TensorFlow. The model is trained on the CIFAR-10 dataset to learn and recognize different object categories from images. It predicts the class of input images and evaluates performance using accuracy and loss metrics.

# 📌 Image Classification using CNN (TensorFlow)

## 📖 Project Overview
This project implements an Image Classification model using a Convolutional Neural Network (CNN) in TensorFlow. The model is trained on the CIFAR-10 dataset to classify images into 10 different object categories such as airplanes, cars, animals, and more. It demonstrates the practical application of deep learning in computer vision.

## 🎯 Objective
- To build and train a CNN model for image classification  
- To learn feature extraction using deep learning  
- To evaluate model performance using accuracy and loss  

## 📂 Dataset
- Name: CIFAR-10  
- Source: Built-in TensorFlow dataset  
- Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck  
- Training Images: 50,000  
- Testing Images: 10,000  

## 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Google Colab  

## 🧠 Model Architecture
- Convolutional Layers (Conv2D)  
- Max Pooling Layers  
- Flatten Layer  
- Fully Connected (Dense) Layers  
- Output Layer with Softmax Activation  

## ⚙️ How It Works
1. Load and preprocess the CIFAR-10 dataset  
2. Normalize image pixel values  
3. Build a CNN model  
4. Train the model using training data  
5. Evaluate performance using test data  
6. Visualize accuracy and loss graphs  
7. Predict and classify images  

## 📊 Results
- Model achieves good accuracy on test data  
- Accuracy and loss graphs are plotted for performance evaluation  
- Sample predictions are visualized  

## ▶️ How to Run
1. Open the project in Google Colab  
2. Run all code cells step by step  
3. Train the model  
4. View graphs and predictions  

## 📌 Output
- Classified images with predicted labels  
- Accuracy and loss visualization graphs  

## 💾 Model Saving
The trained model can be saved using:
model.save("image_classification_model.keras")

## 🚀 Future Improvements
- Increase model accuracy using deeper architectures  
- Use custom datasets  
- Apply data augmentation  
- Deploy the model using Flask  

## 📚 Conclusion
This project demonstrates how deep learning can be used to classify images by learning meaningful patterns and features from data.
