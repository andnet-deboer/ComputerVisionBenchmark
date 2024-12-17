# Math 395-Project-Final
[Project Report PDF]([Computer_Vision_Math_395.pdf](https://github.com/user-attachments/files/18170661/Computer_Vision_Math_395.pdf)
)

### Project Overview

In this project, we aim to develop and compare several machine learning models to classify images. The models will be trained to recognize and categorize distinct features within an image. By leveraging computer vision techniques, the model will learn to extract relevant visual features from the images to make accurate predictions about their classes. A comparison of each technique's performance will be conducted and the nuances of each technique will be analyzed in a final report.

### **Why is this Interesting or Important?**

Computer vision has become a critical area of artificial intelligence due to its broad range of applications, from facial recognition and autonomous driving to medical imaging and quality control in manufacturing. This project is particularly important because it seeks to determine the most performant techniques for computer vision outlining the strengths and pitfalls of each method. 

### **Specific Questions to Explore:**

1. **How accurate is the model's classification performance?**  
   * We will evaluate the model's ability to classify images correctly, measuring its accuracy, precision, recall, and F1 score to assess performance.  
2. **What features does the model use to classify images?**  
   * We will investigate the most important features (e.g., color, texture, shape, edges) for the model to learn in order to have the best performance.

**Data Set**

* [CIFAR-10](https://www.cs.toronto.edu/%7Ekriz/cifar.html): Contains 60000 32x32 color images with 10 classes and each class with 6000 images   
* [CIFAR-100](https://www.cs.toronto.edu/%7Ekriz/cifar.html): Contains 600 images for each class with a 100 classes   
* **Variables and Features**  
  * Labels: *airplane, automobile, bird, cat, deer, dog, frog, horse, ship and truck*  
  * Histogram of Oriented Gradients  
  * Quality of Edges using MSE and Structural Similarity

# 


# **Planned Analysis**

This project seeks to investigate the performance of CNN, KNN, and Logistic regression models on the CIFAR data set. Initially CIFAR-10 will be explored and then the more challenging CIFAR-100 will be analyzed. This presents a challenge for machine learning models since there are only 600 samples per class in the CIFAR-100 data set. By comparing model performance across these variations of the data set our project seeks to understand and compare the impact on performance for each model using the evaluation metrics such as percent error, precision, F1-score.

**Project Timeline**

1. *Preprocessing the Data*   
   1. Clean up  data so that the model can be trained(padding, normalization, encoding, etc.)  
2. *Developing the Model*  
   1. Convolutional Neural Networks  
   2. K Nearest Neighbors  
   3. Multit-Class Logistic Regression  
3. *Evaluating*   
   1. Percent Error  
   2. Precision  
   3. F1-Score  
   4. Confusion Matrix  
   5. Accuracy
