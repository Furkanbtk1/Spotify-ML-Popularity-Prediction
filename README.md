# 🎵 Spotify Song Popularity Prediction

This project aims to predict the **popularity scores of Spotify songs** using machine learning techniques. It includes steps for data analysis, feature engineering, and model training/evaluation.

## 📊 Contents

- `spotify_song_prediction.ipynb` — Main Jupyter Notebook file.
- Dataset: Collected from Spotify API or Kaggle (details below).
- Libraries used:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`


## 🚀 Project Objective

To develop a regression or classification model capable of predicting **Spotify song popularity** based on audio features such as tempo, valence, energy, and danceability.

### Main Steps
- Analyze song features and correlations with popularity.
- Build machine learning models (e.g., Linear Regression, Random Forest, XGBoost).
- Evaluate and compare model performance.

## 🧠 Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Feature selection
   - Standardization / Normalization

2. **Modeling**
   - Train-test split
   - Model training and hyperparameter tuning
   - Evaluation using R², MAE, RMSE metrics

3. **Evaluation**
   - Compare model performance
   - Select the best-performing model


## 📂 Project Structure

```
spotify-song-prediction/
│
├── spotify_song_prediction.ipynb   # Main notebook
├── README.md                       # Project description
└── data/                           # (Optional) Dataset folder
```

## 🧰 Requirements

To install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

## 💡 Future Improvements

- Build a **Streamlit web app** for song popularity prediction 🎧  
- Fetch new data in real time using the Spotify API  
- Deploy the model via **Flask** or **FastAPI**  

## 🖋️ Author

**Furkan Bitik**  
📧 [GitHub Profile](https://github.com/Furkanbtk1)  
🧠 Passionate about Mathematics and Data Science  

---
