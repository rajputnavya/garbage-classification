# Garbage Classification using ResNet 50 (Transfer Learning)
This project is aimed to develop a garbage classification system using the ResNet50 architecture. The primary dataset serves as a foundation for building models that can eventually **automate waste segregation**, a critical step in **optimizing recycling** and **waste management**, ultimately aiding in **environmental conservation**. A notable challenge encountered is the inherent class imbalance within the dataset, prompting the exploration of data augmentation, and varied evaluation metrics. This project journey encompasses a comprehensive dataset analysis, addresses the imbalance, and delves deep into building and evaluating model through transfer learning with ResNet50.

### Objectives:
- **Dataset Exploration:** Dive into the garbage dataset, emphasizing class imbalances.
- **Tackle Imbalance:** Utilize class weights in the loss function to address dataset disparities.
- **Implement Data Augmentation:** Enhance model generalization and combat overfitting.
- **Employ Transfer Learning:** Leverage a pre-trained ResNet50, adapting it for our specific dataset.
- **Evaluate Models:** Assess model's performance using varied metrics (Learning Curves, Performance Matrix & Confusion Matrix) to ensure reliable classification.

### Inference:
- **Average Accuracy: 0.95**
- **Macro Avg. F1 score: 0.94**
- **Weighted Avg. F1 score: 0.95**
  
#### Training Dataset Link:
https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset/data

### Test images classification:
<img width="1159" height="596" alt="Screenshot 2025-11-23 at 10 05 37 PM" src="https://github.com/user-attachments/assets/ba163e5a-b19f-4dd9-b783-af0cef183f93" />
<img width="1157" height="588" alt="Screenshot 2025-11-23 at 10 06 02 PM" src="https://github.com/user-attachments/assets/b2410a85-ddf2-4ed5-9962-53f40e1394da" />
<img width="565" height="296" alt="Screenshot 2025-11-23 at 10 06 23 PM" src="https://github.com/user-attachments/assets/8e04e981-f8a5-4f20-ba44-9bcd2de1873c" />




