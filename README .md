
# Brain Tumor Classification using CNN

This project focuses on the classification of brain tumors using Convolutional Neural Networks (CNNs). The model is trained to differentiate between benign and various types of malignant brain tumors with high accuracy.

## Project Overview

This project utilizes a deep learning model to classify brain tumors into the following categories:
- Benign
- Malignant_Pre-B
- Malignant_Pro-B
- Malignant_early Pre-B

The model achieves an accuracy of 98.1% on the test set.

## Dataset

The dataset used in this project includes images of brain tumors that are labeled into the categories mentioned above. Ensure you have the dataset organized and available for training and testing the model.

## Requirements

To run this project, you will need the following libraries and dependencies:

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow/Keras

You can install these packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

## Usage

1. **Data Preparation**: Ensure your dataset is prepared and split into training and testing sets. The images should be properly labeled according to the categories mentioned.

2. **Model Training**: Run the cells in the notebook to train the CNN model on the training data. The model architecture includes several convolutional layers, max-pooling layers, and fully connected layers.

3. **Evaluation**: After training the model, evaluate its performance on the test set. The notebook includes a confusion matrix to visualize the classification results.

4. **Visualization**: The notebook provides visualization of the confusion matrix to help understand the model's performance in classifying each category.

## Results

The model achieved an accuracy of 98.1% on the test set. The confusion matrix visualization helps in understanding the model's performance across different categories of brain tumors.

## Conclusion

This project demonstrates the effectiveness of CNNs in classifying brain tumors with high accuracy. Further improvements can be made by experimenting with different model architectures, data augmentation techniques, and hyperparameter tuning.

## Acknowledgments

Special thanks to the creators of the dataset and the open-source community for providing the tools and libraries that made this project possible.
