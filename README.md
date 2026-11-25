# OceanTrace-AI
### **OceanTrace AI – Project Explanation**

This project presents a Deep Learning and Generative AI approach for analyzing underwater images to support marine pollution awareness. The main objective is to identify image content, generate descriptions, and provide preliminary information about possible marine pollution.

The methodology starts with preparing and exploring an underwater image dataset containing 5,130 images. The images are organized into training, validation, and testing datasets. A Convolutional Neural Network (CNN) is developed using TensorFlow and Keras for image classification.

Next, the BLIP model is used to generate captions for underwater images. The FLAN-T5 model uses these captions to generate text-based reports. Two sample images are analyzed and compared using visualizations.

The project demonstrates how CNN, BLIP, and FLAN-T5 can be combined for underwater image analysis and marine pollution awareness. The current dataset has only one detected class, so further work is needed for reliable multi-class classification.

