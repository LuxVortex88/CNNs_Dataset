🧠 Convolutional Neural Network (CNN) on CIFAR-10
A compact image classification project with visualization and clarity.

✨ Overview
This project demonstrates a clean implementation of a Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset — a widely used benchmark for image classification tasks. It includes model evaluation and a visual representation of predictions on test images.

🧪 Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class:

Airplane, Automobile, Bird, Cat, Deer

Dog, Frog, Horse, Ship, Truck

🏗️ Model Architecture
The CNN model is composed of:

3 Convolutional layers with ReLU activation

2 MaxPooling layers

1 Fully Connected (Dense) layer

1 Output layer with 10 units (for classification)



🧠 Training
Optimizer: Adam

Loss Function: SparseCategoricalCrossentropy


🎯 Results
The model is evaluated on the test set, and the accuracy is printed.

In addition, the model predicts the class of the first image in the test set and visualizes the result using matplotlib.

📂 How to Run
pip install tensorflow matplotlib
python cnn_cifar10.py




📜 License
This project is open-source and free to use for learning and experimentation.
