# pH Prediction using Vision Transformer (ViT)

This project explores the use of **Vision Transformers (ViT)** for predicting **soil pH values** from satellite imagery.  
Currently, the model is trained on **synthetically generated dummy data** for demonstration purposes.  
The repository serves as a proof of concept and a starting point for future work with real-world datasets.

---

## 📂 Repository Structure

```bash
├── satellite_data/      # Sample satellite-like input images (dummy)
├── saved_models/        # Trained ViT model checkpoints
├── labels.csv           # Dummy pH labels for the dataset
├── model.ipynb          # Jupyter Notebook with model training pipeline
├── requirements.txt     # Required dependencies
├── README.md            # Project documentation
└── .gitignore
```

---

## 🚀 Features

- Implements a **Vision Transformer (ViT)** architecture for regression tasks.  
- Demonstrates training on synthetic data (pH labels randomly generated).  
- Modular structure for easy adaptation to real-world satellite/soil data.  
- Includes model saving and loading functionality.

---

## ⚙️ Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/rudra-swnt-12/Soil-pH-ViT.git
cd pH_prediction_using-ViT
pip install -r requirements.txt
```

---

## 📊 Usage

Open the Jupyter notebook:

```bash
jupyter notebook model.ipynb
```

Run through the cells to:

- Load dummy data
- Train the Vision Transformer
- Evaluate model performance

---

## 📈 Results

Since the training data is randomly generated, the results are not meaningful.  
The purpose of this repo is to demonstrate the workflow and architecture setup.  
Once real satellite + soil pH data is available, the same pipeline can be applied for actual prediction tasks.

---

## 🔮 Future Work

- Integrate real multispectral/hyperspectral satellite data.
- Calibrate the model with ground-truth soil pH measurements.
- Experiment with hybrid architectures (CNN + ViT).
- Contributions of real-world datasets are highly welcome to make the project more impactful.

---

## 📝 License

This project is licensed under the MIT License.

## 🏷️ Badges

![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)