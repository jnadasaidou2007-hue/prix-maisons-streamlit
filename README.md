# 🏠 Estimation du prix des maisons

Mini-projet pédagogique : analyse de données et prédiction des prix de maisons avec une régression linéaire, présentée dans une application web Streamlit.

## Objectif
- Calculer des statistiques simples (moyenne, médiane, minimum, maximum, étendue)
- Calculer le prix au m²
- Analyser la corrélation entre superficie et prix
- Entraîner un modèle de Machine Learning et estimer le prix d'une maison

## Données
8 maisons fictives avec 3 variables : superficie (m²), nombre de chambres et ancienneté (ans). Les prix sont en milliers de dirhams (kDH).

## Technologies
Python, pandas, matplotlib, scikit-learn, Streamlit

## Fichiers
- `analyse.py` : statistiques et graphique
- `app.py` : application Streamlit
- `requirements.txt` : bibliothèques nécessaires

## Lancer le projet
```bash
pip install -r requirements.txt
python analyse.py
streamlit run app.py
```

## Limites
Le jeu de données ne contient que 8 exemples fictifs. Les métriques (MAE, R²) ne prouvent pas la fiabilité du modèle. Ce projet est uniquement pédagogique et ne doit pas servir à estimer de vrais prix immobiliers.

## Auteure
Nada Saidou, étudiante en BTS Intelligence Artificielle
