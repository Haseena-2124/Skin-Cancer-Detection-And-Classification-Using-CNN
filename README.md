# Skin-Cancer-Detection-And-Classification-Using-CNN
Skin cancer is one of the most serious cancers in the world. The abnormal growth of skin cells is referred to as skin cancer. It occurs when the DNA in skin cells is damaged, or our skin is over exposure to sunlight. We have 7 different classes of skin cancer such as "Melanocytic nevi ", "Melanoma", "Benign keratosis-like lesions", "Basal cell carcinoma", "Actinic Keratoses", "Vascular lesions", "Dermatofibroma". In the past decade (2013-2023) the number of melanoma cases diagnosed annually increased by 27 percent. Most of the existing models predict Melanoma cancer only but our proposed system is going to detect and classify 7 different classes of skin cancer. Machine learning algorithm-based methods help dermatologists in classifying images. We are going to propose a model with a deep learning-based method using convolutional neural networks to detect and classify skin cancer in the early stages. We collected a dataset from the Modified National Institute of Standard and Technology Human Against Machine (MNIST-HAM10000) containing 10,000 dermoscopy images to train our model. The best accuracy this model could achieve is 96%.
#DATA-SET
https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000
#Libraries used
numpy
keras
tensorflow
pandas
matplotlib
pillow
flask
seaborn
#Skin cancer.ipynb
This is the Jupyter notebook used to define and train the model.
#app.py
Used to run the web app
#How to run app.py
Run the app.py file in vs code
Go to http://localhost:5000/ on your browser
Use the Upload and button to browse and upload the image you want
Hit submit to get the results.
