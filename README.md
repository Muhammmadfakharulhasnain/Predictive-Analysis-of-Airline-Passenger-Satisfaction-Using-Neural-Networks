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

### Key Features
- **Passenger Demographics:** `Gender`, `Age`, `Customer Type`
- **Travel Information:** `Type of Travel`, `Class`, `Flight Distance`
- **Service Ratings:** `Inflight wifi service`, `Food and drink`, `Online boarding`, `Seat comfort`, `Inflight entertainment`, `On-board service`, `Leg room service`, `Baggage handling`, `Checkin service`, `Inflight service`, `Cleanliness`
- **Delay Information:** `Departure Delay in Minutes`, `Arrival Delay in Minutes`
- **Target Variable:** `satisfaction` (binary classification)

### Dataset Summary
- **Total Entries:** 103,904
- **Columns:** 25
- **Data Types:** Integer, Float, and Categorical

### Example Columns:
- `Unnamed: 0` (int64) - Index
- `id` (int64) - Unique identifier for each passenger
- `Gender` (object) - Passenger gender
- `Customer Type` (object) - Type of customer (e.g., loyal, disloyal)
- `Arrival Delay in Minutes` (float64) - Delay duration upon arrival
- `satisfaction` (object) - Satisfaction status (Satisfied/Neutral or Dissatisfied)

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
- **Missing Value Imputation:** Implemented using RandomForestClassifier for categorical data and RandomForestRegressor for numerical data. This iterative imputation strategy helps maintain data integrity while filling in missing values based on related features. The process includes encoding categorical variables with LabelEncoder, handling other missing columns iteratively, and evaluating imputation performance using metrics like accuracy (for classification) and MAE, RMSE, R² (for regression).
- **Neural Network Architecture:** Fully connected layers with activation functions to capture complex patterns in passenger satisfaction data. The model consists of an input layer, hidden layers with ReLU activation functions, and an output layer with a sigmoid activation function suitable for binary classification tasks.
- **Model Compilation:** The model is compiled using the **Adam optimizer**, with **Binary Cross-Entropy** as the loss function, suitable for binary classification tasks. The **accuracy** metric is used to evaluate performance.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score

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

