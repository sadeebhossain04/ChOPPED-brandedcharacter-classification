# ChOPPED-brandedcharacter-classification
# ChOPPED-brandedcharacter-classification

This repository contains the source code for the **ChOPPED** system:  
**Child-Oriented Product Promotion Evaluation & Detection** — a deep learning-based AI pipeline developed to classify branded characters in digital food marketing targeted at children.

This work was conducted as part of the Bachelor of Health Sciences Honours Thesis at the University of Calgary (March 2025).

## 📂 Project Structure

\`\`\`
ChOPPED-AI/
├── models/
│   ├── cnn_model.ipynb
│   └── resnet_model.ipynb
├── utils/
│   └── data_utils.py
├── figures/
│   └── confusion_matrix.png
├── README.md
├── requirements.txt
└── .gitignore
\`\`\`

## 🧠 Project Description

The ChOPPED system is a seven-module AI pipeline that automates the classification of branded characters in food advertisements. It contributes to broader efforts to monitor compliance with Canada's upcoming **Child Health Protection Act (CHPA)**.

The models were trained using a curated dataset of ~1,400 annotated frames from YouTube ads, featuring ten branded food characters.

## 📊 Models

- `cnn_model.ipynb`: A custom convolutional neural network.
- `resnet_model.ipynb`: A transfer learning model using ResNet-18.

## 🖼️ Dataset

Due to GitHub file size limitations, the dataset is hosted externally.

📥 **Download here:**  
[Google Drive Dataset Link](https://drive.google.com/your-link-here)

## 🛠️ Requirements

- Python 3.10+
- Jupyter Notebook
- PyTorch
- torchvision
- numpy
- matplotlib
- scikit-learn
- opencv-python

Install via:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

## ▶️ How to Run

1. Clone the repository:

\`\`\`bash
git clone https://github.com/sadeebhossain04/ChOPPED-brandedcharacter-classification.git
cd ChOPPED-brandedcharacter-classification
\`\`\`

2. Launch Jupyter:

\`\`\`bash
jupyter notebook
\`\`\`

3. Run the models inside `models/`.

## 📖 Citation

> Hossain, S. (2025). *Enhancing Artificial Intelligence Classification of Branded Characters in Digital Food Marketing to Children for Improved Compliance Under Canada’s Upcoming Child Health Protection Act* (Undergraduate thesis). University of Calgary.

## 🔐 License

For academic use only. Contact the author for permission regarding reuse or redistribution.
