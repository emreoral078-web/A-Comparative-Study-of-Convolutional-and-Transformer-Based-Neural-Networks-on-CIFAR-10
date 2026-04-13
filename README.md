# A Comparative Study of Convolutional and Transformer-Based Neural Networks on CIFAR-10

This repository contains the final research report for the **EE443: Neural Networks** course. The project investigates the performance trade-offs between traditional Convolutional Neural Networks (CNNs) and modern Transformer-based architectures when applied to small-scale image datasets.

##  Author
* **Emre Oral** (Group 31) - Bilkent University

##  Project Overview
The core objective of this study is to determine whether Vision Transformers (ViTs) can outperform established CNN architectures on the **CIFAR-10** dataset when trained from scratch. 

The study evaluates three specific models:
1. **ResNet-18:** Representing standard residual learning.
2. **DenseNet-121:** Representing dense connectivity and feature reuse.
3. **DeiT-Tiny (Data-efficient Image Transformer):** Representing a compact transformer-based approach.

##  Key Findings
* **CNN Superiority:** On small-scale datasets like CIFAR-10, CNNs (ResNet and DenseNet) significantly outperform Transformer-based models in both accuracy and training speed.
* **ResNet-18 Performance:** Achieved the best overall results, proving highly effective for general image classification tasks.
* **DeiT-Tiny Limitations:** Showed lower accuracy and required significantly longer training times, highlighting the challenges Transformers face without large-scale pre-training or massive datasets.
* **Efficiency:** DenseNet-121 provided a highly competitive alternative to ResNet while maintaining a lower parameter count.

##  Repository Structure
* `Emre-Oral-31-final.pdf`: The complete academic report detailing the methodology, experimental setup, hyperparameters, and detailed performance analysis.
* `README.md`: Project documentation and summary of findings.

##  Experimental Setup
* **Dataset:** CIFAR-10 (60,000 32x32 color images in 10 classes)
* **Framework:** PyTorch / TensorFlow
* **Metrics:** Top-1 Accuracy, Training Time (minutes), Parameter Efficiency, and Class-wise Performance.

## 🎓 Conclusion
The results confirm that while Transformers are revolutionary for large-scale vision tasks, CNNs remains the more robust and efficient choice for smaller, localized datasets like CIFAR-10 due to their inherent inductive biases (locality and translation invariance).
