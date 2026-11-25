### F3. Prévision de l'inflation

- **Question :** le chômage et le taux directeur aident-ils à prévoir l'inflation d'un an sur l'autre ?
- **Tâche :** régression sur séries mensuelles.
- **Données :** FRED CPIAUCSL, UNRATE et FEDFUNDS, par exemple https://fred.stlouisfed.org/graph/fredgraph.csv?id=CPIAUCSL. Environ 950 observations mensuelles.
- **Prétraitement :** calculer la variation annuelle de l'indice des prix, aligner les dates, construire des retards.
- **Modèles :** dernière valeur (référence), régression Ridge, gradient boosting.
- **Métriques :** RMSE sur un horizon de 12 mois.
- **Livrable :** notebook et analyse de l'importance des variables.
- **Risque :** les séries économiques sont révisées après publication. Les données actuelles ne sont pas celles disponibles à l'époque : c'est un biais d'anticipation (*look-ahead bias*). Le signaler dans le rapport.
