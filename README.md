# 🧠 CIFAR-10 Image Classification using PyTorch

A simple Convolutional Neural Network (CNN) built with PyTorch to classify images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) into 10 categories:


['plane', 'car', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck']

---

## 📌 Features

- Built using PyTorch
- Custom CNN architecture
- Achieved **68.46% accuracy** on test set
- Trained on the CIFAR-10 dataset
- Includes preprocessing, training, evaluation, and sample predictions

---

## 📁 Dataset

The project uses the **CIFAR-10** dataset, which contains:

- 60,000 32x32 color images
- 10 classes
- 50,000 training images, 10,000 test images

You can load it using:

```python
import torchvision.datasets as datasets
trainset = datasets.CIFAR10(root='./data', train=True, download=True)
```

### 📊 Accuracy

Final Accuracy on Test Set: 68.46%

| Image                 | Ground Truth | Predicted |
| --------------------- | ------------ | --------- |
| ![plan](https://github.com/user-attachments/assets/b4ed6e81-1c04-4479-843b-7979058c7282) | plane        | plane     |
| ![cat](https://github.com/user-attachments/assets/6d638b8d-8062-47f5-9dc3-f4aac2c1fb56)   | cat          | dog       |
| ![Ship01](https://github.com/user-attachments/assets/bae780b2-1d3b-4956-ab58-56935f74fca4) | ship         | ship      |

## 💡 Future Improvements
Add dropout for regularization

Try pretrained models like ResNet

Increase accuracy beyond 80%

Visualize the confusion matrix and misclassified images

