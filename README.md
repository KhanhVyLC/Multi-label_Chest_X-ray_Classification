# Multi-label_Chest_X-ray_Classification

Link Dataset: https://www.kaggle.com/datasets/ashery/chexpert

Developed a memory-safe ensemble classification system to detect thoracic diseases from chest X-ray images using the CheXpert dataset. The system combines multiple CNN architectures (DenseNet121, ResNet50, EfficientNet-B0) in a binary classification framework for each pathology, ensuring efficient training even on large datasets by processing data in manageable chunks. With many training samples (CheXpert Dataset consists of more than 220,000 chest X-ray images from over 65,000 patients) and GPU acceleration, the model effectively addresses multi-label classification while optimizing memory usage.

<img width="550" height="273" alt="image" src="https://github.com/user-attachments/assets/93bc17cd-a0f6-4149-8147-49fab0ce0a5f" />

Overall Performance Summary:
--------------------------------------------------------------------------------
Mean AUC: 0.775 ± 0.159

Mean AP: 0.489 ± 0.329

Mean F1: 0.488 ± 0.315

Mean Sensitivity: 0.542 ± 0.334

Mean Specificity: 0.776 ± 0.249
