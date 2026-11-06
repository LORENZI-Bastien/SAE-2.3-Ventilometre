# SAÉ 2.3 · Le ventilomètre

> Application web qui affiche le vent du jour dans les villes de résidence des étudiants, avec historique des recherches et vent médian collectif.

| | |
|---|---|
| **Formation** | BUT Réseaux et Télécommunications, Montbéliard |
| **Année** | 1<sup>re</sup> année, semestre 2 |
| **Organisation** | En équipe de 3 |
| **Outils et notions** | `Python` `Flask` `SQLite` `API OpenWeather` `HTML / Jinja` |

## Fonctionnalités

- Recherche d’un étudiant et affichage du vent dans sa ville de résidence
- Historique des recherches, global et par utilisateur
- Calcul du vent médian collectif du jour
- Collecte des données météo par l’API OpenWeather et import des étudiants depuis un fichier JSON

## Lancer l’application en local

```bash
cd code
pip install -r requirements.txt
export OPENWEATHER_API_KEY="votre_cle"   # sous Windows : set OPENWEATHER_API_KEY=votre_cle
python reset_db.py      # recrée la base de démonstration
python collect_wind.py  # récupère la météo du jour
python app.py           # puis ouvrir http://127.0.0.1:5000
```

La base `students.db` et le fichier `etudiants.json` ne contiennent que des **données fictives**. Aucune clé d’API n’est publiée.

## Contenu du dépôt

```
code/          application Flask (app.py, scripts, templates, base de démo)
docs/          guides d’installation et d’utilisation (français et anglais), vue globale
presentation/  présentation initiale du projet
```

- [Guide d’installation](docs/guide-installation.pdf) · [Guide utilisateur](docs/guide-utilisateur.pdf)
- [Installation guide (EN)](docs/installation-guide-en.pdf) · [User guide (EN)](docs/user-guide-en.pdf)
- [Vidéo de soutenance](https://github.com/LORENZI-Bastien/SAE-2.3-Ventilometre/releases/tag/v1.0)

---

<sub>Bastien Lorenzi · BUT Réseaux et Télécommunications, parcours cybersécurité · [Portfolio](https://wonderful-chebakia-f83e9d.netlify.app/#projets) · [Profil GitHub](https://github.com/LORENZI-Bastien)</sub>
