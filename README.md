📁 1. README – Image Preprocessing Project (Hands On.py)
🖼️ Image Preprocessing using TensorFlow & Matplotlib
📌 Overview

This project demonstrates basic image preprocessing steps such as loading, resizing, normalization, and visualization using Python libraries. It is useful as a foundation for deep learning and computer vision tasks.

🎯 Objective
Load an image from local system
Resize it to a fixed dimension
Convert to array format
Normalize pixel values
Display the processed image
🛠️ Technologies Used
Python 🐍
NumPy
Matplotlib
TensorFlow / Keras
🔍 Workflow
Upload image using Google Colab
Load image using Keras preprocessing
Resize image to (128, 128)
Convert image to NumPy array
Normalize pixel values (0–1)
Add batch dimension
Display image
💻 Code Highlights
img = image.load_img("Krishna.jpg", target_size=(128, 128))
img_array = image.img_to_array(img)
img_array = img_array / 255.0
img_array = np.expand_dims(img_array, axis=0)
▶️ How to Run
pip install tensorflow matplotlib numpy
python Hands\ On.py
📊 Output
Displays the processed image using Matplotlib
Image is normalized and ready for ML models
🚀 Future Improvements
Add image augmentation
Support multiple images
Integrate with CNN model
