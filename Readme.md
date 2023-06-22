### Potato Disease Classification using CNN

This repository contains the code for a project that focuses on the classification of potato diseases using Convolutional Neural Networks (CNN). The goal of this project is to build a model that can accurately identify various diseases affecting potato plants, aiding in early detection and effective treatment.


## Dataset
The dataset used for training and evaluation is a collection of labeled images of healthy potatoes and different disease-infected potatoes. It includes images of common diseases such as late blight, early blight, and leaf mold, among others. The dataset is properly labeled and divided into training, validation, and testing sets to ensure reliable model performance.


## Model Architecture

The classification model is built using a CNN architecture, which has proven to be highly effective for image recognition tasks. The model leverages convolutional layers to extract relevant features from input images and employs pooling layers to reduce spatial dimensions. It also includes fully connected layers for classification purposes. The architecture has been fine-tuned and optimized to achieve accurate disease classification.


## Dependencies

To run this project, the following dependencies are required:

 Python (version X.X)
- TensorFlow (version X.X)
- FastAPI (version X.X)
- TF-Serving (version X.X)

It is recommended to create a virtual environment and install the necessary packages using the provided requirements.txt file.

## Usage
1) Clone this repository to your local machine.
2) Install the required dependencies by running pip install -r requirements.txt in your virtual environment.
3) Preprocess and augment the dataset if necessary.
4) Train the CNN model using the prepared dataset. Optionally, you can fine-tune the hyperparameters to achieve better performance.
5) Evaluate the trained model on the validation set to assess its accuracy and adjust if needed.
6) Once satisfied with the model's performance, save it in a format compatible with TF-Serving.
7) Deploy the model using FastAPI and TF-Serving to create an API endpoint for disease classification.
8) Integrate the API endpoint into your mobile and web applications to allow users to classify potato diseases easily.

## Additional Resources
- Link to the dataset
- Example notebook for data preprocessing and model training
- Documentation on FastAPI
- Documentation on TensorFlow Serving
Please note that this README provides a high-level overview of the project. For detailed instructions and implementation details, refer to the accompanying code and documentation files.

## License
This project is licensed under the MIT License. Feel free to modify and adapt the code for your purposes.
