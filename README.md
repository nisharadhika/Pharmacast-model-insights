# Pharmacast-model-insights
A lightweight forecasting and analytics tool designed to help small and medium pharmacies improve their sales prediction accuracy using modern machine learning and time-series models.

💡 Why This Project?

Traditional forecasting techniques often fail when applied to localized pharmacy sales because the data volume is small and demand patterns vary drastically.
PharmaCast AI solves this by applying advanced models and comparing them to find the best-performing forecast for each dataset.

🚀 Features

✔️ Multiple forecasting models compared side-by-side
(ARIMA, SARIMA, Holt-Winters, Prophet, LSTM, XGBoost, etc.)

✔️ Trend, seasonality & cycle analysis

✔️ Stationarity checks & preprocessing helpers

✔️ Model evaluation using error metrics
(MAE, MAPE, MSE)

✔️ Automated 3-month sales forecasting

✔️ Business insights & recommendations using an LLM

✔️ Dashboard for visualization and decision support

🧠 Tech Stack
Core Environment

Anaconda / Conda

Jupyter Notebook

VS Code

Python Libraries

Pandas, NumPy, Statsmodels, Prophet, Scikit-learn, Keras, XGBoost, SQLAlchemy

Machine Learning Models

ARIMA, SARIMA, Holt-Winters, Prophet, LSTM, XGBoost

Dashboard

React + Tailwind CSS

Node.js backend

PostgreSQL database

Recommendations Engine

HuggingFace GPT-2 model

📥 Installation & Setup
1️⃣ Create Conda Environment
conda create -n pharm_env python=3.10
conda activate pharm_env

2️⃣ Install Required Libraries
conda install pandas numpy matplotlib seaborn statsmodels keras scikit-learn prophet sqlalchemy

3️⃣ Clone This Repository
git clone <your-repo-link>

📊 Running the Model

Open the Model folder

Use the cleaned dataset from the input/ directory

Run the notebooks in this order:

data_analysis.ipynb

model_evaluation.ipynb

data_forecasting.ipynb

Avoid running preprocessing to prevent redundant files.

🗄️ Database Setup (PostgreSQL)

Install PostgreSQL

Create database: pharmecast_db

Load CSV files manually or run the load_to_db.ipynb notebook after adding DB credentials.

🖥️ Dashboard Setup
Backend
cd backend
npm install
node server.js


Check database connection at:
http://localhost:3001

Frontend
cd frontend
npm install
npm run dev


Dashboard opens at:
http://localhost:5173

🔮 Future Enhancements

Cloud deployment

Automated quarterly pipeline

Auto-sync predicted data into historical dataset

More deep learning models

⭐ Step 3 — Commit Your Own Project Structure

Instead of cloning someone else’s GitHub repo:

Do this:

Create your own folder locally.

Add:

model/

frontend/

backend/

database/

input/ (your cleaned CSVs)

Add your own .ipynb notebooks

Push everything to your repo:

git add .
git commit -m "Initial commit for PharmaCast AI"
git push origin main
