# Source des données

* **Étudiant :** IDRISSI AZAMI Marwa (Code Apogée 25007652), Groupe G2
* **Sujet :** F1 — Risque de crédit en Allemagne[cite: 4, 5]
* **Tâche :** Classification binaire à coûts asymétriques[cite: 4]
* **Jeu de données :** Statlog (German Credit Data), 1 000 observations (unité : demande de crédit), 20 variables explicatives + 1 cible `creditability` (`good` = 700, `bad` = 300)[cite: 4, 5]
* **Origine et période :** Hofmann, H. (1994), UCI Machine Learning Repository, https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data (aussi présent sur Kaggle : `uciml/german-credit`)[cite: 4, 5]
* **Copie utilisée :** version avec en-têtes et libellés lisibles, issue du paquet `scorecardpy` (https://github.com/ShichenXie/scorecardpy)[cite: 5]
* **Licence :** CC BY 4.0 (Creative Commons Attribution 4.0 International — source UCI)
* **Date d'extraction :** 17/11/2026[cite: 5]
* **Fichier :** `data/raw/german_credit.csv`[cite: 4, 5]
* **Matrice de coûts (UCI) :** classer un mauvais client (`bad`) comme bon (`good`) coûte 5 fois plus cher que l'inverse (coût FN = 5, coût FP = 1)[cite: 5]
