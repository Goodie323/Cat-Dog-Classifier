# Cat-Dog-Classifier
This project is a Streamlit web app that classifies images as either a cat or a dog using a CNN model. The model, trained on a dataset of cat and dog images, expects inputs resized to 64x64 pixels. The app provides an intuitive interface for image uploads and displays the classification results.

This project is a Streamlit-based web application that classifies images as either a cat or a dog using a Convolutional Neural Network (CNN) model. The model is trained to identify whether an image contains a cat or a dog and provides results through an interactive web interface.

Demo

Features
Image Classification: Classifies uploaded images as either a cat or a dog.

User-Friendly Interface: Built with Streamlit, offering an intuitive and easy-to-use UI.

Real-Time Results: Instant classification upon image upload.

Installation
To run the app locally, follow these steps:


Here's a comprehensive README template for your cat vs. dog classifier project:

Cat vs Dog Classifier Web App
This project is a Streamlit-based web application that classifies images as either a cat or a dog using a Convolutional Neural Network (CNN) model. The model is trained to identify whether an image contains a cat or a dog and provides results through an interactive web interface.

Demo

Features
Image Classification: Classifies uploaded images as either a cat or a dog.
User-Friendly Interface: Built with Streamlit, offering an intuitive and easy-to-use UI.
Real-Time Results: Instant classification upon image upload.
Installation
To run the app locally, follow these steps:

Clone the Repository:
git clone https://github.com/Goodie323/cat-dog-classifier.git
cd cat-dog-classifier

Create a Virtual Environment (Optional but recommended):
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

Install Dependencies:
pip install -r requirements.txt


Run the Application:
streamlit run main.py

Usage
Upload an Image: Drag and drop an image or use the file uploader to select an image of a cat or dog.
View the Result: The app will display the uploaded image and the predicted class ("Cat" or "Dog").


Model Details
Input Shape: 64x64x3 (Height, Width, Channels)
Architecture: Custom Convolutional Neural Network (CNN)
Framework: TensorFlow/Keras
Project Structure
app.py: The main Streamlit application script.
model/: Contains the trained model file (model.h5).
requirements.txt: A list of dependencies required to run the app.
assets/: Contains images and other assets used in the README.

.gitignore: Specifies files and directories to be ignored in the repository.
Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository, create a new branch, and submit a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
Streamlit - Framework for creating the web app.
TensorFlow - Deep learning library used for model training.
Pillow - Library for image processing.
