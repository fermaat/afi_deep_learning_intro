# Deep Learning Foundations – Hands-On Course

This repository contains a complete, low-level deep learning course built from scratch. It is designed to help learners truly understand the foundational concepts of deep learning through hands-on experimentation and minimal abstraction.

## 🚀 What is this about?

- Emphasis on **foundational understanding** with low-level code
- Carefully structured practicals and exercises
- Covers all critical topics in a typical DL curriculum
- Ideal for learners transitioning from traditional ML to DL

---

## 📁 Repository Structure

- **Complete/** — Instructor notebooks with full solutions and explanations.
- **Training/** — Student notebooks with exercises and suggestions for practice.
- **data/** — Datasets used in the assignments (e.g., `heart.csv`).
- **models/** — Saved models and related files.
- **Theory/** - Theoretical material, slides, or markdown notes 
- `requirements.txt`, `requirements_windows.txt` — Python dependencies for Linux/Mac and Windows.
- `README.md` — This file.

Please note each pair of notebooks on **Training** and **Complete** covers the same topic, so learners can practice and later consult the full solution.

## 📚 Topics Covered

- Neural networks vs traditional ML (MNIST, CIFAR-10)
- Activation functions
- Optimization algorithms (SGD, Adam, etc.)
- Learning rate strategies
- TensorBoard usage (basics and advanced)
- Model regularization
- Hyperparameter tuning
- PyTorch basics and integration
- Practical classification examples (binary, fashion)

## 🧠 Intended Audience

This course is ideal for:
- Learners with some ML background who want to dive into DL
- Self-taught developers looking for hands-on content
- Educators searching for structured, editable content to use in class

---

## 🛠️ Setup Instructions (a bit old. Would work better on newer versioons of the software)

### Linux (Ubuntu)
```bash
sudo apt install python3-pip
pip3 install virtualenv
virtualenv env_dl_course
source env_dl_course/bin/activate
pip install -r requirements.txt
# For GPU support
pip install -r requirements_gpu.txt
ipython kernel install --user --name=env_dl_course
```

### Windows

1. Install **Python 3.6.8 (64-bit)** from [python.org](https://www.python.org/downloads/windows/)
2. Enable script execution for PowerShell (if needed):
```powershell
Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser
```

---

#### Create and activate environment

```bash
pip install virtualenv
virtualenv env_dl_course
# CMD
.\env_dl_course\Scriptsctivate.bat
# PowerShell
.\env_dl_course\Scriptsctivate.ps1
```

Install requirements:
```bash
pip install -r requirements_windows.txt
pip install notebook
```

For Torch (CPU):
```bash
pip install torch==1.3.1+cpu torchvision==0.4.2+cpu -f https://download.pytorch.org/whl/torch_stable.html
```

Register the Jupyter kernel:
```bash
ipython kernel install --user --name=env_dl_course
```
---

## 📬 Contact

For questions, collaborations, or feedback, feel free to reach out:

📧 Email: fermaat.vl@gmail.com
🧑‍💻 GitHub: [@fermaat](https://github.com/fermaat)
🌐 [Website](https://fermaat.github.io)


