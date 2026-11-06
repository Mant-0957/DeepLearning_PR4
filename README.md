# Deep Learning Practical 4A – CNN from Scratch: CIFAR-10 Image Classifier

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** using Deep Learning techniques to classify images from the CIFAR-10 dataset.

The main objective is to understand how CNNs work, starting from basic convolution operations and progressing toward advanced concepts such as data augmentation and transfer learning.

This practical covers six major tasks, including image preprocessing, convolution, pooling, CNN architecture development, backpropagation, data augmentation, and MobileNetV2-based transfer learning.

The project is implemented using Python, TensorFlow, and Keras in a Jupyter Notebook.

## 🎯 Project Objectives

- Understand the fundamentals of Convolutional Neural Networks.
- Load and preprocess the CIFAR-10 dataset.
- Understand convolution operations, padding, and strides.
- Explore Max Pooling and Average Pooling.
- Implement LeNet-5 and custom CNN architectures.
- Understand forward propagation and backpropagation.
- Train and evaluate CNN models.
- Apply data augmentation to reduce overfitting.
- Implement transfer learning using MobileNetV2.
- Compare different model architectures and their performance.

## 📂 Dataset Information

**Dataset:** CIFAR-10

CIFAR-10 is a popular image classification dataset containing 60,000 colour images divided into 10 different categories.

| Dataset Information | Details |
|---|---|
| Total Images | 60,000 |
| Training Images | 50,000 |
| Testing Images | 10,000 |
| Image Dimensions | 32 × 32 |
| Colour Channels | 3 (RGB) |
| Number of Classes | 10 |
| Problem Type | Multiclass Classification |

### CIFAR-10 Classes

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

