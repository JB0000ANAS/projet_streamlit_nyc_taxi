# Application d'Analyse des Trajets de Taxi NYC

Cette application Streamlit permet d'analyser et de visualiser les données de trajets de taxis à New York.

## Installation locale

1. Cloner le dépôt
2. Créer un environnement virtuel :
   ```
   python -m venv venv
   source venv/bin/activate  # Sur Windows: .\venv\Scripts\activate
   ```
3. Installer les dépendances :
   ```
   pip install -r requirements.txt
   ```
4. Lancer l'application :
   ```
   streamlit run accueil.py
   ```

## Structure du projet

- `accueil.py` : Point d'entrée principal de l'application
- `taxi_ml_predictions.py` : Module de prédictions ML
- `nyc_zones_data.py` : Données des zones de New York
- `requirements.txt` : Dépendances Python
- `data/` : nyc_taxi_sample.csv
  
