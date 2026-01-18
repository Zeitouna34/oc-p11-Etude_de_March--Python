# 🌍 Projet 5 - Étude de Marché ACP & Clustering Python

## Résumé du projet :
Étude de marché internationale pour La Poule qui Chante (export poulets bio) via analyse Python avancée. L'objectif était d'identifier les groupements de pays pertinents pour prioriser les marchés d'export, en analysant 170 pays sur 15 variables PESTEL (FAO, Banque Mondiale) via ACP et clustering hiérarchique, puis présenter des recommandations stratégiques au COMEX.

## Tâches réalisées :
Collecte et nettoyage multi-sources : Extraction données FAO (production agricole), Banque Mondiale (PIB, urbanisation), données mondiales (population), fusion sur codes ISO pays, imputation valeurs manquantes, détection outliers.
Analyse en Composantes Principales (ACP) : Normalisation StandardScaler, réduction de 15 dimensions à 2-3 composantes principales (67% variance expliquée), cercle des corrélations, projection des pays sur plan factoriel, interprétation axes (Axe 1 = Développement économique, Axe 2 = Taille marché).
Clustering hiérarchique (CAH) + K-means : Dendrogramme méthode Ward, coupe à k=4 clusters, validation par méthode du coude et silhouette score, profil détaillé de chaque cluster (moyennes par variable).
Recommandations stratégiques COMEX : Présentation PowerPoint avec identification de 4 clusters, priorisation Allemagne/UK (marchés premium proches, ROI 12 mois), plan d'action phases 1-2-3, projection CA export +250% sur 3 ans.

## Compétences et outils mobilisés :
Outils : Python (Pandas, Scikit-learn PCA/KMeans, Scipy CAH, Matplotlib/Seaborn), Jupyter Notebook (2 notebooks : nettoyage / analyses).
Expertise : Analyse PESTEL, ACP (réduction dimensionnalité), clustering hiérarchique, K-means, interprétation statistique, data storytelling COMEX, recommandations business.

## Livrables :
Notebook nettoyage des données
Notebook ACP & clustering (cercle corrélations, dendrogramme, profils clusters)
Dataset CSV maître (170 pays, 15 variables)
Présentation COMEX (méthodologie, 4 clusters, recommandations stratégiques)
