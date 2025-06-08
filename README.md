README.md

# PneumoniaMNIST Classification

This project is a PyTorch-based CNN model trained to classify chest X-ray images into:
- Normal
- Pneumonia

## 🚀 How to Reproduce

### 1. Clone the Repository
```bash
git clone https://github.com/Gokul-Viswam/Pneumonia-resnet50.git
cd your-repo
```


### 2.Install Dependencies
```bash
pip install -r requirements.txt
```

### 3.Run the Notebook
Open the notebook in Jupyter or Colab and run all cells:
```bash	
jupyter notebook PneumoniaMNIST.ipynb
```

### 📊Dataset
Dataset used: PneumoniaMNIST (part of MedMNIST)

Download from https://www.kaggle.com/datasets/rijulshr/pneumoniamnist/data

### Evaluation
Classification report

Confusion matrix

Accuracy, precision, recall, F1

---

##### ✅  Hyperparameter Notes

```markdown
 🧪 Hyperparameter Choices

| Hyperparameter   | Value              | Reason                                                                 |
|------------------|--------------------|------------------------------------------------------------------------|
| Learning Rate    | `0.001`            | Standard starting point for Adam; worked well without exploding loss   |
| Batch Size       | `32`               | Balanced between GPU memory usage and training stability               |
| Epochs           | `05`               | Enough for convergence on PneumoniaMNIST without overfitting           |
| Optimizer        | `Adam`             | Adaptive learning rate and fast convergence                            |
| Loss Function    | `CrossEntropyLoss` | Standard for multi-class classification problems                       |





