
# RescueNet_M

## Overview
The goal of this project is to build and train a simple object detection model capable of identifying objects and their corresponding bounding boxes within an image. The dataset is preprocessed, and the model is trained using custom data generators, followed by evaluation and visualization of the results..



 
## Key Feature
- Custom Dataset: The dataset is downloaded from Kaggle and includes training, validation, and test images with YOLO-formatted annotations.
- CNN Model: A simple CNN is used for feature extraction and object detection.
- Custom Data Generators: Custom data generators are implemented to load and preprocess the dataset in batches.
- Training and Evaluation: The model is trained for multiple epochs and evaluated on validation data. Results are visualized using loss plots for both training and validation sets.

## Dataset Information
The dataset is sourced from Kaggle and contains labeled images for object detection. Annotations are provided in the YOLO format, which includes object class labels and bounding box coordinates.
https://www.kaggle.com/datasets/rgbnihal/c2a-dataset

- Training Set: Images and annotations used for training the model.
- Validation Set: Images and annotations used to validate model performance during training.
- Test Set: Held-out images and annotations for final evaluation of the trained model..

## Results and Performance
The trained model’s performance is evaluated using the loss function, and the results are visualized using loss curves for both training and validation sets. The overall objective is to minimize the loss, indicating better object detection performance.

## Future Work
Potential improvements to this project could include:

- Advanced Data Augmentation: Use more sophisticated augmentation techniques to enhance model robustness.
- Model Fine-tuning: Implement pre-trained models or fine-tune the current architecture for better accuracy.
- Custom Loss Function: Refine the custom loss function to better suit object detection tasks, such as using Intersection-over-Union (IoU) based loss.



