# Football Project – Player Market Value Prediction

This repository was created as part of the **Akbank Machine Learning Bootcamp**. It focuses on a **supervised learning** problem, aiming to **predict football players' market values** based on various physical and technical attributes using the **Football Manager 2020 dataset**.

---

##  Problem Description

In the football industry, accurately estimating a player's market value is crucial for clubs during transfers. This project aims to develop a machine learning model that predicts a player's market value using features like:

- Age, Height, Weight  
- Club, Nationality, Position  
- Technical skills (e.g., Dribbling, Passing, Finishing)  
- Mental attributes (e.g., Determination, Composure)  
- Physical stats (e.g., Acceleration, Agility)

---

##  Algorithm Used

The main algorithm used in this project is **Decision Tree Regressor**. It builds a tree-like structure by splitting the dataset based on feature values, making it effective in capturing complex patterns in the data.

The reasons for choosing this algorithm:
- It is easy to interpret and visualize,
- Less sensitive to outliers compared to linear models,
- Works well with non-linear relationships,
- Fast to train and test with structured data.

The model showed promising results when predicting player market values based on physical, technical, and mental attributes.


##  Evaluation Metrics

The following metrics were used for model evaluation:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

Each metric was discussed in detail in the notebook to understand model performance beyond numerical output.

---

##  Dataset Info

- Dataset: `datafm20.csv` (Football Manager 2020)
- Rows: ~18,000 players
- Features: 64 total columns
- No missing values
- Source: Kaggle-like structured dataset

---

##  Real-World Relevance

This kind of predictive model can help:

- Clubs estimate fair transfer fees
- Scout teams compare potential signings
- Automate valuation for sports analytics tools
- Enhance gaming simulations like FIFA/FM

---

##  Future Improvements

- Add features like injury history, performance trends, and match ratings
- Deploy the model with **Streamlit** or **Gradio**
- Scrape real-time player stats from online sources
- Try advanced models (e.g., XGBoost, LightGBM, Neural Networks)
- Build an interactive dashboard for predictions

---

##  Project Structure

- `football_project.ipynb`: Main Jupyter Notebook with detailed code and analysis  
- `datafm20.csv`: Dataset used for model training  
- `README.md`: Project explanation and future goals

---

##  Kaggle Notebook Links

- [Decision Trees - Accuracy & Feature Selection](https://www.kaggle.com/code/goker67/decision-trees-acc-metrics-feature-selection)  
- [GPU-based ML with cuml, polars, and cupy](https://www.kaggle.com/code/goker67/everything-on-gpu-ml-with-cuml-polars-cupy)

---

##  Final Note

This project was built during the bootcamp to demonstrate practical skills in data processing, model training, evaluation, and documentation.  
It will be improved continuously and may serve as a foundation for real-world football analytics applications.

---


