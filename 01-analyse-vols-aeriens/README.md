# ✈️ Analyse des Données de Vols Aériens en Inde

## 📋 Contexte

Ce projet analyse **300 153 vols intérieurs en Inde** pour comprendre les facteurs qui influencent le prix des billets d'avion. L'objectif est de fournir des recommandations concrètes aux voyageurs et aux professionnels du secteur.

## 🎯 Questions business

1. Quelle compagnie domine le marché ?
2. Comment le prix varie selon la classe, l'horaire et le moment de réservation ?
3. Quel est le meilleur moment pour réserver un vol au meilleur prix ?

## 📊 Dataset

| Caractéristique | Valeur |
|-----------------|--------|
| **Lignes** | 300 153 |
| **Colonnes** | 11 |
| **Source** | Données de réservation (6 compagnies indiennes) |
| **Période** | 2023 |

### Variables
- `airline` : Compagnie aérienne
- `source_city` / `destination_city` : Villes de départ et d'arrivée
- `departure_time` / `arrival_time` : Créneaux horaires
- `class` : Economy ou Business
- `duration` : Durée du vol (heures)
- `days_left` : Jours avant le départ au moment de la réservation
- `price` : Prix du billet (₹)

## 🔍 Méthodologie

1. **Nettoyage** : Vérification des valeurs manquantes, analyse des outliers
2. **Exploration** : Distribution des variables, statistiques descriptives
3. **Analyse** : Groupby, visualisations, comparaisons
4. **Recommandations** : Insights actionnables basés sur les données

## 📈 Résultats clés

### 1. Le délai de réservation impacte fortement le prix
![Prix vs jours restants](screenshots/prix_vs_days_left.png)

- **Réserver 1-2 jours avant** : ~35 000 ₹ en moyenne
- **Réserver 20-40 jours avant** : ~18 000 ₹ en moyenne
- **Économie potentielle** : ~75%

### 2. Vistara et Air India dominent le marché
Ces deux compagnies représentent **70% des vols** du dataset.

### 3. Business = 8× le prix Economy
Un billet Business coûte en moyenne 61 000 ₹ contre 7 400 ₹ en Economy.

### 4. Les vols Early Morning sont les moins chers
Bonne option pour les voyageurs flexibles et soucieux de leur budget.

## 💡 Recommandation finale

> Pour un vol **Delhi → Mumbai en Economy** au meilleur prix :
> - Réserver **20-30 jours avant** le départ
> - Choisir **AirAsia ou SpiceJet**
> - Opter pour un départ **Early Morning**

## 🛠️ Outils utilisés

- **Python 3.x**
- **Pandas** : Manipulation des données
- **Matplotlib / Seaborn** : Visualisation
- **Jupyter Notebook** : Environnement de développement

## 📁 Fichiers

```
01-analyse-vols-aeriens/
├── README.md                              # Ce fichier
├── Analyse_Vols_Aeriens_Portfolio.ipynb   # Notebook principal
├── airlines_flights_data.csv              # Dataset source
└── screenshots/                           # Captures des graphiques
```

## 🚀 Comment exécuter

```bash
# Cloner le repo
git clone https://github.com/silue-ange/data-analyst-portfolio.git

# Naviguer vers le projet
cd data-analyst-portfolio/01-analyse-vols-aeriens

# Ouvrir le notebook
jupyter notebook Analyse_Vols_Aeriens_Portfolio.ipynb
```

## 📫 Contact

**Ange SILUE** — angesilue02@gmail.com
