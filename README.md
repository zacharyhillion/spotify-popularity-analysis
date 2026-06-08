
# Spotify Popularity Analysis

## 🎯 Objective
This project analyzes which factors are associated with the popularity of songs on Spotify.  
The goal is to understand whether audio features such as energy, danceability, or valence can explain or predict a song’s popularity.

---

## 📊 Dataset
The dataset contains over 170,000 Spotify tracks with audio features such as:
- energy
- danceability
- valence
- acousticness
- tempo
- loudness
- release year
- popularity score

---

## 🧪 Methodology

1. Data exploration (structure, missing values)
2. Filtering to modern music (2000+)
3. Correlation analysis
4. Data visualization
5. Segmentation by time periods
6. Predictive modeling (linear regression)

---

## 📈 Key Findings

- The release year is the strongest factor associated with popularity
- Audio features (energy, danceability, valence) have weak correlations with popularity
- A linear regression model using only audio features achieves low predictive performance (R² ≈ 0.04)

---

## 🧠 Conclusion

Song popularity on Spotify is weakly explained by audio features alone.  
External factors such as trends, playlists, marketing, and cultural context likely play a much larger role.

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## 🚀 Future Improvements
- Use non-linear models (Random Forest, XGBoost)
- Include artist and playlist data
- Add time-series analysis of trends
