# ⚽ Visualisation des tirs d’Erling Haaland – Premier League 2022/23

Ce projet reproduit une **visualisation inspirée par The Athletic (NYT)** et la **vidéo de McKay Johns** :  
🎥 [How Erling Haaland Scores So Many Goals](https://www.youtube.com/watch?v=v3uI44ZA_WU)

L’objectif est de représenter graphiquement **tous les tirs d’Erling Haaland** lors de la saison **2022/23** de Premier League, en mettant en avant :
- La **localisation des tirs**
- La **qualité des occasions (xG)**
- Les **buts marqués**
- Les **statistiques clés** de la saison

---

## 🧰 Librairies utilisées

- `pandas` – manipulation des données  
- `matplotlib` – création des visualisations  
- `mplsoccer` – traçage du terrain et des positions de tirs  
- `matplotlib.font_manager` – personnalisation de la police (style The Athletic)

---

## 📂 Données

Les données proviennent de [Understat](https://understat.com/player/), et sont chargées depuis le fichier :

