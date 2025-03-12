# Portfolio Risk Prediction using Random Forest

## 📌 Project Overview
This project focuses on predicting portfolio risk using a **Random Forest model**. It optimizes asset allocation by maximizing the **Sortino Ratio** and minimizing **downside risks** through **Mean-Variance Optimization (MVO)**. Additionally, we analyze risk using **Value at Risk (VaR)** and **Conditional Value at Risk (CVaR)**.

The project integrates **real-world financial data** across multiple asset classes, including **stocks, bonds, and cryptocurrencies**, and is deployed using **Streamlit**.

---

## 🚀 Features
- **Portfolio Optimization**: Uses Mean-Variance Optimization (MVO) to maximize the Sortino Ratio.
- **Risk Analysis**: Computes Value at Risk (VaR) and Conditional VaR (CVaR).
- **Machine Learning Model**: Implements Random Forest to predict risk.
- **Interactive Web Application**: Built using Streamlit for easy user interaction.
- **Real-World Data**: Utilizes historical market data to provide realistic risk analysis.

---

## 🛠 Installation & Setup
Follow these steps to set up and run the project on your local machine.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/portfolio-risk-prediction.git
cd portfolio-risk-prediction
```

### 2️⃣ Create a Virtual Environment (Recommended)
```bash
python -m venv env
source env/bin/activate   # On macOS/Linux
env\Scripts\activate     # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Streamlit App
```bash
streamlit run app.py
```
This will start a local server, and you can access the application at:
```
http://localhost:8501
```

---

## 📊 Usage Guide
1. **Upload Market Data**: Upload historical stock, bond, and cryptocurrency data.
2. **Set Risk Parameters**: Choose portfolio constraints and risk preferences.
3. **Run Optimization**: The system calculates optimal asset weights.
4. **View Predictions**: Check portfolio risk, VaR, CVaR, and optimized allocation.
5. **Download Reports**: Export results for further analysis.

---

## 🌍 Deployment (For Cloud & Colab Users)
If running in Google Colab, you need to expose the Streamlit app using Ngrok.

### 1️⃣ Install & Import Ngrok
```bash
pip install pyngrok
```
```python
from pyngrok import ngrok
```

### 2️⃣ Run Streamlit in the Background
```bash
!streamlit run app.py &>/dev/null &
```

### 3️⃣ Generate a Public URL
```python
public_url = ngrok.connect(port='8501')
print(f"Streamlit app is live at: {public_url}")
```
This will give you a public link to access the app remotely.

---

## 📌 Technologies Used
- **Python** (pandas, NumPy, scikit-learn, Streamlit, PyPortfolioOpt)
- **Machine Learning** (Random Forest, Mean-Variance Optimization)
- **Risk Analysis** (VaR, CVaR, Sortino Ratio, Sharpe Ratio)
- **Deployment** (Streamlit, Ngrok for remote access)

---

## 🤝 Contributing
We welcome contributions! If you'd like to improve the project:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes and push to GitHub.
4. Open a pull request.

---

## 📜 License
This project is licensed under the MIT License.

---



Happy Investing! 📈🚀

