# Image-Classification-with-Hugging-Face-Transformers

This project was created to perform Image Classification while using Huggin Face Transformers for Computer Vision application.

Hugging Face Transformers package is very popular and versatile Python library that provides pre-trained models for a variety of applications in Computer Vision, as well other areas such as Text classification , audio analysis, multimodal analysis (optical character recognition, video classification, visual question answering and many more).

# Dataset: sasha/dog-food 
(https://huggingface.co/datasets/sasha/dog-food)

The Dataset consists of 3000 images, where 66.7% are images of food and 33.3% are of dogs.

There were some funny Memes going around in the internet, showing how Machine Learning algorithms gets confused between Dogs and Food. The example images are given below:

![image](https://github.com/user-attachments/assets/3c5105e5-6985-4a0e-93de-a255dc37510e)

![image](https://github.com/user-attachments/assets/0d5176e8-492d-4c11-b532-20ea05b45d4a)

# Performance of Vision Transformer

Hence, to perform this binary classification task, a Vision Transformer (ViT) is used. 
In the main GitHub repository (https://github.com/qw2243c/Image-Recognition-Dogs-Fried-Chicken-or-Blueberry-Muffins-.git), the classification was performed using the given Deep-learning models:

![image](https://github.com/user-attachments/assets/fd7e0eb4-ad53-47ff-ae51-2d2828a000fe)

However, using the Vision Transformer outperforms the above-mentioned models with the training process achieving 

![Screenshot from 2024-08-18 15-47-18](https://github.com/user-attachments/assets/11aa4c9d-3e7a-4625-96fa-04672efd2e6b)

The evaluation done on the test dataset is given by a Confusion Matrix:

![Screenshot from 2024-08-18 15-49-48](https://github.com/user-attachments/assets/0a55de37-c4a0-4d01-9f4e-c14a31b1abef)
