🧠 Deep Learning Practical Report 4 – CNN from Scratch & Transfer Learning
📌 Project Overview

This project focuses on implementing and understanding Convolutional Neural Networks (CNNs) for image classification using the CIFAR-10 dataset.

The practical covers fundamental deep learning concepts, including convolution operations, padding, strides, pooling, CNN architecture design, backpropagation, data augmentation, and transfer learning using MobileNetV2.

The project is implemented using Python, TensorFlow, and Keras in a Jupyter Notebook.

🎯 Objectives
Understand the fundamentals of Convolutional Neural Networks.
Load, explore, and preprocess the CIFAR-10 dataset.
Implement convolution operations and understand padding and strides.
Explore max pooling and average pooling.
Build and train CNN architectures from scratch.
Understand backpropagation in CNNs.
Apply data augmentation to improve model generalization.
Implement transfer learning using MobileNetV2.
Compare different deep learning models based on test accuracy and parameters.
📂 Dataset – CIFAR-10

The project uses the CIFAR-10 dataset, which consists of 60,000 color images belonging to 10 different classes.

Training images: 50,000
Testing images: 10,000
Image dimensions: 32 × 32 pixels
Color channels: 3 (RGB)
Number of classes: 10
Classes
Airplane
Automobile
Bird
Cat
Deer
Dog
Frog
Horse
Ship
Truck

The dataset is loaded directly using TensorFlow/Keras.

🛠️ Technologies & Libraries Used
Python
TensorFlow
Keras
NumPy
Pandas
Matplotlib
Seaborn
SciPy
Scikit-learn
Jupyter Notebook / Google Colab
📚 Project Tasks
Task A1 – Data Loading, EDA & Preprocessing
Load the CIFAR-10 dataset.
Explore dataset dimensions and class distributions.
Visualize sample images.
Analyze pixel intensity distributions.
Normalize image pixel values.
Perform one-hot encoding of class labels.
Task A2 – Convolution Operation, Padding & Strides
Understand the mathematical operation of convolution.
Implement a manual convolution operation.
Explore different padding techniques:
VALID Padding
SAME Padding
Understand the effect of strides on output dimensions.
Visualize convolution outputs and learned feature maps.
Task A3 – Pooling, Flatten & CNN Architectures
Understand max pooling and average pooling.
Visualize feature maps before and after pooling.
Explore flattening operations.
Implement LeNet-5 architecture.
Build a custom CNN architecture using Keras.
Analyze model summaries and parameter counts.
Task A4 – Backpropagation in CNN & Training
Understand forward propagation and backward propagation.
Train the custom CNN model from scratch.
Use callbacks such as:
Early Stopping
ReduceLROnPlateau
Monitor training and validation accuracy.
Evaluate the model on test data.
Generate confusion matrices and classification reports.
Visualize incorrectly classified images.
Task A5 – Data Augmentation
Understand the importance of data augmentation.
Apply random image transformations.
Use Keras ImageDataGenerator.
Implement augmentation using Keras preprocessing layers.
Compare model performance with and without augmentation.
Task A6 – Transfer Learning: Feature Extraction & Fine-Tuning
Implement transfer learning using MobileNetV2.
Use ImageNet-pretrained weights.
Perform feature extraction by freezing the pretrained base model.
Train a custom classification head.
Fine-tune the top layers of MobileNetV2.
Compare feature extraction and fine-tuning performance.
Demonstrate a residual block architecture.
🏗
