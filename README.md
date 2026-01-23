## Project Overview

I built an end-to-end Convolutional Neural Network (CNN) classification model to classify diseases on potato leaves, to predict whether they have early blight, late blight or are healthy, and deployed the model.

The model was trained using Adam optimizer and achieved:

- **Training set:** 98.79% accuracy  
- **Validation set:** 98.44%  
- **Test set:** 98.43%

## Backend and Deployment

I implemented a FastAPI-based REST API backend that performs classification by forwarding requests to a TensorFlow Serving model where the model is stored and served from a Docker container.

I used Postman which a client tool to test the model but by sending HTTP requests to the container API.

## Frontend and Cloud Deployment

I built a local web-based app using React.js to implement how the model would be deploy and be used by people e.g farmers.

I then deployed the model on Google cloud platform.
