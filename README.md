 # 🐾 Animal Image Classification with PyTorch

An image classification project using transfer learning with *ResNet50* in PyTorch to classify animals into multiple categories with training, validation, testing, and inference support.

---
📂 Dataset

Download dataset at: https://drive.google.com/drive/folders/1tCpRwWlnp4jYwTg9dZKssQ-erTaZhFOT?usp=sharing
Contains 15 class folders (Dog, Cat, Tiger, etc.).

Auto-splits into train (70%) / val (15%) / test (15%) if not already split.

## 🚀 Features
- Dataset organization with *train/val/test* split
- Image preprocessing & augmentation using torchvision.transforms
- Transfer learning with *ResNet50 (pretrained on ImageNet)*
- Optimizer: *AdamW*
- Training loop with validation tracking & best model saving
- Model evaluation with classification report & confusion matrix
- Custom inference function to predict top-k classes for new images

---📊 Results

Example validation accuracy after training for 5 epochs: ~85%
(Accuracy will improve with more epochs, larger batch size, or fine-tuning.)

The script outputs:

Training/validation loss & accuracy

Classification report on test data

Confusion matrix heatmap🛠 Tech Stack

Python 3.8+

PyTorch + Torchvision

scikit-learn

Matplotlib & Seaborn

tqdm
