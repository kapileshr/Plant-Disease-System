# Plant-Disease-System
🌿 Welcome to the Plant Disease Recognition System! 🔍

Our mission is to help in identifying plant diseases efficiently. Upload an image of a plant, and our system will analyze it to detect any signs of diseases.

📂 About the Dataset

This dataset is recreated using offline augmentation from the original dataset. The original dataset can be found on this GitHub repository.

🔹 Dataset Overview:

This dataset consists of about 87K RGB images of healthy and diseased crop leaves.

The dataset is categorized into 38 different classes.

It is divided into an 80/20 ratio for training and validation while preserving the directory structure.

A separate directory containing 33 test images is created later for prediction purposes.

DataSet link : https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

📁 Dataset Structure:

Train Set - 70,295 images

Test Set - 33 images

Validation Set - 17,572 images

🚀 How It Works

Upload Image: Navigate to the Disease Recognition page and upload an image of a plant with suspected diseases.

Analysis: The system processes the image using Convolutional Neural Networks (CNN) and Deep Learning to identify potential diseases.

Results: The model predicts the disease and provides recommendations for further action.

🛠️ Technologies Used

Python 

TensorFlow/Keras for Deep Learning

OpenCV for Image Processing

Streamlit for Web App Development

NumPy & Pandas for Data Handling

Matplotlib & Seaborn for Data Visualization

🏁 How to Get Started

1️⃣ Clone the Repository

git clone https://github.com/kapileshr/Plant-Disease-System.git
cd Plant-Disease-System

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Streamlit App

streamlit run main.py

📜 About Us

This project was created to assist farmers and agricultural researchers in detecting plant diseases early, reducing crop loss, and improving productivity. 🌱💡

For any questions or contributions, feel free to raise an issue or contribute to the repository!

🚀 Let's revolutionize plant disease detection together!
