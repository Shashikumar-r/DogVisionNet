
# 🐶 DogVisionNet 🎨

## Overview
DogVisionNet is a TensorFlow 2.0 based project utilizing transfer learning to classify dog breeds. This repository includes the implementation in the `dog-vision-net.ipynb` file, which serves as the main notebook for training and evaluating the model.

## Features 🚀
- **Transfer Learning:** Utilizes pre-trained models from TensorFlow Hub for feature extraction.
- **Dog Breed Classification:** Trains a deep learning model to classify different breeds of dogs.
- **TensorFlow 2.0:** Takes advantage of the latest TensorFlow functionalities and best practices.

## 📁 Files
- `dog-vision-net.ipynb`: Jupyter notebook containing the complete code for data preprocessing, model training, evaluation, and inference.
- `README.md` (this file): Provides an overview of the project, installation instructions, usage guidelines, results

## Installation 🛠️
1. Clone the repository:
   ```
   git clone https://github.com/Shashikumar-r/DogVisionNet.git
   cd DogVisionNet
   ```
   
2. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```
   Ensure TensorFlow 2.x is installed (`tensorflow` or `tensorflow-gpu`).

## Usage 🖥️
1. Open and run `dog-vision-net.ipynb` in a Jupyter notebook environment.
2. Follow the instructions in the notebook to:
   - Load and preprocess the dataset.
   - Choose a pre-trained model from TensorFlow Hub.
   - Fine-tune the model on the dog breed classification task.
   - Evaluate the model's performance.
   - Make predictions on new images.

## Example Workflow 📋
- **Step 1:** Load and preprocess the dataset using TensorFlow's `ImageDataGenerator`.
- **Step 2:** Choose a pre-trained model (e.g., InceptionV3, ResNet50) from TensorFlow Hub.
- **Step 3:** Fine-tune the model by adjusting the top layers for the dog breed classification task.
- **Step 4:** Train the model and monitor its performance using validation metrics.
- **Step 5:** Evaluate the final model on a test set and visualize results.
- **Step 6:** Use the model for inference on new images to predict dog breeds.

## Results 📊
![dog_1 Screenshot](https://github.com/Shashikumar-r/DogVisionNet/blob/main/dog_1.png)

![dog_2 Screenshot](https://github.com/Shashikumar-r/DogVisionNet/blob/main/dog_2.png)

## License 📜
This project is licensed under the [MIT License](LICENSE).

