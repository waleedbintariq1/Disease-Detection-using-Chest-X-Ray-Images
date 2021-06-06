# Disease-Detection-using-Chest-X-Ray-Images
Research and development project where the purpose is to develop a model that is able to classify from amongst five chest diseases using chest X-Ray images. Transfer learning technique is used.

# Diseases to be classified
1. COVID-19
2. Cardiomegaly
3. Infiltration
4. Atelectasis
5. Effusion

# Model Architectures trained
1. Vgg16
2. Inception v3
3. Efficient Net B5
4. Efficient Net B7

# Procedure
1. Collected publicly available chest x-ray dataset from kaggle.com
2. Trained multiple models using ImageNet weights as a starting point
3. Selected best performing model which was Inception v3
4. Fine tuned the hyper parameters to improve performance
5. Upscaled and downscaled the disease data so that each disease has same amount of images
6. Performed data augmentation for upscaling the data
8. Developed web application using Flask framework
9. Integrated trained model into the web application
