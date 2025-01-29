# * Music Recommendation using Deep Learning*  

## *📌 Overview*  
This project detects human emotions from facial images using a *Convolutional Neural Network (CNN)* and recommends music based on the detected emotions. Implemented with **Python, TensorFlow, Keras, and OpenCV**, it runs on **Google Colab**.  

---  

## *📂 Dataset*  
✅ *Training Data* – Facial images categorized into seven emotions (Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise).  
✅ *Testing Data* – Similar dataset used for model evaluation.  

Images are preprocessed and normalized for better performance.  

---  

## *📌 Model Architecture*  
✔ *4 Convolutional Layers* with ReLU activation  
✔ *Batch Normalization & MaxPooling*  
✔ *Dropout Layers* to prevent overfitting  
✔ *Dense Layers* with Softmax Activation* for multi-class classification  

The model classifies images into *7 emotion categories*.  

---  

## *📊 Training & Evaluation*  
✅ *Categorical Crossentropy Loss*  
✅ *Adam Optimizer*  
✅ *Data Augmentation*  
✅ *Early Stopping* to prevent overfitting  

---  

---  

## *📌 How to Use*  
1️⃣ Upload an image to Colab.  
2️⃣ The model predicts the detected emotion.  
3️⃣ Recommends music based on the predicted emotion.  

---  

## *🚀 Technologies Used*  
✔ *Python*  
✔ *TensorFlow / Keras*  
✔ *OpenCV*  
✔ *NumPy & Pandas*  
✔ *Matplotlib*  

---  

## *📌 Run Locally*  
```bash  
git clone https://github.com/yourusername/Emotion-Music-Recommendation.git  
cd Emotion-Music-Recommendation  
pip install -r requirements.txt  
python predict.py --image test.jpg  
```  

---  

## *🔗 Credits*  
🔹 *Author:* Thulasi Sandeep
🔹 *GitHub Repository:* [Emotion Music Recommendation](https://github.com/THULASISANDEEP/Emotion-Music-Recommendation)  

---
