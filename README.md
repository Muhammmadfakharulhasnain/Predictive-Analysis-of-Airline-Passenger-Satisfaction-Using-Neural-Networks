# 📊 Predictive Analysis of Airline Passenger Satisfaction Using Neural Networks

## ✈️ Overview
This project focuses on predictive analysis to determine airline passenger satisfaction levels using neural networks. The goal is to analyze passenger data and build a model capable of accurately classifying satisfaction based on various factors such as service quality, comfort, and in-flight experience.

## 🚀 Features
- Exploratory Data Analysis (EDA) with visualizations
- Data preprocessing and feature engineering
- **Missing value imputation using Random Forest-based models**
- Neural network model development for classification
- Model evaluation and performance metrics
- Interactive plots using Plotly for better data insights

## 📂 Dataset
The dataset includes:
- **Training Data:** `train.csv`
- **Testing Data:** `test.csv`

Key features include:
- Passenger demographics
- Flight service ratings
- Travel preferences
- Overall satisfaction

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/airline-satisfaction-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd airline-satisfaction-analysis
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Usage
Run the Jupyter notebook to explore the analysis:
```bash
jupyter notebook
```
Open `Airline_Passenger_Satisfaction.ipynb` and follow along with the analysis and model-building process.

## 🧠 Model Details
- **Missing Value Imputation:** Implemented using RandomForestClassifier for categorical data and RandomForestRegressor for numerical data. This iterative imputation strategy helps maintain data integrity while filling in missing values based on related features.
- Neural Network Architecture: Fully connected layers with activation functions
- Loss Function: Categorical Cross-Entropy
- Optimizer: Adam
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

## 📈 Results
The model achieved high accuracy in predicting passenger satisfaction, demonstrating the effectiveness of neural networks for classification tasks in customer feedback data.

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, make changes, and submit pull requests.

## 📬 Contact
**Author:** Muhammad Fakhar ul Hasnain  
- [GitHub](https://github.com/Muhammmadfakharulhasnain)  
- [Kaggle](https://www.kaggle.com/mfakharulhasnain)  
- [LinkedIn](https://www.linkedin.com/in/muhammadfakharulhasnain6/)  
- [Email](mailto:muhammadfakharulhasnain6@gmail.com)

---

*This project is a demonstration of using machine learning techniques to enhance customer satisfaction analysis in the airline industry.*

