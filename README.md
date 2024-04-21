# Pedestrian Detection with Convolutional Neural Networks

## Introduction
Welcome to my pedestrian detection repository! In this project, I've implemented pedestrian detection using convolutional neural networks (CNNs) in Python. The goal of this project is to detect pedestrians in images using deep learning techniques.

## Dataset
For this project, I've collected a dataset of images from Google Images containing both pedestrians and scenes without pedestrians. This dataset serves as the basis for training and testing the pedestrian detection model.

## Image Preprocessing
Before feeding the images into the CNN model, I performed preprocessing techniques to enhance the model's performance. These techniques include:
- Resizing images to a uniform size to ensure consistency.
- Normalizing pixel values to a range between 0 and 1.
- Data augmentation to increase the diversity of the training set and improve generalization.

## Convolutional Neural Network (CNN)
I implemented a CNN architecture for pedestrian detection. CNNs are particularly effective for image-related tasks due to their ability to automatically learn hierarchical representations from the data.

### CNN Architecture
The CNN architecture consists of convolutional layers, pooling layers, and fully connected layers. Each layer learns specific features from the input images, gradually transforming them into high-level representations.

## Model Training
The CNN model was trained using the prepared dataset. During training, the model learns to classify images into two categories: images containing pedestrians and images without pedestrians.

## Evaluation and Testing
After training, the model was evaluated on a separate test set to assess its performance. Evaluation metrics such as accuracy, precision, recall, and F1-score were used to measure the model's effectiveness in pedestrian detection.

## Final Prediction
Once trained and evaluated, the pedestrian detection model is capable of predicting the presence of pedestrians in new images. This prediction can be used for various applications, including pedestrian ![test and result from the test](https://github.com/mdoctos/Pedistrian-Detection-/assets/57889962/d4facb72-b587-40c8-a736-a90e4ab054be)
detection in surveillance systems, autonomous vehicles, and pedestrian safety.

## Conclusion
Pedestrian detection using CNNs is a crucial task with numerous real-world applications. This project demonstrates the effectiveness of deep learning techniques in accurately detecting pedestrians in images. By leveraging the power of CNNs, we can create robust and reliable pedestrian detection systems for enhanced safety and security.

Feel free to explore the repository, experiment with the code, and contribute to further advancements in pedestrian detection technology!
