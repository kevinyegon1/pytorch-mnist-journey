\# 🧠 PyTorch Digit Classifier: From Linear to CNN



A hands-on exploration of Deep Learning using PyTorch. This project tracks the evolution from a basic Neural Network to a high-performance \*\*Convolutional Neural Network (CNN)\*\* capable of recognizing handwritten digits with near-human accuracy.







\## 🚀 Project Evolution

In this project, I implemented two different architectures to solve the MNIST digit classification problem:

1\.  \*\*Fully Connected Network:\*\* A basic "Linear" approach (Baseline).

2\.  \*\*CNN (Convolutional Neural Network):\*\* An advanced architecture that uses spatial filters to identify patterns like loops and lines.



\## 📈 Results

| Model | Accuracy | Training Time |

| :--- | :--- | :--- |

| Simple Linear | ~92.0% | < 1 min |

| \*\*Convolutional (CNN)\*\* | \*\*~99.1%\*\* | \*\*~3 mins\*\* |



---



\## 🛠️ Tech Stack

\* \*\*Framework:\*\* \[PyTorch](https://pytorch.org/)

\* \*\*Dataset:\*\* MNIST (Handwritten digits)

\* \*\*Libraries:\*\* `torchvision`, `matplotlib`, `numpy`

\* \*\*Optimizer:\*\* Adam



---



\## 📁 Repository Structure

\* `main.py`: The complete training and evaluation pipeline.

\* `requirements.txt`: List of Python dependencies.

\* `.gitignore`: Set up to keep the large `/data` folder out of the repository.

\* `mnist\_cnn.pth`: The trained model weights (save/load functionality).



---



\## 💻 Getting Started



\### 1. Clone the repo

```bash

git clone \[https://github.com/YOUR\_USERNAME/pytorch-mnist-journey.git](https://github.com/YOUR\_USERNAME/pytorch-mnist-journey.git)

cd pytorch-mnist-journey

