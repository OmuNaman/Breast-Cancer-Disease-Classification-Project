# 🧬 Breast Cancer Classification Project

A deep dive into machine learning and neural networks for breast cancer classification, leveraging both Decision Tree classifiers and dense neural networks to achieve high accuracy in differentiating between malignant and benign tumors.

## 📝 Project Overview
This project uses the Breast Cancer Wisconsin dataset to develop a robust classification model, combining scikit-learn's Decision Tree classifier with a dense neural network model built with TensorFlow. The goal is to achieve high sensitivity and precision in identifying malignant cases, pushing the boundaries of AI applications in healthcare.

### Key Features
- **Data Preprocessing**: Implemented with scikit-learn's `Pipeline` and `ColumnTransformer` to ensure consistent scaling and handling of missing values.
- **Modeling**: Utilizes both a **Decision Tree** classifier for interpretability and a **Neural Network** model for deep pattern recognition.
- **Evaluation Metrics**: Extensive evaluation using accuracy, precision, recall, and F1-score, validated on separate test and validation datasets.

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries:

   ```bash
  pip install numpy pandas scikit-learn matplotlib tensorflow

## Installation

### Clone the repository:
    ```bash #Ignore This Line
      git clone https://github.com/yourusername/breast-cancer-classification.git 
      cd breast-cancer-classification

### Run the Jupyter Notebook:

Execute all cells in the Jupyter Notebook to run the project.

## 📊 Results

| Metric            | Decision Tree (Test)       | Decision Tree (Validation)|
|-------------------|----------------------------|---------------------------|
| Accuracy          | 96.4%                      | 100%                      |
| Precision         | 0.94                       | 01.0                      |
| Recall            | 01.0                       | 01.0                      |
| F1 Score          | 0.9714                     | 01.0                      |

### Neural Network (RNN):

The neural network model can be run by setting up TensorFlow, with accuracy and loss visualizations available for each epoch.

## 📈 Visualizations

- **Decision Tree Structure:** Visualized for interpretability.
- **Neural Network Training:** Plots for accuracy and loss over epochs (requires TensorFlow installation).

## 🧠 Insights

This project showcases how combining simpler models like Decision Trees with deep neural networks can balance interpretability and performance, making it a powerful approach for healthcare diagnostics.

## 🤝 Contributing

Feel free to submit issues or pull requests. Contributions are welcome!

## 📜 License

This project is licensed under the MIT License.

