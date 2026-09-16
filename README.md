Deep Learning Fashion Classification
A Google Colab practical for BBA AI/ML students demonstrating how Deep Learning can be used to classify fashion product images using the Fashion MNIST dataset.

📌 Project Overview
In e-commerce, thousands of product images may need to be categorized before products are added to an online store. This project demonstrates how a simple Artificial Neural Network can automatically classify fashion images into different product categories.

🎯 Learning Objectives
Understand images as input for Deep Learning.

Build a simple Artificial Neural Network using TensorFlow/Keras.

Understand input, hidden, and output layers.

Train a model using labelled image data.

Evaluate model accuracy.

Use the trained model to predict product categories.

Understand a practical business application of image classification.

🗂️ Dataset
The project uses the Fashion MNIST dataset provided through TensorFlow/Keras.

The dataset contains 28×28 grayscale images belonging to 10 fashion categories:

T-shirt/Top

Trouser

Pullover

Dress

Coat

Sandal

Shirt

Sneaker

Bag

Ankle Boot

🧠 Model Architecture
The neural network contains three main stages:

Input Image → Hidden Layer → Output Layer

Flatten converts the 28×28 image into a one-dimensional input.

Dense(64) is the hidden layer.

ReLU is used as the hidden-layer activation function.

Dense(10) produces outputs for the 10 product categories.

Softmax provides category probabilities.

⚙️ Technologies Used
Python

TensorFlow

Keras

NumPy

Matplotlib

Google Colab

📊 Project Steps
Import required libraries.

Load the Fashion MNIST dataset.

Define product categories.

Visualize product images.

Normalize pixel values from 0–255 to 0–1.

Create the neural network.

Compile the model.

Train the model for 3 epochs.

Evaluate test accuracy.

Predict product categories.

Compare predicted and actual categories.

Interpret the results from a business perspective.

💼 Business Application
An e-commerce company can use image classification to assist with product categorization.

Traditional Process:

Product Image → Employee → Manual Category Selection

AI-Assisted Process:

Product Image → Deep Learning Model → Predicted Category → Human Review → Product Listing

Possible Benefits
Faster product listing

Reduced repetitive manual work

More consistent product categorization

Improved product search

Ability to process large numbers of images

⚠️ Limitations
The model may make incorrect predictions, especially for visually similar categories such as shirts, T-shirts, pullovers, and coats.

Therefore, human review can remain important before automatically publishing product information.

📁 Repository Structure
part-a/
└── deep-learning/
    ├── Deep_Learning_Fashion_Classification_Name.ipynb
    ├── README.md
    └── screenshot.png

📸 Submission
The notebook should include a screenshot showing:

A product image

Predicted category

Actual category

The notebook should be renamed as:

Deep_Learning_Fashion_Classification_Name.ipynb

👨‍🎓 Student Reflection
This project demonstrates how Deep Learning can solve a practical business problem by automatically classifying product images. It also highlights that AI predictions are not always perfect and that businesses should consider accuracy, risk, and human oversight when deploying AI systems.

📌 Conclusion
This practical provides a basic introduction to image classification using an Artificial Neural Network. It connects Deep Learning concepts with a real-world e-commerce use case and demonstrates how AI can support business processes while keeping humans involved where necessary.
