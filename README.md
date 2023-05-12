## Malaria Disease Detection using Deep Learning 

This project aims to detect malaria using deep learning techniques. Malaria is a life-threatening disease caused by the Plasmodium parasite. Early detection and prompt treatment can significantly reduce the mortality rate. In this project, we will be using deep learning algorithms to classify images of blood cells as infected or not infected with the malaria parasite.
## Dataset

The dataset used in this project is the Malaria Cell Images Dataset. It contains 27,558 cell images with equal instances of parasitized and uninfected cells. Each image is in RGB format and has a size of 120x120 pixels.

## Approach

1) Preprocessing: The images are preprocessed by resizing them.

2) Training-Validation Split: The dataset is split into training and validation sets. The training set contains 80% of the data, and the validation set contains 20%.

3) Model Architecture: A Convolutional Neural Network (CNN) is used to classify the images. The CNN has 4 convolutional layers followed by 2 fully connected layers. The output layer has 2 nodes for binary classification.

4) Training: The model is trained on the training set using the Adam optimizer and binary cross-entropy loss. The model is trained for 50 epochs with a batch size of 32.

5) Evaluation: The model is evaluated on the validation set using the accuracy metric.

6) Testing: The model is tested on a separate test set to evaluate its performance on new data.
## Conclusion

In this project, we have demonstrated the use of deep learning techniques to detect malaria in blood cells. The results show that our CNN model achieves high accuracy on the validation and test sets. This approach can be extended to other medical image classification problems to aid in early disease diagnosis.
## Author

Atharva Fulmamdikar (Linkedin : https://www.linkedin.com/in/atharva2706/)