# Driver_ML_Drowsiness
**Driver Drowsiness Detection System with OpenCV & Keras**

![driver-drowsiness](https://github.com/0-0Dibakar/Driver_ML_Drowsiness/assets/106139442/84f7258f-391e-4d84-aedf-d1751be4123f)

With this Python project, we will be making a drowsiness detection system. A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy.

The majority of accidents happen due to the drowsiness of the driver. So, to prevent these accidents we will build a system using Python, OpenCV, and Keras which will alert the driver when he feels sleepy.

**Drowsy Driver Alert System**
Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving.

The objective of this intermediate Python project is to build a drowsiness detection system that will detect that a person’s eyes are closed for a few seconds. This system will alert the driver when drowsiness is detected.

**Driver Drowsiness Detection System**
In this Python project, we will be using OpenCV for gathering the images from webcam and feed them into a Deep Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’. The approach we will be using for this Python project is as follows :

**Step 1** – Take image as input from a camera.

**Step 2** – Detect the face in the image and create a Region of Interest (ROI).

**Step 3** – Detect the eyes from ROI and feed it to the classifier.

**Step 4** – Classifier will categorize whether eyes are open or closed.

**Step 5** – Calculate score to check whether the person is drowsy

**The Model Architecture**
The model we used is built with Keras using **Convolutional Neural Networks (CNN)**. A convolutional neural network is a special type of deep neural network which performs extremely well for image classification purposes. A CNN basically consists of an input layer, an output layer and a hidden layer which can have multiple layers. A convolution operation is performed on these layers using a filter that performs 2D matrix multiplication on the layer and filter.

The CNN model architecture consists of the following layers:

**->**Convolutional layer; 32 nodes, kernel size 3
**->**Convolutional layer; 32 nodes, kernel size 3
**->**Convolutional layer; 64 nodes, kernel size 3
**->**Fully connected layer; 128 nodes
The final layer is also a fully connected layer with 2 nodes. A Relu activation function is used in all the layers except the output layer in which we used Softmax.

**Project Prerequisites**
The requirement for this Python project is a webcam through which we will capture images. You need to have Python (3.6 version recommended) installed on your system, then using pip, you can install the necessary packages.

**1.OpenCV** – pip install opencv-python (face and eye detection).
**2.TensorFlow** – pip install tensorflow (keras uses TensorFlow as backend).
**3.Keras** – pip install keras (to build our classification model).
**4.Pygame** – pip install pygame (to play alarm sound).
