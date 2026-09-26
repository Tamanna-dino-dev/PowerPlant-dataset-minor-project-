# PowerPlant Dataset — Minor Project

A minor project applying **Artificial Neural Networks (ANNs)** to two tasks: classification and regression. This repository contains the notebooks, along with the workflow for data preprocessing, model building, training, and evaluation.

## 📌 Project Overview

This project explores two core ANN use cases:

- **Classification** — predicting categorical outcomes using the Date Fruit dataset.
- **Regression** — predicting continuous outcomes (power output) using the Power Plant dataset.

## 📂 Repository Structure

```
ANN_models/
├── ANN_Classification.ipynb   # ANN model for classification task
├── ANN_Regression.ipynb       # ANN model for regression task
├── DateFruit_Dataset.csv      # Dataset used for classification (not tracked in Git)
├── powerplant_data.csv        # Dataset used for regression (not tracked in Git)
└── README.md
```

> **Note:** Dataset CSV files are excluded from version control via `.gitignore`. To run the notebooks, place the datasets in the `ANN_models/` folder locally.

## 🛠️ Tech Stack

- Python
- NumPy / Pandas
- Scikit-learn
- TensorFlow / Keras (or PyTorch — update as applicable)
- Jupyter Notebook

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Tamanna-dino-dev/PowerPlant-dataset-minor-project-.git
   cd PowerPlant-dataset-minor-project-/ANN_models
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Add the dataset CSVs into the `ANN_models/` folder (see note above).

4. Open and run the notebooks:
   ```bash
   jupyter notebook
   ```

## 📊 Results

| Model | Task | Metric | Score |
|-------|------|--------|-------|
| ANN Classification | Classification | Accuracy | _add your result_ |
| ANN Regression | Regression | R² / RMSE | _add your result_ |

## 📈 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Model comparison with other algorithms (Random Forest, XGBoost)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE). 