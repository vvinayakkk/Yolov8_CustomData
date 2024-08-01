# Personal Protective Equipment Detection Using Yolov8

## Overview

This project focuses on detecting and classifying Personal Protective Equipment (PPE) such as helmets, goggles, jackets, gloves, and footwear using a custom dataset. The goal is to ensure compliance with safety standards by accurately identifying the presence of these protective items in images.

## Methodology

The project utilizes the YOLO (You Only Look Once) object detection framework, chosen for its efficiency in real-time detection. YOLO's ability to perform object localization and classification in a single forward pass makes it ideal for this application. The process involved:

1. **Data Collection**: A custom dataset was created, containing images labeled for the presence of PPE items: Helmet, Goggles, Jacket, Gloves, and Footwear.
2. **Data Preprocessing**: Images were resized and normalized to fit the input requirements of the YOLO model. Annotations were converted into the YOLO format.
3. **Model Training**: The YOLO model was trained on the custom dataset. The training involved fine-tuning a pre-trained YOLO model on the specific PPE classes.
4. **Evaluation**: The model's performance was evaluated using metrics such as mean Average Precision (mAP) and Intersection over Union (IoU).
5. **Deployment**: The trained model was deployed for inference, capable of detecting and classifying PPE in real-time.

![Screenshot 2024-08-01 224453](https://github.com/user-attachments/assets/513f5c45-74e1-4930-8a50-b3f183296e36)
![Screenshot 2024-08-01 224501](https://github.com/user-attachments/assets/7655b740-4dbe-4dbb-9d08-f8e985a14589)
![Screenshot 2024-08-01 224507](https://github.com/user-attachments/assets/ec7d2871-4d21-493d-9273-5e831888fc2e)



## Advantages

- **Real-Time Detection**: The use of YOLO allows for real-time detection and classification of PPE, making it suitable for applications requiring immediate feedback.
- **High Accuracy**: The model is trained specifically on a custom dataset, ensuring high accuracy for detecting the targeted PPE items.
- **Scalability**: The system can be extended to include additional PPE items or other safety equipment by retraining the model on an updated dataset.

## Conclusion

This project demonstrates the effectiveness of using the YOLO object detection framework for identifying PPE in images. The model's high accuracy and real-time detection capabilities make it a valuable tool for enhancing workplace safety.
