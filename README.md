# Lung-Nodules-Detection-and-Classification-using-UNet-DenseNet

Achieved an accuracy of 99.96 % on Luna-16 dataset .

Problem Statement

 Lung Nodule detection using Deep Learning
The detection of lung cancer stands as a critical global health priority, emphasizing the significance of early identification for improved patient outcomes. Recent advancements in medical imaging have showcased the exceptional potential of deep learning techniques in addressing this concern. This study delves into the exploration of U-Net and DenseNet, two influential deep learning models, for the task of lung cancer detection using medical imaging data. The proposed methodology harnesses U-Net, a convolutional neural network (CNN) known for its adeptness in semantic segmentation, and DenseNet, a hybrid architecture characterized by dense connections among layers, to automate lung cancer detection from 3D computed tomography (CT) scans.

•Project Scope
1.	Develop a machine learning (ML) model for lung cancer detection using U-Net and DenseNet architectures.
2.	Achieve an accuracy of at least 99.96% in lung nodule detection and classification.
3.  Achieved validation of 99.9%. 
5.	Package the model into a user-friendly web application accessible to healthcare professionals.
6.	Integrate the model seamlessly with existing medical imaging workflows for efficient clinical use.


•	Data Requirements:
1.	Large dataset of CT scans annotated with lung nodules:
2.	Minimum of 10,000 CT scans with diverse patient demographics.
3.	Each CT scan is labeled with individual nodules, categorized as benign or malignant.
4.	Standard format compatible with deep learning models (e.g., DICOM, NIfTI).
5.	Additional clinical data (optional):
6.	Patient demographics (age, gender, smoking history).
7.	Histopathological diagnosis for confirmed cases.
8.	Treatment history and follow-up data.
9.	Training and Evaluation Methodology.

•	Data Preprocessing:

1.	Standardize CT scans to a specific resolution and voxel size.
2.	Apply normalization techniques to adjust intensity values.
3.	Segment lung regions and isolate individual nodules using image processing techniques.
4.	Augment the data (optional) to increase model generalizability by adding artificial variations.
5.	Split the data into training, validation, and testing sets.


•	 Model Training:

1.	Combine U-Net architecture for nodule segmentation with DenseNet architecture for classification.
2.	Fine-tune the pre-trained U-Net and DenseNet models on the lung nodule dataset.
3.	Utilize appropriate loss functions tailored to nodule segmentation and classification.
4.	Optimize hyperparameters (learning rate, optimizer settings) for optimal performance.
5.	Monitor training progress on the validation set and adjust parameters accordingly.



•	Model Evaluation:

1.	Evaluate the trained model's performance on the testing set.
2.	Calculate accuracy, sensitivity, specificity, and other relevant metrics.
3.	Analyze the model's strengths and weaknesses, focusing on false positives and negatives.
4.	Utilize visualization techniques and saliency maps to understand the decision-making process.


•	Model Optimization:

1.	Implement techniques like hyperparameter tuning and data augmentation to improve performance.
2.	Explore ensemble learning approaches by combining multiple models for enhanced accuracy.
3.	Consider incorporating explainability methods like SHAP values for transparency and trust.

![Testing Results](https://github.com/abhikrm0102/Lung-Nodules-Detection-and-Classification-using-UNet-DenseNet/assets/153391038/4fb45f12-7f7d-479e-8f96-cd2c0b1c7c58)

