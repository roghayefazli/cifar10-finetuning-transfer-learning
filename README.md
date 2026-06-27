# 🚀 Transfer Learning for Cross-Dataset Image Classification

This repository presents an end-to-end **Transfer Learning pipeline** using TensorFlow and Keras. A convolutional neural network is first pretrained on the **CIFAR-10** dataset and then fine-tuned on multiple downstream image classification tasks to evaluate knowledge transfer across different visual domains.

The project demonstrates how a pretrained model can be reused for new datasets through transfer learning, reducing training time while maintaining competitive performance.

---

# 📌 Project Overview

The workflow consists of three stages:

1. **Pre-training on CIFAR-10**

   * Dataset loading and preprocessing
   * CNN training
   * Model evaluation
   * Saving pretrained weights

2. **Fine-tuning on Coin Classification**

   * Loading pretrained CIFAR-10 weights
   * Replacing the classifier head
   * Fine-tuning on a 6-class coin dataset

3. **Fine-tuning on EuroSAT**

   * Loading pretrained CIFAR-10 weights
   * Transfer learning for remote sensing image classification
   * Evaluation on the EuroSAT benchmark

---

# 🧠 Features

* ✅ End-to-end Transfer Learning pipeline
* ✅ CIFAR-10 model pretraining
* ✅ Cross-dataset fine-tuning
* ✅ Coin image classification
* ✅ EuroSAT land-cover classification
* ✅ Modular TensorFlow/Keras implementation
* ✅ Training and validation visualization
* ✅ Model saving and reuse
* ✅ Easy-to-extend project structure

---

# 📊 Experimental Results

| Stage        | Dataset             | Classes |                    Performance |
| ------------ | ------------------- | ------: | -----------------------------: |
| Pre-training | CIFAR-10            |      10 |       **79.36% Test Accuracy** |
| Fine-tuning  | Coin Classification |       6 |       **78.65% Test Accuracy** |
| Fine-tuning  | EuroSAT             |      10 | **76.74% Validation Accuracy** |

---

# 🛠 Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/roghayefazli/transfer-learning-image-classification.git
cd transfer-learning-image-classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebooks in the following order:

1. CIFAR10_Pretraining.ipynb
2. Coin_FineTuning.ipynb
3. EuroSAT_FineTuning.ipynb

---

# 🔬 Future Improvements

* Evaluate EfficientNet, DenseNet, and MobileNet backbones
* Compare CIFAR-10 and ImageNet pretrained weights
* Add Grad-CAM visualization
* Perform hyperparameter optimization
* Export models for deployment (ONNX / TensorFlow Lite)

---

# 📄 License

This project is released under the MIT License.

---

# 👩‍💻 Author

**Roghaye Fazli**

M.Sc. Student in Artificial Intelligence

GitHub: https://github.com/roghayefazli
