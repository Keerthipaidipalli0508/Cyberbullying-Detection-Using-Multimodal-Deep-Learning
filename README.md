# Cyberbullying-Detection-Using-Multimodal-Deep-Learning
A deep learning–based system designed to detect cyberbullying on social media by analyzing both text and image data. This project combines Natural Language Processing (NLP) and Computer Vision techniques to build an end-to-end detection pipeline, supported by a real-time Flask web application.

🔍 Project Highlights
Multimodal Input Handling: Utilizes both textual and visual content to identify abusive behavior online.

Text Classification: Implemented an LSTM model to classify comments as abusive or non-abusive, achieving 90.7% training accuracy.

Image Classification: Leveraged a VGG16 CNN to detect unsafe imagery, trained on a balanced dataset of labeled images.

Data Engineering: Built data pipelines for cleaning, transforming, and batching data using Pandas, NumPy, and Keras utilities.

EDA & Visualization: Performed exploratory data analysis and visualized model performance using Matplotlib and Seaborn.

Deployment: Developed a Flask web application for real-time predictions based on user-provided messages and images.

Scalable Design: Codebase structured for integration with SQL databases, cloud storage (AWS/GCP), and workflow tools like Airflow (future scope).

🛠️ Tech Stack
Languages & Frameworks: Python, Flask, HTML/CSS

Libraries: TensorFlow, Keras, Pandas, NumPy, Matplotlib, Seaborn

Models Used: LSTM (text), VGG16 CNN (images)

Tools: Jupyter, Pickle, ImageDataGenerator, LabelEncoder
