# 🚖 Uber Hot Zones - New York City

## 🎯 Objectif
Détecter les "hot zones" (zones à forte demande) pour les conducteurs Uber à New York, selon le jour et l'heure, à partir de données historiques.

## 📊 Méthodologie
- Fusion de fichiers de pick-up Uber (2014-2015)
- Extraction temporelle (jour, heure)
- Clustering des points de pick-up (KMeans, DBSCAN)
- Visualisation sur carte interactive (Plotly)
- Dashboard interactif pour navigation temporelle


## ▶️ Lancer le dashboard
```bash
pip install -r requirements.txt
jupyter notebook notebooks/Projet_Uber.ipynb
