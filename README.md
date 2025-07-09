# Moosic_UML 
## Algorithmic Playlists: Clustering Spotify Songs by Vibe 
---

What if playlists could organize themselves—without genres, user input, or human bias?

**Moosic_UML** is a hands-on, learning-focused project that explores how unsupervised machine learning can be used to group Spotify tracks based purely on their audio features. Using clustering algorithms like K-Means, it uncovers natural groupings of songs that share a similar *feel* not just a genre label.

By analyzing attributes such as energy, danceability, tempo, and mood, the algorithm creates vibe-based playlists rooted in the raw sound of the music.

### Highlights

- **Learning-first**: A practical application of unsupervised techniques using real music data.
- **Vibe over genres**: Let the data guide the flow—no labels or pre-defined categories.
- **No manual tags**: Clusters form organically from the sonic "fingerprint" of each track.

Think of it as *machine-curated mood music* where the algorithm decides what belongs together, based only on how it sounds.

---
## Project Structure
```
Moosic_UML/
│
├── Data/         # Raw and preprocessed datasets (.csv, .xlsx, etc.)
├── Notebooks/    # Jupyter notebooks for exploration, preprocessing, and modeling
├── README.md     # Project documentation
└── .gitignore    # Files and folders ignored by Git
```


---

## Workflow

1. Load and clean Spotify audio data  
2. Apply unsupervised learning (K-Means clustering)  
3. Visualize and interpret the resulting clusters  
4. Generate playlist-like groups based on similarity  

---

## Technologies Used

- Python 3  
- Jupyter Notebooks / Google Colab  
- Pandas, NumPy, Scikit-learn  
- Matplotlib / Seaborn  

---

## Dataset

Located in the **`Data/`** folder, the dataset includes audio features and metadata for a selection of Spotify tracks:

- Danceability  
- Energy  
- Tempo  
- Acousticness  
- Genre (optional metadata)  
- Artist / Track name  

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/LauraM-SG/Moosic_UML.git
   cd Moosic_UML
   
2. Launch the Jupyter notebook of your choice (locally or via Google Colab) and follow along.

---


  ## *Feel free to fork, experiment, or remix — this is a project for learning and creativity!* 🚀✨

