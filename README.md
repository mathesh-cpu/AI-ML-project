# AI-ML-project
Overview
This project demonstrates stock price forecasting using deep learning models, specifically LSTM (Long Short-Term Memory) networks, applied to Apple Inc. (AAPL) stock. The prediction results are visualized and deployed through a Streamlit app.

Tech Stack
• Python
• yfinance
• NumPy, Pandas
• scikit-learn
• Keras / TensorFlow
• Matplotlib
• Streamlit

Dataset
• Source: Yahoo Finance (AAPL)
• Range: 2015-01-01 to 2024-12-31
• Field Used: Closing price

Model Workflow
1. Download Data with yfinance
2. Normalize data with MinMaxScaler
3. Generate Sequences for LSTM input
4. Train LSTM Model
5. Evaluate using test data
6. Plot Predictions
7. 
Visualization
The final visualization is built using matplotlib and integrated into a Streamlit app. The plot compares actual and predicted prices using a clear line chart.

Deployment
The project is deployed via Streamlit Community Cloud.

visit my app👇
maddys-aiproject.streamlit.app

Files included:
• app.py - Main Streamlit app
• predictions.npy, actual_prices.npy - Prediction results
• requirements.txt - Python dependencies

How to Run Locally
1. Clone the repository:
   git clone https://github.com/yourusername/stock-prediction-streamlit.git
   cd stock-prediction-streamlit

2. Install dependencies:
   pip install -r requirements.txt

3. Run the app:
   streamlit run app.py
   
Author
Matheshwaran.N
Intern at Elevate Labs
Duration: 24.04.2025 – 23.05.2025
