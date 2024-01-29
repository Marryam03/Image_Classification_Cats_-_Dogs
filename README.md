A deep learning model that classifies images of cats and dogs using transfer learning with InceptionResNetV2. The project used TensorFlow and Keras for model development. 

Steps:
1) Data Augmentation: Data augmentation techniques are applied to the training set to enhance model generalization. Augmentation includes rotation, width and height shifting, preprocessing, shear, zoom, and horizontal flip.

2) Data Processing & Visualization: The script connects data generators to image folders, processes the data, and visualizes examples from the dataset. The number of samples, classes, and class names are displayed.

3) Transfer Learning: The InceptionResNetV2 model pre-trained on ImageNet is used as a base model. Additional layers are added, and pre-trained layers are frozen. The model is compiled using categorical crossentropy loss and Adam optimizer.

4) Model Training: The model is trained on the augmented data with early stopping and model checkpoint callbacks. Training progress, including loss and accuracy, is displayed.

5) Learning Curves: Training and validation loss, as well as accuracy, are visualized over epochs to assess model performance.

6) Model Evaluation: The model is evaluated on both the validation and test datasets, and the results, including loss and accuracy, are printed. A confusion matrix with a heatmap is generated for further evaluation.
