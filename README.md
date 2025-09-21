🚖 Dynamic Pricing System – Uber/Lyft

A Dynamic Pricing Dashboard that predicts optimal ride prices in real-time to maximize revenue using a Random Forest ML model. Built with Python, scikit-learn, and Streamlit for a fully interactive user experience.

📌 Project Overview

Dynamic pricing is a strategy where prices are adjusted in real-time based on demand, supply, and other external factors. This project simulates a real-world use case for ride-hailing services like Uber and Lyft, predicting the optimal price to maximize revenue for each trip.

Key Features:

Predicts expected demand based on trip features.

Suggests optimal price to maximize revenue.

Interactive Price vs Revenue graph to visualize impact.

User-friendly Streamlit dashboard for real-time experimentation.

<img width="1919" height="849" alt="image" src="https://github.com/user-attachments/assets/e02d9ff4-d8bc-4189-8256-97d588bb9b39" />


🛠️ Features & Functionality
1. Inputs:

Cab type (Uber / Lyft)

Cab name (e.g., Black SUV, Lux Black XL, etc.)

Hour of the day (0–23)

Weekend flag (0/1)

Surge multiplier (1.0–3.0)

2. Outputs:

Suggested optimal price

Expected revenue

Price vs Revenue interactive chart

Summary of input trip features

3. Bonus:

Transparent, modern dashboard design with gradient background.

Interactive Plotly graph for better visualization.

📊 Model

Type: Random Forest Regressor

Training dataset: Uber ride dataset (dataset/rideshare_kaggle.csv)

Evaluation Metrics:

RMSE: 8.82

MAE: 4.40

R²: 0.984

The model predicts demand at different price points, and the app calculates the price that maximizes revenue.

🛠️ Tech Stack

Backend & ML: Python, scikit-learn, joblib

Frontend: Streamlit, Plotly

Libraries: pandas, numpy, matplotlib, plotly, joblib, lightgbm

🚀 How to Run

Clone the repository:

git clone https://github.com/<your-username>/dynamic-pricing-project.git
cd dynamic-pricing-project


Create and activate a virtual environment (recommended: Anaconda):

conda create -n dynamic_pricing python=3.12
conda activate dynamic_pricing


Install dependencies:

pip install -r requirements.txt
# or manually:
pip install streamlit scikit-learn pandas numpy matplotlib plotly joblib lightgbm


Run the Streamlit app:

streamlit run app/app.py


Open the URL in your browser (usually http://localhost:8501).

🖼️ Screenshots

(Add screenshots of your dashboard here for better visual impact)

Sidebar inputs for trip features

Suggested optimal price & expected revenue

Interactive Plotly chart for price vs revenue

🔮 Future Improvements

Add weather and traffic features to improve demand prediction.

Implement Reinforcement Learning (RL) for advanced dynamic pricing.

Add competitor price scraping for real-time e-commerce dynamic pricing.

Deploy on AWS/GCP for cloud-based real-time pricing.

📂 Repository Structure
dynamic-pricing-project/
│
├── app/
│   └── app.py                        # Streamlit application
│
│
├── notebook/
│   └── dynamic_pricing.ipynb         # Jupyter notebook with data analysis & model building
│
├── .idea/                             # PyCharm project files
└── README.md                          # Project overview


✨ Author

Abdul Hadi S. 

LinkedIn: www.linkedin.com/in/abdulhadi2004
