# Cat-and-Dog-Image-Classifier

Cat and Dog Image Classifier 🐱🐶

This project, created as part of freeCodeCamp’s Machine Learning with Python curriculum, is a deep learning model designed to classify images of cats and dogs. By leveraging Convolutional Neural Networks (CNN) and data augmentation techniques, the classifier learns to differentiate between images of cats and dogs with improved accuracy.

Project Overview

This project enhances skills in Machine Learning and Neural Networks by building a robust image classifier. The model is trained to categorize images as either “cat” or “dog” by analyzing and learning from labeled image data. Through data augmentation, the model becomes more resilient to variations in images, making it adaptable to new, unseen data.

Technologies Used

  •	Python: Core programming language
	•	TensorFlow & Keras: Deep learning frameworks for model building
	•	ImageDataGenerator: For real-time data augmentation

Data Preprocessing

Data augmentation is crucial for making the model more versatile and accurate. The ImageDataGenerator was used to enhance the training images through the following transformations:

  •Horizontal & Vertical Flipping
	•	Zooming
	•	Vertical & Horizontal Shifting

Model Architecture

The model employs Convolutional Neural Networks (CNNs), which are effective for image classification tasks due to their ability to recognize spatial patterns. The architecture includes:

  1.	Convolutional Layers: For feature extraction.
	2.	Pooling Layers: To reduce spatial dimensions and avoid overfitting.
	3.	Fully Connected Layers: For classification into “cat” or “dog.”

Results

The model achieves a high level of accuracy in distinguishing between cats and dogs, aided by both CNN architecture and data augmentation techniques.
