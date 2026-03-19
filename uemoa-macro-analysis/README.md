# Analyse des dynamiques macroéconomiques de la zone UEMOA (2000-2023)

## Description
Analyse exploratoire des trajectoires de croissance des 8 pays de l'UEMOA, incluant un test de β-convergence et une vérification empirique des faits stylisés de Kaldor.

## Données
- Source : Banque Mondiale (API via le package R `wbstats`)
- Période : 2000-2023
- Pays : Côte d'Ivoire, Sénégal, Mali, Burkina Faso, Bénin, Togo, Niger, Guinée-Bissau

## Indicateurs
- PIB réel et PIB par habitant (USD constants 2015)
- Taux de croissance du PIB
- Formation brute de capital fixe (% du PIB)
- Ouverture commerciale (% du PIB)
- Inflation (IPC)

## Résultats clés
- Signaux de β-convergence (les pays les plus pauvres croissent plus vite) mais non significatifs statistiquement (p = 0.285, n = 8)
- Corrélation faible mais significative entre investissement et croissance (r = 0.20, p < 0.01)
- Aucune relation détectable entre ouverture commerciale et croissance (r ≈ 0, p = 0.97)

## Outils
R | RMarkdown | tidyverse | wbstats | plotly | kableExtra

## Auteur
SILUE Chigata Gbambelé Ange — Licence 3 Statistique et Économie Appliquée, UPB
