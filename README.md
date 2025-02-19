# Trading-Strategies

## Description
Ce projet implémente et analyse trois stratégies de trading sur l'action Amundi :
- Moving Average (MA)
- Relative Strength Index (RSI)
- Bollinger Bands (BB)

## Stratégies

### Moving Average (MA)
- Utilise deux moyennes mobiles (courte et longue)
- Génère des signaux basés sur les croisements
- Performance : +5.21% (période de test)
- Win Rate : 50.00%

### RSI
- Indicateur de momentum
- Identifie les conditions de surachat/survente
- Performance : +1.57%
- Win Rate : 55.56%

### Bollinger Bands
- Utilise les bandes de volatilité
- Signals basés sur les déviations de prix
- Performance : -3.81%
- Win Rate : 41.18%

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib

## Résultats (20/01/2025 - 18/02/2025)
- Meilleure performance : Stratégie MA
- Meilleur Sharpe Ratio : 4.69 (MA)
- Meilleur Win Rate : 55.56% (RSI)

## Installation
```bash
pip install pandas numpy matplotlib
```

## Usage
1. Téléchargez les données historiques Amundi
2. Ouvrez le notebook Jupyter
3. Exécutez les cellules pour voir les résultats

## Structure du Projet
- `Amundi_Trading_Strategies.ipynb` : Notebook principal
- `Amundi Stock Price History.csv` : Données historiques

## Licence
Pour usage personnel et éducatif uniquement.
