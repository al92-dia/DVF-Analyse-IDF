## Projet de Data analyst de Al Ousseynou Diallo
# Analyse du marché immobilier en Île-de-France (2024)

## À propos du projet
Analyse complète de 127 466 transactions immobilières DVF (Demandes de Valeurs Foncières)
en Île-de-France sur l'année 2024. Données officielles issues de data.gouv.fr.

## Structure du projet
| Notebook | Description |
|----------|-------------|
| `DVF_Analyse.ipynb` | Collecte et préparation des données (8 départements IDF) |
| `DVF EDA.ipynb` | Analyse exploratoire — prix, saisonnalité, surface, outliers |
| `DVF Modelisation.ipynb` | Modélisation XGBoost — prédiction du prix au m² |

## Résultats clés
- Paris : **9 800 €/m²** en médian — 3x plus cher que la Seine-et-Marne (3 107 €/m²)
- Juillet est le mois record avec **14 449 transactions** (+70% vs août)
- Les studios (< 30m²) coûtent **2,4x plus cher** au m² que les grands appartements
- Modèle XGBoost : R² = **0.549** — la localisation est la variable la plus prédictive (SHAP)

## Stack technique
- Python · pandas · matplotlib · scikit-learn · XGBoost · SHAP · Folium
- Données : [DVF data.gouv.fr](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres-geolocalisees/)

## Auteur
**Al Ousseynou Diallo** — Data Analyst · Île-de-France 2026
### alousseynoudiallo92@gmail.com
