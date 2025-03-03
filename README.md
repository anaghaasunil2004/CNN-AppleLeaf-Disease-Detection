# CNN-AppleLeaf-Disease-Detection

---



This repository contains a **Convolutional Neural Network (CNN)** model for detecting apple leaf diseases. The model classifies leaves into **Healthy, Rust, Scab, or Multiple Diseases**.

![image](https://github.com/user-attachments/assets/fc648d8a-9d7e-426c-8205-b70d4d737345)![image](https://github.com/user-attachments/assets/5c8525cb-057d-4a16-af33-b9becdda3045)![image](https://github.com/user-attachments/assets/7373b489-1ca5-434c-b42b-bafe6d691db1)![image](https://github.com/user-attachments/assets/2fa3d99d-28da-4e52-b16c-b0571ecd1bdb)

## Dataset
- Dataset: [Plant Pathology 2020 - FGVC7 | Kaggle](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7)
- Contains labeled images of apple leaves.

## Model Overview
- **Custom CNN architecture** with multiple convolutional layers.
- Uses **ReLU activation** and **Max Pooling** for feature extraction.
- **Fully Connected Layers** with a **Softmax classifier** for final predictions.

## Installation & Requirements
To run this project, install dependencies:
```bash
pip install tensorflow keras numpy pandas matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CNN-AppleLeaf-Disease-Detection.git
   cd CNN-AppleLeaf-Disease-Detection
   ```
2. Open and run `cnn_final.ipynb` in Jupyter Notebook or Google Colab.
3. Load the dataset and train the model.

## Results
- Achieved **65% accuracy**.
- Struggles with complex disease patterns compared to deeper models.

## Future Improvements
- Adding more layers or using **pre-trained models**.
- Implementing **data augmentation** for better generalization.

## License
This project is licensed under the **MIT License**.