**Dataset Source:** [CIFAR-10 Official Website](https://www.cs.toronto.edu/~kriz/cifar.html)

The dataset is automatically downloaded using the TensorFlow/Keras dataset API.

## 🛠️ Technologies & Libraries Used

- **Python** – Programming language
- **TensorFlow** – Deep Learning framework
- **Keras** – CNN model implementation
- **NumPy** – Numerical computations
- **Pandas** – Data manipulation
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **SciPy** – Convolution operations
- **Scikit-learn** – Model evaluation

## ⚙️ Project Workflow

### Task A1 – Data Loading, EDA & Preprocessing

**Objective:** Understand and prepare the CIFAR-10 dataset for CNN training.

Activities:
- Load the CIFAR-10 dataset.
- Examine training and testing dataset shapes.
- Display sample images from all 10 classes.
- Perform exploratory data analysis (EDA).
- Visualize image pixel distributions.
- Normalize pixel values from 0–255 to 0–1.
- Convert target labels into one-hot encoded format.

**Expected Outputs:**
- Dataset information and shapes.
- 5 × 10 image visualization grid.
- Pixel distribution histograms.
- Preprocessed image and label information.

### Task A2 – Convolution Operation, Padding & Strides

**Objective:** Understand how convolution extracts important features from images.

Activities:
- Perform manual 2D convolution.
- Understand convolution filters and kernels.
- Explore VALID and SAME padding.
- Compare different stride values.
- Understand convolution output dimensions.
- Visualize learned Conv2D feature maps.

**Key Concepts:**
- Convolution
- Filters and Kernels
- Padding
- Strides
- Feature Extraction
- Feature Maps

**Expected Outputs:**
- Manual convolution results.
- Output shape comparisons.
- 4 × 4 feature-map visualization.

### Task A3 – Pooling, Flatten & CNN Architectures

**Objective:** Understand pooling operations and build CNN architectures.

Activities:
- Implement Max Pooling.
- Implement Average Pooling.
- Compare feature maps before and after pooling.
- Understand Flatten operations.
- Calculate model parameters.
- Implement LeNet-5 architecture.
- Build a modern custom CNN architecture.

**Key Concepts:**
- Max Pooling
- Average Pooling
- Flatten Layer
- Fully Connected Layers
- LeNet-5
- Custom CNN

**Expected Outputs:**
- Pooling comparison visualizations.
- Tensor shape information.
- CNN model summaries.
- Parameter comparisons.

### Task A4 – Backpropagation in CNN & Training

**Objective:** Train CNN models and understand how backpropagation updates network parameters.

Activities:
- Understand forward propagation.
- Understand backward propagation.
- Calculate gradients during training.
- Train the custom CNN model.
- Apply Early Stopping.
- Use ReduceLROnPlateau.
- Evaluate the trained model.

**Model Evaluation:**
- Training accuracy.
- Validation accuracy.
- Training loss.
- Validation loss.
- Test accuracy.
- Classification report.
- Confusion matrix.
- Misclassified image visualization.

**Expected Outputs:**
- Training and validation curves.
- Test performance metrics.
- Confusion matrix.
- Visualization of incorrectly classified images.

### Task A5 – Data Augmentation

**Objective:** Improve model generalization and reduce overfitting using image augmentation techniques.

Activities:
- Understand the importance of data augmentation.
- Apply random image transformations.
- Perform image shifting.
- Apply rotation and zoom.
- Use horizontal flipping.
- Implement ImageDataGenerator.
- Implement Keras preprocessing augmentation layers.
- Compare augmented and non-augmented models.

**Key Concepts:**
- Image Augmentation
- Random Rotation
- Width and Height Shifting
- Zooming
- Horizontal Flipping
- Regularization

**Expected Outputs:**
- Augmented image visualization grid.
- Training performance comparison.
- Test accuracy comparison.

### Task A6 – Transfer Learning: Feature Extraction & Fine-Tuning

**Objective:** Use a pretrained MobileNetV2 model to improve image classification performance.

Activities:
- Understand transfer learning.
- Load ImageNet-pretrained MobileNetV2.
- Resize CIFAR-10 images for MobileNetV2.
- Freeze the pretrained base model.
- Perform feature extraction.
- Train a custom classification head.
- Fine-tune the top 30 layers.
- Use a low learning rate during fine-tuning.
- Compare transfer learning with scratch CNN models.

**Key Concepts:**
- Transfer Learning
- MobileNetV2
- ImageNet Weights
- Feature Extraction
- Fine-Tuning
- Frozen Layers
- Trainable and Non-Trainable Parameters

**Expected Outputs:**
- Model parameter summaries.
- Feature extraction training curves.
- Fine-tuning training curves.
- Six-model performance comparison.
- Residual block implementation.

## 🧠 CNN Architecture

The project explores multiple CNN architectures:

1. LeNet-5
2. Custom CNN
3. CNN with Data Augmentation
4. CNN with Keras Augmentation Layers
5. MobileNetV2 Feature Extraction
6. MobileNetV2 Fine-Tuning

The models are evaluated to understand the benefits of different CNN architectures and training techniques.

## 📊 Model Evaluation Metrics

The following evaluation methods are used:

| Metric | Purpose |
|---|---|
| Accuracy | Measures overall correct predictions |
| Loss | Measures prediction error |
| Precision | Measures correctness of positive predictions |
| Recall | Measures the ability to identify actual positives |
| F1-Score | Balances precision and recall |
| Confusion Matrix | Compares actual and predicted classes |

Additional visualizations include:
- Training and validation accuracy graphs.
- Training and validation loss graphs.
- Confusion matrix.
- Misclassified image samples.
- Model performance comparison table.


## 📁 Project Structure

```text
DeepLearning_PR4/
│
├── DL_PR4A (1).ipynb
│   └── Complete CNN implementation
│
└── README.md
    └── Project documentation
```

**Note:** CIFAR-10 is downloaded automatically through TensorFlow/Keras, so a separate dataset file is not required.

## 📚 Key Learning Outcomes

After completing this practical, I gained hands-on experience with:

- Deep Learning fundamentals.
- Convolutional Neural Networks.
- Image preprocessing and normalization.
- Convolution operations and feature extraction.
- Padding and stride calculations.
- Pooling and Flatten layers.
- CNN architecture development.
- LeNet-5 implementation.
- Forward and backward propagation.
- Model training and optimization.
- Data augmentation techniques.
- Transfer learning using MobileNetV2.
- Feature extraction and fine-tuning.
- Model evaluation and visualization.

## 👨‍💻 Author

**Mant Sherasiya**

- GitHub: [Mant-0957](https://github.com/Mant-0957)
- Repository: [DeepLearning_PR4](https://github.com/Mant-0957/DeepLearning_PR4)
- Notebook: [DL_PR4A (1).ipynb](https://github.com/Mant-0957/DeepLearning_PR4/blob/main/DL_PR4A%20%281%29.ipynb)

---
