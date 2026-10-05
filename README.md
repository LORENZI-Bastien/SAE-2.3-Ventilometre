# SAÉ 2.3 — Le ventilomètre

Projet de première année de BUT Réseaux et Télécommunications à Montbéliard.

## Objectif

Application web permettant de consulter les données de vent associées aux villes de résidence et l’historique des recherches.

## Travaux réalisés

Collecte des données météo, import de données, recherche dans l’interface et calcul du vent médian collectif.

## Outils et technologies

- Python / Flask
- SQLite
- API météo

## Organisation

Projet en autonomie.

## Présentation

[Mon portfolio](https://wonderful-chebakia-f83e9d.netlify.app/#projets)

## Configuration locale

Installer les dépendances avec `pip install -r requirements.txt`. Dans le dossier `src`, définir la variable `OPENWEATHER_API_KEY`, puis initialiser la base avec `python reset_db.py`, collecter la météo avec `python collect_wind.py` et lancer `python app.py`. Les données fournies sont fictives. Cette application pédagogique est destinée à une démonstration locale ; son fonctionnement n’a pas été vérifié ici.

## Livrables

La documentation, les guides français et anglais et la présentation initiale sont disponibles dans ce dépôt. `ventilometre-sources.zip` conserve les dossiers du code. Les données d’exemple sont fictives et la clé météo se configure localement. La vidéo de soutenance est disponible dans les Releases.
