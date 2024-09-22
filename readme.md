# Analyse des Données Boursières

L'analyse des données boursières est un processus qui consiste à examiner et interpréter les données de prix des actions afin de comprendre leur performance passée et d'anticiper les tendances futures. Ce projet utilise les données historiques des actions de Procter & Gamble (PG) pour calculer les rendements et évaluer la performance de l'action.

## 1. Chargement des Données

Les données historiques sont généralement fournies sous forme de fichiers CSV, contenant des informations sur les prix d'ouverture, de fermeture, les plus hauts et plus bas, ainsi que le volume des transactions. Ces données sont chargées dans un DataFrame Pandas pour faciliter leur manipulation.

## 2. Rendement Simple

Le rendement simple d'une action est calculé comme le pourcentage de changement du prix de l'action d'une période à l'autre. Il se calcule avec la formule :

$$
R_t = \frac{P_t - P_{t-1}}{P_{t-1}} = \frac{P_t}{P_{t-1}} - 1
$$


où \(R_t\) est le rendement à la période \(t\) et \(P_t\) est le prix de fermeture à la période \(t\). Les rendements simples permettent d'évaluer la performance quotidienne d'un actif.

## 3. Rendement Logarithmique

Le rendement logarithmique est une autre manière de mesurer la performance des actions. Il est calculé comme :

$$
R_t = \frac{P_t - P_{t-1}}{P_{t-1}} = \frac{P_t}{P_{t-1}} - 1
$$


où \(\ln\) représente le logarithme naturel. Les rendements logarithmiques sont souvent préférés dans les analyses financières, car ils permettent de mieux modéliser les distributions de rendement et facilitent les calculs d'analyses plus complexes, comme le calcul de la volatilité.

## 4. Visualisation des Rendements

Les graphiques des rendements simples et logarithmiques aident à visualiser la performance historique de l'action. Ils permettent d'identifier des tendances, des anomalies et d'autres caractéristiques importantes des données.

## 5. Interprétation des Résultats

Les rendements moyens (quotiens et annuels) fournissent des informations sur la performance générale de l'action sur la période étudiée. Un rendement positif indique une performance favorable, tandis qu'un rendement négatif peut signaler une baisse de la valeur de l'actif.

## Conclusion

L'analyse des données boursières, par le biais de calculs de rendements, est essentielle pour les investisseurs qui cherchent à évaluer la rentabilité de leurs investissements. En utilisant des données historiques, les investisseurs peuvent prendre des décisions éclairées sur l'achat, la vente ou la conservation d'actions.
