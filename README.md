# Portfolio Data Analyst

**Zacharie Dannenmuller**  
Master Économétrie & Statistiques — ISFA Lyon 1

---

## Projets

### 1. Analyse des passages aux urgences en France (2017-2023)

**Contexte** : Analyse exploratoire de 7 ans de données hospitalières pour comprendre les dynamiques temporelles et géographiques des urgences en France.

**Données** : 247 933 observations, 98 départements — Source : [DREES / data.gouv.fr](https://www.data.gouv.fr/fr/datasets/series-longues-corrigees-du-nombre-de-passages-aux-urgences-2017-a-2023-en-france/)

**Résultats clés** :
- Effet lundi : +18.5% de passages vs dimanche
- Saisonnalité marquée : janvier +9% vs août
- Impact COVID : -47% en avril 2020 vs référence 2018-2019
- Disparités régionales : la Corse voit son activité augmenter de 50% l'été (tourisme)

**Stack** : Python, pandas, matplotlib, seaborn

📁 [Voir le notebook](projet1_urgences/analyse_urgences.ipynb)

---

### 2. Pipeline ETL & Analyse des dépenses de médicaments

**Contexte** : Construction d'un pipeline ETL pour agréger des données de consommation de médicaments (1.9M lignes) avec des données démographiques INSEE, puis analyse des disparités régionales.

**Données** : 
- Open Medic (Assurance Maladie) — 1.9M lignes, 24.3 Mds € de remboursements
- Population par département (INSEE)

**Pipeline ETL** :
- Extraction et nettoyage de sources hétérogènes
- Jointure et agrégation par région
- Stockage SQLite + export CSV

**Résultats clés** :
- Dépenses par habitant : de 331€ (Pays de la Loire) à 438€ (PACA)
- Clustering en 3 profils régionaux distincts
- Discussion honnête des limites méthodologiques (12 régions = échantillon trop petit pour modélisation prédictive)

**Stack** : Python, pandas, SQLite, scikit-learn

📁 [Voir le notebook](projet2_medicaments/etl_modelisation_medicaments.ipynb)

---

## Contact

📧 zacharie.dannenmuller@gmail.com  
