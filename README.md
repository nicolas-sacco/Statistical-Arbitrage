# Statistical-Arbitrage
Statistical Arbitrage model developed in python 

#Mean Reversion - Statisitcal Arbitrage


##Objective: Capitalize on statistical divergences from historical relationships between two equities.


##Steps:

1. Get Data: Clean, normalize, and get data in a form that we can feed into our model
2. Identify High Correlation between two equities using a ρ-value heatmap
3. Develop Algorithm: Backtest model to find past statistical deviations between the two equites
4. Analyze Performance: Evaluate performance of our Algorithm


# Explanation of Strategy
Statistical arbitrage is a trading strategy leveraging **correlation coefficients** and **z-scores** to exploit temporary mispricings in asset relationships. We identify pairs of assets with historically high positive correlation, signaling a tendency to move together. Z-scores quantify the difference between current and historical spreads, offering insights into potential overvaluation or undervaluation. The strategy assumes the "mean-reversion principle", anticipating that prices will revert to their historical norms over time. In summary, the strategy aims to **long the undervalued equity & short the overvalued equity**.

