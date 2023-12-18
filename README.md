# Cat and Dog Image Classifier
## Cat: 
![Cat Image]https://pbs.twimg.com/media/F_QzuHsXoAApvjz?format=jpg&name=small

## Dog:
![Dog Image]https://cdn.britannica.com/79/232779-050-6B0411D7/German-Shepherd-dog-Alsatian.jpg
## Overview

This Python script implements an image classification model using a Support Vector Machine (SVM) with a Convolutional Neural Network (CNN). The model is trained to distinguish between images of cats and dogs. The project is part of Prodigy Infotech's third task.

## Instructions for Use

1. **Importing Important Modules:**
   - Pandas: Data manipulation and analysis.
   - NumPy: Numerical operations.
   - TensorFlow: Neural network construction and training.

2. **Preprocessing the Training Data:**
   - Data augmentation is applied using TensorFlow's ImageDataGenerator to prevent overfitting.
   - Training and test sets are generated from the provided dataset.

3. **Creating the Model:**
   - The CNN model is built using TensorFlow's Keras API.
   - Layers include convolutional layers, pooling layers, flattening layers, fully connected layers, and an output layer.

4. **Training the CNN:**
   - The model is compiled with the Adam optimizer and hinge loss function.
   - Training involves fitting the model to the training set and validating it on the test set for multiple epochs.

5. **Plotting Training and Validation Metrics:**
   - Code is provided to plot training and validation loss, as well as training and validation accuracy over epochs.

6. **Saving the Trained Model:**
   - The trained CNN model is saved as a .h5 file for future use or deployment.

7. **Testing the Model on a Sample Image:**
   - A sample image from the test set is loaded, preprocessed, and used to make predictions.
   - The result is displayed alongside the image.

## Conclusion

This project serves as a tutorial on image classification using SVM with CNN. Feel free to modify the code or address any bugs. For questions or improvements, please contact the author.

## Author

[Your Name]

## License

This project is licensed under the [MIT License](LICENSE).
