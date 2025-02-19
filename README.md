# Melanoma_Detection
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Skin cancer is a deadly disease that can be life-threatening if not detected early. This project aims to build a CNN-based model that accurately detects melanoma, the deadliest form of skin cancer. The model evaluates images and alerts dermatologists about the presence of melanoma, reducing the manual effort needed for diagnosis.

Dataset
The Dataset can be downloaded from Here.

The dataset used in this project consists of 2357 images of malignant and benign oncological diseases, sourced from the International Skin Imaging Collaboration (ISIC). The dataset contains nine sub-directories, each representing a specific type of skin cancer:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
The dataset was divided into training and testing sets, with approximately 80% of the images used for training and 20% for validation.

Technologies Used
Python
TensorFlow
Keras
Augmentor
NumPy
Matplotlib
OpenCV
PIL
Model Architecture
The CNN model used in this project consists of several convolutional and pooling layers, followed by fully connected layers. The model was trained to classify the nine different types of skin cancer present in the dataset. Data augmentation techniques, such as random flipping, rotation, and zoom, were applied to handle class imbalances and improve model performance.

Results
After training the model for around 50 epochs, the following results were achieved:

Training Accuracy: 80%
Validation Accuracy: 75%
Training Loss: 0.5
Validation Loss: 0.8
The model showed significant improvement in accuracy and reduced overfitting compared to earlier versions. Class rebalancing using data augmentation played a crucial role in achieving these results.

Conclusion
The developed CNN model shows promising results in accurately detecting different types of skin cancer. By leveraging deep learning techniques and data augmentation, the model can assist dermatologists in diagnosing melanoma and other skin cancer types. Further improvements can be made by collecting more diverse and balanced datasets and fine-tuning the model architecture.

Feel free to contribute to this project and adapt it to your specific needs.


