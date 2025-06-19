# Fair-Prediction

A machine learning-based fare prediction system with explainable logic, built during my internship at TIARO (May 2025 – Present).  
This project uses custom feature engineering and ensemble models to provide transparent and accurate fare predictions.

##  Overview

- Developed using Python, pandas, scikit-learn, and Streamlit
- Focused on real-world pricing logic:
  - Vehicle age
  - AC usage
- Compared models like:
  - Linear Regression
  - Decision Tree
  - Random Forest (Best: RMSE ~19.30)

##  Features

- Custom logic: age factor, AC factor
- Streamlit web app for real-time prediction
- Model transparency vs black-box pricing (like Ola/Uber)
- Trained & tested on sample TIARO fleet dataset

##  How to Run
pip install -r requirements.txt
streamlit run app.py 

 [View Streamlit App PDF](./Streamlit.pdf)
 [Streamlit App Example – PDF Demo](./Streamlit%201.pdf)





