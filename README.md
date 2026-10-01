# Segmentation clients e-commerce par analyse RFM

## Le problème
Un e-commerçant traite des milliers de clients de la même façon.
Résultat : il dépense autant en marketing pour un client qui achète
une fois que pour son meilleur client fidèle depuis 3 ans.

## La solution
L'analyse RFM (Récence, Fréquence, Montant) permet d'identifier
automatiquement 5 profils de clients distincts et d'adapter
la stratégie marketing à chacun.

## Résultats clés
- 541 909 transactions analysées sur 12 mois
- 4 338 clients segmentés en 5 groupes
- CA total : 8 911 407 £
- Les Champions (30% des clients) génèrent 73% du CA
- 646 clients à risque représentent 1 040 932 £ récupérables

## Segments identifiés

| Segment          |Clients| Part CA | Action recommandée           |
|------------------|-------|---------|------------------------------|
| Champions        | 1 319 | 73%     | Programme VIP                |
| Clients à risque | 646   | 11.7%   | Réactivation urgente         |
| Clients perdus   | 1 504 | 8.6%    | Campagne "Vous nous manquez" |
| Clients fidèles  | 610   | 5.7%    | Montée en gamme              |
| Nouveaux clients | 259   | 1%      | Onboarding 30 jours          |

## Stack technique
- **Python** — Pandas, NumPy, Plotly
- **Analyse** — Segmentation RFM, K-means
- **Visualisation** — 4 graphiques interactifs Plotly

## Structure du projet
- data/ — Dataset brut et dataset nettoyé
- notebooks/01_exploration.ipynb — Exploration initiale
- notebooks/02_nettoyage.ipynb — Nettoyage des données
- notebooks/03_rfm_segmentation.ipynb — Segmentation RFM
- notebooks/04_visualisations.ipynb — Visualisations et insights

## Source des données
Dataset UCI Online Retail — 541 909 transactions réelles
d'un e-commerçant britannique (2010-2011)

---
*Projet réalisé par [ClearInsight]
(https://github.com/clearinsightdata)*