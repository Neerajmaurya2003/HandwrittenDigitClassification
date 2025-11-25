# 🧠 Handwritten Digit Classification using Deep Learning (PyTorch)

This repository contains my first deep learning project — a neural network built using **PyTorch** to classify handwritten digits from the **MNIST dataset**. The model was trained and evaluated using end-to-end deep learning workflow, achieving an accuracy of **96.71%** on the test dataset.

---

## 🚀 Features
- Built a Multilayer Perceptron (MLP) using **PyTorch**
- Data preprocessing with normalization and batching via `DataLoader`
- Forward & backward propagation with **Autograd**
- Model evaluation using accuracy and loss metrics
- Visualization of loss/accuracy trends during training

---

## 🔧 Tech Stack
| Component | Technology |
|----------|------------|
| Language | Python |
| Framework | PyTorch |
| Dataset | MNIST |
| Libraries | NumPy, Pandas, Matplotlib, Torchvision |

---

## 📂 Repository Structure
├── HandwrittenDigitClassification.ipynb # Main project notebook<br>
└── README.md # Project documentation


---

## 🧠 Model Training Workflow
1. Load MNIST dataset with Torchvision
2. Normalize images and prepare DataLoader
3. Define MLP architecture using `torch.nn`
4. Train using optimizer + loss backpropagation
5. Evaluate on test dataset and visualize metrics

---

## 📌 Results
| Metric | Score |<br>
| Test Accuracy | **96.71%** |<br>
| Loss | Reduced progressively across epochs |

---


## 🛠️ How to Run the Notebook
```bash
git clone <your_repo_link>
cd <repo_directory>
pip install -r requirements.txt   # Optional if using a requirements file

