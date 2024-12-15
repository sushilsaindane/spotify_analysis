# Spotify Music Analysis

## Project by:

- Sushil Saindane

## Project Overview

This project analyzes music data from Spotify and Genius to gain insights into song characteristics, popularity, and lyrical content. I have developed a comprehensive pipeline that includes:

1. **Data Collection:** 
   - Utilized Spotify API to gather track metadata and audio features
   - Scraped lyrics from Genius using their API

2. **Data Integration:**
   - Combined Spotify track data with corresponding lyrics
   - Created a rich dataset with musical, popularity, and lyrical information

3. **Analysis Objectives:**
   - **Summary Generation:** Produced concise summaries of song lyrics using advanced NLP techniques
   - **Sentiment Analysis:** Categorized songs into various moods based on lyrical content
   - **Content-based Recommendation:** Developed a system to suggest similar songs based on audio features and lyrics
   - **Popularity Prediction:** Built a model to forecast a song's potential popularity

## Repository Structure

- `scrape_data.ipynb`: Script for scraping data from Spotify and Genius APIs
- `master_final.xlsx`: The dataset containing all collected and processed data
- `spotify_analysis.ipynb`: Main Jupyter notebook containing all analysis objectives

## Setup and Installation

1. Clone the repository: git clone https://github.com/your-username/spotify-music-analysis.git
cd spotify-music-analysis


2. Install required dependencies: ```pip install -r requirements.txt```

3. Set up API credentials:
- Create or login to your account on spotify and genius.
- Setup a new project to get your own API's
- Note: Spotify has made some API level changes recently, which is why scraping audio features is not allowed anymore, which is why the script might give you errors. You can simply update the script to scrape only the data that spotify is now allowing users to scrape.
- Add your Spotify and Genius API credentials to the scrape_data.ipynb file:
  ```
  SPOTIFY_CLIENT_ID=your_spotify_client_id
  SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
  GENIUS_ACCESS_TOKEN=your_genius_access_token
  ```

## Running the Analysis

1. Open `spotify_analysis.ipynb` in Jupyter Notebook or JupyterLab.
2. Ensure that `master_final.xlsx` is in the same directory as the notebook.
3. Run all cells in the notebook to perform the analysis.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- transformers
- torch
- spotipy
- lyricsgenius

## Results

The analysis provides insights into:
- Lyrical themes and sentiments across different genres and artists
- Factors influencing song popularity
- Effectiveness of content-based recommendation systems for music
- Trends in musical features and lyrical content over time

For detailed results and visualizations, please refer to the `spotify_analysis.ipynb` notebook.

## Future Work

- Incorporate more advanced NLP techniques for lyric analysis
- Expand the dataset to include a wider range of artists and genres
- Develop a user interface for interactive exploration of the analysis results

## Contact

Sushil Saindane - sushswork@gmail.com
LinkedIn - https://www.linkedin.com/in/sushil-saindane-12520a1a4/
