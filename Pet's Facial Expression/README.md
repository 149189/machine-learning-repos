# **Pet's Facial Expression Detection**

### 🎯 Goal
This project aims to develop an advanced image classification system that can accurately identify the facial expressions of pets using cutting-edge deep learning techniques.

### Purpose
Understanding pet emotions through their facial expressions can significantly enhance the bond between pets and their owners. This project aims to leverage advanced AI models to detect and classify various facial expressions in pets, aiding in better care and understanding of pets' emotional states.

### 🧵 Dataset
The dataset used in this project is: https://www.kaggle.com/datasets/anshtanwar/pets-facial-expression-dataset

### 🧾 Description
This project focuses on developing a sophisticated image classification system to identify different facial expressions in pets using deep learning techniques. The system leverages three state-of-the-art convolutional neural network (CNN) architectures: EfficientNet and ResNet50, and Vision Transformer (ViT) architecture, each known for their robustness and high performance in image recognition tasks.

### 🚀 Models Implemented
- ViT Transformer: Utilizes the transformer architecture for image classification, providing state-of-the-art accuracy.
- EfficientNet: A family of models that balance model depth, width, and resolution, achieving high performance with fewer parameters.
- ResNet50: Employs residual learning to train very deep networks, addressing the vanishing gradient problem and achieving high accuracy.

### 📚 Libraries Needed
- TensorFlow: For building and training deep learning models.
- Keras: For simplifying the creation and training of neural networks.
- NumPy: For numerical computations and array operations.
- Pandas: For data manipulation and analysis.
- Matplotlib: For plotting and visualizing data.

### 📊 Exploratory Data Analysis Results
Exploratory Data Analysis (EDA) involved examining the distribution of the dataset, visualizing sample images, and understanding the different classes of facial expressions. The dataset was split into training and testing sets to evaluate the model's performance effectively.


### 📢 Conclusion
The Vision Transformer (ViT) model successfully classified the facial expressions of pets with high accuracy. The EfficientNet model showed moderate performance, and the ResNet50 model achieved the highest accuracy among the three models. Each model's performance demonstrates the potential of using advanced neural network architectures for image classification tasks in the domain of pet emotion detection.

### Accuracy Results
The model's performance was evaluated using accuracy and F1 scores.
1. ViT
   - Training Accuracy: 80.0%
   - F1 Score: 0.8
2. EfficientNet
   - Training Accuracy: 57.7%
   - F1 Score: 0.54
3. ResNet50
   - Training Accuracy: 97.99%

### Best Fitted Model
The ResNet50 model proved to be the best-fitted model for this task, achieving the highest accuracy and demonstrating robustness in classification.

## ✒️ Contributor
- Name: Himanshu Kumar