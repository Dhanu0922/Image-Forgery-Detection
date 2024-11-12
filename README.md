#Image-Forgery-Detection using ELA and CNN

Overview
This project is an Image Forgery Detection tool that identifies tampered or manipulated images. It utilizes Error Level Analysis (ELA) and Convolutional Neural Networks (CNN) for effective and accurate forgery detection. The project is implemented in Python using the TensorFlow framework, offering a solution to detect alterations in images, such as splicing or cloning, by highlighting the discrepancies between original and manipulated image areas.

#Features
- Error Level Analysis (ELA)**: ELA is a technique that helps in visualizing compression artifacts, making it easier to spot tampered regions in an image.
- Convolutional Neural Network (CNN)**: A CNN is used to learn from ELA-processed images and classify them as either *original* or *forged*.
- Python-based Implementation**: The project is written in Python, leveraging TensorFlow for building the CNN model.
- Automated Detection: It provides a systematic way to detect image forgeries with minimal manual intervention.

Dataset
https://www.kaggle.com/datasets/divg07/casia-20-image-tampering-detection-dataset

Technologies Used
- Programming Language: Python
- Libraries: TensorFlow, Keras, OpenCV
- Framework: TensorFlow for CNN architecture and training
- Tools: Jupyter Notebook for interactive coding and analysis
