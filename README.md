#  Analyse du Marché Immobilier en Île-de-France (DVF 2021-2025)

##  Description
Analyse complète du marché immobilier francilien à partir des données officielles
des Demandes de Valeurs Foncières (DVF) publiées par la DGFiP.

**Question centrale :** Comment ont évolué les prix au m² dans les 8 départements
d'Île-de-France entre 2021 et 2025 ?

##  Source des données
- **DVF** — data.gouv.fr (Ministère de l'Économie)
- **Périmètre :** 8 départements IDF (75, 77, 78, 91, 92, 93, 94, 95)
- **Volume :** ~834 000 transactions (Appartements et Maisons)
- **Période :** 2021 → 2025

##  Stack technique
| Outil | Usage |
|-------|-------|
| Python / pandas | Nettoyage et traitement des données |
| PostgreSQL | Stockage et requêtes analytiques |
| SQLAlchemy | Connexion Python → PostgreSQL |
| Power BI | Dashboard interactif |
| DBeaver | Administration base de données |

##  Dashboard Power BI
**Page 1 — Vue générale**
- KPIs : nombre de ventes, prix médian, prix moyen
- Carte géographique IDF par département
- Graphique à barres et anneau par département
- Slicer interactif par département

**Page 2 — Évolution des prix**
- Courbe d'évolution 2021-2025 par département
- Tableau comparatif des prix médians par année
- Slicer interactif par département

##  Principaux résultats
- **Paris (75)** : baisse de 10 968 → 9 833 €/m² (-10,3%)
- **Hauts-de-Seine (92)** : baisse de 7 281 → 6 634 €/m² (-8,9%)
- **Val-de-Marne (94)** : baisse de 5 232 → 4 925 €/m² (-5,9%)
- Tous les départements IDF ont baissé suite à la hausse des taux (2022-2023)

