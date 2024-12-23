# Fruit-Classification-and-Quality-Checker
This project is a Flask-based web application designed to classify fruits and assess their quality using a Convolutional Neural Network (CNN). The model is trained with Keras and TensorFlow, leveraging computer vision techniques to analyze features such as color, texture, and shape for accurate quality assessment.

# Features
- Fruit Classification: Identify the type of fruit based on uploaded images.
- Quality Assessment: Evaluate the ripeness or overall quality of the fruit.
- User-Friendly Interface: Simple and intuitive web interface powered by Flask for seamless interactions.
- AI-Driven Insights: Uses a trained CNN model to provide reliable results.

# Technical Highlights
- Frameworks: Flask for the web app, Keras and TensorFlow for the machine learning model.
- Dataset: A curated dataset of labeled fruit images used to train the CNN model.
- Model Architecture: CNN designed for feature extraction and classification.
- Real-Time Processing: Allows users to upload images and receive instant feedback.

# How It Works
- Upload an Image: The user uploads a fruit image via the web app.
- Processing: The image is analyzed by the trained CNN model.
- Results: The app displays the fruit type and its quality assessment.

# Use Cases
Enhancing decision-making for storage and transportation of fruits.
Reducing food waste by providing insights on fruit ripeness.
Assisting consumers in selecting high-quality fruits.

# Run
After successfully creating anaconda environment, install the required packages and libraries:

pip install -r requirements.txt

Then by run:

python app.py
