# Hand Gesture Recognition - 1 to 5
This project uses machine learning algorithms to recognize hand gestures representing the numbers 1 to 5. The dataset consists of images of hands with different numbers of fingers extended. The goal is to train a classifier that can predict the correct number of fingers represented by a hand gesture in a new image.

## Dataset
The dataset used in this project is a collection of images of hands with different numbers of fingers extended. Each image is labeled with the correct number of fingers represented in the image. The dataset consists of 360 images, with 72 images for each of the numbers 1 to 5. The images are grayscale, high contrasted and have a resolution of 64 x 64 pixels.

## Preprocessing
Before training the machine learning models, the images are preprocessed to improve the quality of the data. First, the images are resized to 32 x 32 pixels to reduce the computational requirements. Then, the pixel values are scaled between 0 and 1. Finally, the dataset is split into a training set (88%), valid test (8%), and a test set (4%).

## Models
We used [YoloV8](https://github.com/ultralytics/ultralytics) for this task. The performance of each model is evaluated using accuracy, precision, recall, and F1 score on the test set. The best model is selected based on its performance.

## Results
The model achieved a precision of 70%. The confusion matrix shows that the model performs well for all classes, with the lowest accuracy for the number 2. The precision, recall, and F1 scores for each class are also reported.

## Conclusion
This project demonstrates the use of machine learning algorithms to recognize hand gestures representing the numbers 1 to 5. This model can be used for a variety of applications, such as sign language recognition or gesture-based interfaces.