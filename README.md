# 🎵 Analysis of Popular Songs on Spotify (2023)

This project aims to analyze the *Most Streamed Spotify Songs 2023* dataset to understand the relationship between musical characteristics and the popularity of songs on Spotify. The analysis explores patterns, correlations, and trends over time.

## 📊 Project Details

- **Objective:** Investigate the factors influencing song popularity on Spotify by analyzing characteristics such as energy, valence, playlist presence, sentiment, and artist popularity.
- **Context:** Public datasets containing information about the most popular Spotify songs in 2023 were used, along with historical data from 2017-2021. Song lyrics were also extracted for sentiment analysis and linguistic pattern identification.
- **Main Techniques Used:**  
  - Exploratory Data Analysis (EDA)  
  - Visualizations (Scatter plots, histograms, word clouds, etc.)  
  - Sentiment Analysis with *VADER*  
  - Spearman Correlation  
  - Linear Regression (*Ordinary Least Squares - OLS*)  
  - Principal Component Analysis (*PCA*)  
  - Conditional Probability  

## 🛠️ Repository Structure

```
├── analise_dados_spotify      # Jupyter Notebook with analyses
├── relatorio.pdf        # Report containing all conducted analyses
├── README.md       # Project documentation
```

## 🚀 Results & Insights

- **Popularity and musical characteristics:** No strong correlations were found between popularity and characteristics such as BPM, valence, or energy.  
- **Playlist influence:** Songs featured in popular playlists on Spotify, Deezer, and Apple Music showed significant correlation with the number of streams.  
- **Recent releases dominate:** Songs released in 2022 were the most popular in 2023, with a decline in popularity for previous years.  
- **Lyrics analysis:** Words like "love," "know," and "like" were the most common in the most played songs.  
- **Song sentiment:** Most popular songs had neutral or slightly positive sentiments.  
- **Release patterns:** Many songs were released on the 1st of each month and in January, suggesting marketing strategies.  

## 📁 Data

- **Data Sources:**
  - [Most Streamed Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)
  - [Spotify Daily Top 200 (2017-2021)](https://www.kaggle.com/datasets/ivannatarov/spotify-daily-top-200-songs-with-genres-20172021)
  - Lyrics extraction and translation using Lyrics.ovh API and Gemini - Pro AI.
  
- **Data Format:**  
  - CSV files containing information such as song name, artist, release date, number of streams, audio features (danceability, energy, valence, etc.), and playlist presence.

## 🤷‍♂️ How to Use

1. Clone this repository:  
   ```bash
   git clone https://github.com/GabrielIamato/spotify_musics_analysis.git
   ```
2. Install the required libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud scipy statsmodels scikit-learn nltk vaderSentiment
   ```
3. Run the main script:  
   ```bash
   python main.py
   ```

## 📈 Technologies Used

- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` – Data manipulation  
  - `matplotlib`, `seaborn`, `wordcloud` – Visualization  
  - `scipy`, `statsmodels` – Statistical analysis  
  - `sklearn` – PCA and modeling  
  - `nltk`, `vaderSentiment` – Natural language processing  

## 🤝 Contributions

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a branch for your feature:  
   ```bash
   git checkout -b my-feature
   ```
3. Submit a Pull Request.  

## 📄 License

This project is licensed under the GNU General Public License v3.0, published by the Free Software Foundation.
