# 🌦️ Weather Prediction in Australia

Hello everyone! My name is Marcos Salguero Carrero, and this is my project on weather prediction in Australia. In this project, we will explore the steps of collecting, processing, and analyzing weather data to predict whether it will rain tomorrow. We focus on various machine learning techniques, such as Support Vector Machines (SVM), Random Forests, and Neural Networks, to build a predictive model. 

## 📌 Description  

This project uses machine learning models to predict whether it will rain tomorrow in Australia, based on historical weather data. The dataset includes various meteorological variables such as temperature, humidity, wind speed, and pressure, which are used to make predictions. The goal is to determine the probability of rainfall exceeding 1 mm the following day.

## 🚀 Features  

✅ Data cleaning and processing of historical weather data.  
✅ Implementation of multiple machine learning models (SVM, Random Forest, Neural Networks).  
✅ Evaluation of model performance using accuracy, precision, recall, and other metrics.  
✅ Visualization of model results and predictions.  
✅ Correlation analysis to identify important weather features.

## 📂 Project Structure  

📁 weather-prediction  
│── 📂 data/                 # Weather data file  
│── 📂 src/                  # Project source code  
│── ── requirements.txt      # Project dependencies  
│── ── README.md             # Project documentation  

## 🛠️ Installation and Setup  

### 1️⃣ Clone the Repository  

```bash  
git clone https://github.com/Marcos-Salguero/weather-prediction.git  
cd weather-prediction

```

2️⃣ Create and Activate a Virtual Environment
```bash
python -m venv venv  
source venv/bin/activate  # On macOS/Linux  
venv\Scripts\activate     # On Windows
```

3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

📊 Usage    

🔹 Load the Data

The dataset (weatherAUS.csv) contains historical weather data for Australia, including variables such as temperature, humidity, wind speed, and more. You can load the dataset using pandas and begin your data analysis.

🔹 Train the Model

You can train various machine learning models such as SVM, Random Forest, or Neural Networks. The models are designed to predict whether it will rain tomorrow based on the features in the dataset.

🔹 Evaluate the Model

After training, evaluate the model’s accuracy and performance using error metrics and confusion matrices. Visualize the results using matplotlib and seaborn.

📈 Results and Evaluation

The results of the prediction models can be visualized using plots to compare predicted values with actual rainfall data. The accuracy and other performance metrics will help you assess the model's predictive power.

📄 License  
This project is licensed under the MIT License.

📞 Contact  
📧 Email: msalgueroc@gmail.com

🌍 GitHub: github.com/Marcos-Salguero