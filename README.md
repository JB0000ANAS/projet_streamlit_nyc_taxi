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

## Déploiement sur Streamlit Cloud

1. Poussez ce dépôt sur GitHub
2. Connectez-vous à [Streamlit Cloud](https://streamlit.io/cloud)
3. Cliquez sur "New app"
4. Sélectionnez votre dépôt et la branche
5. Spécifiez le fichier principal : `accueil.py`
6. Cliquez sur "Deploy!"

## Structure du projet

- `accueil.py` : Point d'entrée principal de l'application
- `taxi_ml_predictions.py` : Module de prédictions ML
- `nyc_zones_data.py` : Données des zones de New York
- `requirements.txt` : Dépendances Python
- `data/` : Dossier contenant les jeux de données (non versionné)
