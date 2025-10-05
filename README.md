<h1 align="center">🎵 Spotify EDA Project</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Analysis-EDA-blue.svg" />
  <img src="https://img.shields.io/badge/Python-3.8+-green.svg" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange.svg" />
  <img src="https://img.shields.io/badge/Status-Complete-success.svg" />
  <img src="https://img.shields.io/github/license/your-username/Spotify_EDA_Project" />
</p>

---

## 📊 Project Overview  

 As a Music Director or Mixing Engineer, the goal is to optimize new songs for popularity. Using the Spotify dataset, which includes features like danceability, energy, loudness,and duration, we aim to perform ExploratoryData Analysis to uncover insights that guide music production for better audience appeal.  

**Author:** Subham Singh

---

## 🚀 Objectives  

- Perform **data cleaning and preprocessing**  
- Explore **artist, genre, and popularity distribution**  
- Visualize **correlations among audio features**  
- Analyze **year-wise music evolution**  
- Provide a foundation for **future/current implemenatations for tracks to maximise popularity** (e.g., recommendations, hit prediction)  

---

## 🛠️ Tech Stack  

- **Python 3.8+**  
- **Pandas, NumPy** → Data wrangling & transformation  
- **Matplotlib, Seaborn** → Data visualization  
- **Google Colab** → Development environment  

---
## 📈 Key Insights
- 🎤 **Top 1% tracks** → Identified most popular songs that indicated a power law distribution  
- ⭐ **Popularity Analysis** → Distribution and outliers of song popularity  
- 🔥 **Correlation Heatmap** → Energy strongly correlates with popularity  
- 💃 **Danceability Trend** → Increasing over recent years  
- 🎶  **Audience Leans More Towards High-Energy Mix Arcs** → Energy and Danceability clusters in top tracks
## 🎯 Results
- ✔ Strong relationship between **energy & popularity**    
- ✔ Increasing **danceability and tempo** trends in modern music  
- ✔  Korean songs (14%) have the **highest mean popularity**,suggesting high engagement despite lower volume.
- ✔ Mode is Secondary: **Do not let mode constrain your creative choice.** 




How to Run the Notebook

Install the required dependencies by running the following command

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```


**If you are unable to run the notebook locally, download the Spotify_EDA_Analysis.ipynb file along with the datasets, and run it directly on Google Colab.**

## 📂 Project Structure  

```bash
Project1_Spotify_EDA/
│
├── Spotify_EDA_Analysis.ipynb        # Main notebook with full EDA
├── README.md                        # Project overview
├── spotify_dataset.zip              # The datasets I used for my analysis
└── Presentation_EDA.pdf            # Presenatation based on graphs and key insights



