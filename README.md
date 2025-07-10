# Moosic_UML 
## Algorithmic Playlists: Clustering Spotify Songs by Vibe 
---

What if playlists could organize themselves—without genres, user input, or human bias?

**Moosic_UML** is a hands-on, learning-focused project that explores how unsupervised machine learning can be used to group Spotify tracks based purely on their audio features. Using clustering algorithms like K-Means, it uncovers natural groupings of songs that share a similar *feel* not just a genre label.

By analyzing attributes such as energy, danceability, tempo, and mood, the algorithm creates vibe-based playlists rooted in the raw sound of the music.

### Main Points

- **Focus on learning by doing**: A practical application of unsupervised techniques using real music data.
- **Vibe over genres**: Let the data guide the flow, not labels or predefined categories.
- **No manual labels**: Clusters form naturally based on each track’s unique sound.

Think of it as *machine-curated mood music* where the algorithm decides what belongs together, based only on how it sounds.

---
## Project Structure
```
Moosic_UML/
│
├── Data/         # Raw and preprocessed datasets (.csv)
├── Notebooks/    # Jupyter notebooks for exploration, preprocessing, and modeling
├── README.md     # Project documentation
└── .gitignore    # Files and folders ignored by Git
```


---

## Workflow

1. Load and clean Spotify audio data  
2. Scale numerical features for clustering  
3. Apply **K-Means clustering** (feel free to experiment with others like DBSCAN!)  
4. Visualize and interpret the resulting clusters  
5. Generate playlist-like song groups based on audio similarity  

---

## Technologies Used

- **Python 3**  
- **Jupyter Notebooks / Google Colab** – same code, two platforms, choose what works best for you  
- **Pandas**, **NumPy**, **Scikit-learn** – for data manipulation and machine learning  
- **Matplotlib**, **Seaborn** – for visualizing patterns in the data    

---

## Dataset

You’ll find the dataset in the **`Data/`** folder. The dataset includes audio features and metadata for a curated selection of Spotify tracks.

- **Acousticness:** Confidence score (0.0 to 1.0) indicating whether the track is acoustic. A value of 1.0 represents high certainty.
- **Danceability:** Suitability for dancing, based on tempo and rhythm; 0.0 = least, 1.0 = most.
- **Duration (ms):** Track length in milliseconds.
- **Energy:** Perceived intensity/activity; 0.0 (calm) to 1.0 (energetic).
- **Instrumentalness:** Likelihood the track has no vocals; closer to 1.0 means more instrumental.
- **Key:** Musical key using Pitch Class notation (e.g., 0 = C, 1 = C♯/D♭, 2 = D, etc.).
- **Liveness:** Probability of a live audience; values > 0.8 suggest live performance.
- **Loudness:** Average loudness in decibels (dB).
- **Mode:** Indicates the modality of the track: 1 = major, 0 = minor.
- **Speechiness:** Detects spoken word content. Values closer to 1.0 indicate speech-heavy recordings (e.g., podcasts, rap).
- **Tempo:** Estimated speed of the track in beats per minute (BPM).
- **Time Signature:**  Beats per measure (e.g., 4 = common time)
- **Valence:** Musical positiveness; closer to 1.0 = happier mood.
---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/LauraM-SG/Moosic_UML.git
   cd Moosic_UML
   
2. Launch the Jupyter notebook of your choice (locally or via Google Colab) and follow along.

---


  ## *Feel free to fork, experiment, or remix — this is a project for learning and creativity!* 🚀✨

