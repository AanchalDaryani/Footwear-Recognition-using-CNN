# Footwear-Recognition-using-CNN

## Introduction :
E-commerce has rapidly grown, and their business strategies are based on user actions and experiences. Accurate product classification is crucial for improving catalogs and providing the best suggestions to users. This project aims to build a Convolutional Neural Network (CNN) to classify types of footwear products.


## Objective : 
Given the images of a product with multiple categories, train a model which can classify the type of a product.

## Data Description : 
- **Dataset:** Data is all about images of shoes with multiple categories and data is collected from a popular Ecommerce site. Data set consists of two folders train and test.
- **Training Data:** 623 images belonging to 3 classes
- **Test Data:** 155 images belonging to 3 classes
- **Classes:**   Sandals, Boots, Slippers

## Model Building
1. **Image Preprocessing:** Applied rescaling, shear range, horizontal flip, and zoom range for data augmentation.
2. **Visualization:** Displayed images of different classes (sandals, boots, slippers).
3. **Model Architecture:** 
   - The model contains a total of 11 layers, including 4 convolutional layers, 4 max-pooling layers, a flatten layer, a fully connected layer, and an output layer.
4. **Performance:**
   - Validation Accuracy: 0.90
   - Validation Loss: 0.39

## Conclusion : 
The model performs well in classifying footwear images with a validation accuracy of 0.90. Future improvements can be made by incorporating more data, fine-tuning hyperparameters, and adding more layers to the model.


