# Mobile Price Classification

## 📌 Overview
This project aims to build a machine learning model that classifies mobile phones into different price ranges based on various features such as battery power, RAM, storage, and other technical specifications. By leveraging classification algorithms, this model helps predict the pricing category of a mobile device.

## 🚀 Technologies Used
- **Python**: Main programming language
- **Pandas, NumPy**: Data processing and manipulation
- **Scikit-learn**: Machine learning model development
- **Matplotlib, Seaborn**: Data visualization
- **Jupyter Notebook**: Development environment

## 🔍 Dataset
The dataset contains information about mobile phone specifications and their corresponding price range categories. Key features include:
- Battery power
- RAM
- Internal memory
- Camera specifications
- Processor speed
- Screen size and resolution
- Mobile weight, thickness, etc.

## 🔧 Steps to Implement
1. **Data Preprocessing**: Load, clean, and analyze the dataset.
2. **Feature Engineering**: Select relevant features and handle missing values if necessary.
3. **Data Visualization**: Use Matplotlib & Seaborn to explore feature relationships.
4. **Model Selection & Training**:
   - Train different classification models (e.g., Decision Tree, Random Forest, SVM, Logistic Regression)
   - Evaluate models using accuracy, precision, recall, and F1-score
5. **Hyperparameter Tuning**: Optimize the model for better accuracy.
6. **Prediction & Evaluation**: Test the model on unseen data.

## 📈 Results
- The best model achieved high accuracy in classifying mobile price categories.
- Feature importance analysis showed that **RAM and Battery Power** are significant indicators of mobile pricing.

## 🏁 How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/OneSun02/Mobile_price_classification.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run `Mobile_price_classification.ipynb`

## 📌 Future Improvements
- Integrate more advanced models like XGBoost or Neural Networks.
- Implement a web-based interface for easy predictions.

## 📂 Repository Structure
```
📂 Mobile_price_classification
├── 📄 Mobile_price_classification.ipynb  # Jupyter Notebook with code
├── 📄 requirements.txt                   # List of dependencies
├── 📂 data                               # Dataset (if applicable)
└── 📜 README.md                          # Project documentation
```

## 🔗 Reference
Dataset Source: [Kaggle / Public Dataset] (if applicable)

---

Feel free to contribute or raise issues if you have any suggestions! 🚀

