# 🖼️ CNN Image Classification: ResNet-18 vs other comparative architectures

## 📌 Overview
This project investigates the performance of **ResNet-18, MobileNetV2, and a custom CNN** for **image classification** on the **CIFAR-10 dataset**. The study evaluates how different architectures affect accuracy, overfitting, and computational efficiency. The models are trained from scratch, and we perform **hyperparameter tuning, dropout regularization, and data augmentation** to optimize performance.

## ✅ Key Features
- ✅ **ResNet-18 trained from scratch** (No pre-trained weights)  
- ✅ **MobileNetV2 implemented for efficient classification**  
- ✅ **Custom CNN architecture tested for comparison**  
- ✅ **Hyperparameter tuning using grid search**  
- ✅ **Regularization (Dropout & Weight Decay) applied**  
- ✅ **Data Augmentation to enhance generalization**  
- ✅ **Evaluation using Stratified K-Fold Cross-Validation**  

## 🛠 Tech Stack
- **Programming:** Python  
- **Frameworks:** PyTorch  
- **Libraries:** torchvision, NumPy, Matplotlib  
- **Techniques:** CNNs, Batch Normalization, Data Augmentation  

## 📊 Results
| Model | Validation Accuracy |
|--------|------------------|
| **ResNet-18 (Best Model)** | **81.91%** |
| MobileNetV2 | 59.44% |
| Custom CNN | 67.88% |

## 🚀 How to Run
```bash
git clone https://github.com/Pamalrojitha/CNN_Image_Classification.git
cd CNN_Image_Classification
pip install -r requirements.txt
jupyter notebook
