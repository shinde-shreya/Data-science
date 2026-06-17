# Machine Learning & Deep Learning Portfolio

Welcome to my Machine Learning and Deep Learning portfolio. This repository contains a curated collection of **10 individual projects** covering supervised machine learning, deep learning (artificial neural networks), computer vision, and natural language processing. 

Each project is self-contained in its own directory, accompanied by an interactive Jupyter notebook and a dedicated, in-depth `README.md` covering the mathematical foundations, preprocessing pipelines, model architectures, and evaluation diagnostics.

---

## 🛠️ Technology Stack
The projects in this portfolio are built using the following core libraries and environments:

- **Languages:** Python (Jupyter Notebooks)
- **Data Analysis & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning (Scikit-Learn):** Logistic Regression, Linear Regression, Decision Trees, Random Forests
- **Deep Learning (TensorFlow & Keras):** Fully Connected Neural Networks (FCNN), Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN)

---

## 📂 Repository Structure
Below is the clean, modular layout of this portfolio:

```text
├── CNN/                                 # Cats & Dogs Image Classification (CNN)
│   ├── CNN.ipynb
│   └── README.md
├── Decision Tree Classifier/            # Heart Disease Classifier (Decision Tree)
│   ├── Decision_Tree_1.ipynb
│   └── README.md
├── Fully Connected Neural Network/      # Fashion MNIST Clothing Classification (FCNN)
│   ├── Fully Connected Neural network.ipynb
│   └── README.md
├── Linear Regression/                   # Insurance Cost Forecast (Linear Regression)
│   ├── Linear Regression1.ipynb
│   └── README.md
├── Logistic Regression/                 # Bank Marketing Campaign (Logistic Regression)
│   ├── Logistic Regression1.ipynb
│   └── README.md
├── Project heart Disease Prediction/    # Multi-Model Heart Risk Predictor
│   ├── Project(Predicting Heart Disease).ipynb
│   └── README.md
├── Project(Customer_churn)/             # Customer Retention Regression & Classification
│   ├── Project(Customer_churn).ipynb
│   └── README.md
├── project creditCard_Fraud_Detection/  # Fraud Detection in Imbalanced Data
│   ├── project(creditCard_Fraud_Detection).ipynb
│   └── README.md
├── Random Forest Classifier/            # Customer Retention Ensemble (Random Forest)
│   ├── Random_forest1.ipynb
│   └── README.md
├── Recurrent Neural Network/            # IMDB Sentiment Sequence Analysis (SimpleRNN)
│   ├── RNN.ipynb
│   └── README.md
├── .gitignore                           # Excludes heavy datasets and Jupyter checkpoints
└── README.md                            # Portfolio Index (This file)
```

---

## 🚀 Project Index & Quick Links

| # | Project / Algorithm | Category | Dataset | Model / Key Technologies | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **01** | **Cats & Dogs Classification** | Computer Vision (DL) | Cats vs Dogs | CNN, Conv2D, Data Augmentation, Dropout | [View Project](./CNN/) |
| **02** | **Decision Tree Classifier** | Supervised ML | `heart.csv` | DecisionTreeClassifier, Gini Impurity | [View Project](./Decision%20Tree%20Classifier/) |
| **03** | **Fashion MNIST Classifier** | Deep Learning | Fashion MNIST | FCNN, Sequential, Dense, SGD, Softmax | [View Project](./Fully%20Connected%20Neural%20Network/) |
| **04** | **Insurance Cost Forecast** | Regression | `new_insurance_data (1).csv` | LinearRegression, R² Evaluation, OLS | [View Project](./Linear%20Regression/) |
| **05** | **Bank Campaign Predictor** | Classification | `bank-additional-full.csv` | LogisticRegression, Sigmoid, Log Loss | [View Project](./Logistic%20Regression/) |
| **06** | **Heart Disease Risk Predictor** | Multi-Model ML | `dataset.csv` | Logistic Regression, Decision Tree, Random Forest | [View Project](./Project%20heart%20Disease%20Prediction/) |
| **07** | **Customer Churn Analysis** | Hybrid ML | `customer_churn.csv` | Linear & Logistic Regression, Decision Tree, RF | [View Project](./Project%28Customer_churn%29/) |
| **08** | **Credit Card Fraud Detector**| Imbalanced Classification | `creditcard.csv` | Decision Tree, Random Forest, Precision/Recall | [View Project](./project%20creditCard_Fraud_Detection/) |
| **09** | **Customer Churn Ensemble** | Classification | `customer_churn.csv` | RandomForestClassifier, Ensemble Bagging | [View Project](./Random%20Forest%20Classifier/) |
| **10** | **IMDB Sentiment Analysis** | NLP (DL) | IMDB Reviews | SimpleRNN, Embedding, Sequence Padding | [View Project](./Recurrent%20Neural%20Network/) |

---

## 💻 Getting Started

To run any of the notebooks locally, follow these steps:

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd <repository-directory-name>
```

### 2. Install dependencies
Make sure you have Python installed. You can install all necessary packages via:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```
Navigate to any project folder and open the `.ipynb` file to run/interact with the code.
