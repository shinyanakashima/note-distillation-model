# ⚗Knowledge Distillation with CIFAR-10⚗

This project validates **knowledge distillation in machine learning**.  
We use the **CIFAR-10 dataset** and perform knowledge distillation  
with **ResNet18 as the teacher model**, training a more lightweight student model.

## Implementation Details
- **Teacher Model**: Pre-trained ResNet18 (`pretrained=True`)
- **Student Model**: ResNet18 trained from scratch (`pretrained=False`)
- **Both models use ResNet18**, but the final fully connected (`fc`) layer is modified for CIFAR-10 (10 classes).
- **Distillation Method**: Soft target learning using KL-Divergence
- **Dataset**: CIFAR-10

## How to Use
This project is implemented as a **Google Colab Notebook**.  
To run the notebook, open it in Google Colab and follow the provided instructions.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cshyj5sk1qJCr1ifQPPmswCUf7vDrbv5?usp=sharing)
