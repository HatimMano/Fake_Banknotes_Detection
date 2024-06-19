# Détection de Faux Billets 💸🔍

## Aperçu du Projet :
Bienvenue dans notre aventure palpitante de détection de faux billets ! 💸 Ce projet a pour mission de déployer un algorithme super intelligent capable de flairer les contrefaçons de billets grâce à des données dimensionnelles (6 métriques). Nous avons un jeu de données divisé en deux catégories : les billets authentiques (True) et les billets contrefaits (False). Avec une panoplie de techniques de machine learning, nous allons analyser, prédire et, surtout, démasquer les faux billets ! 🔍✨

## Méthodes Utilisées :
- **Régression Linéaire Multiple et k-NN (k-Plus Proches Voisins)** :
  Ces techniques sont nos détectives, utilisées pour combler les trous dans notre jeu de données. 🕵️‍♂️🕵️‍♀️

- **Régression Logistique & k-Means avec Analyse en Composantes Principales (ACP)** :
  Nos super-héros pour l'analyse prédictive et la classification des résultats. Ils permettent de séparer le bon grain de l'ivraie. 🦸‍♂️🦸‍♀️

### Ajouts Fun 🎉 :
- **Visualisation des Données :** Imaginez des graphes colorés ! 📊 Nous avons utilisé des scatter plots et pair plots pour voir les relations entre les caractéristiques des billets et leur authenticité. 🌈
- **Analyse Statistique :** Grâce aux tests de Kruskal-Wallis, nous avons comparé les distributions des caractéristiques entre les vrais et les faux billets. Comme un jeu de comparaison, mais avec des stats ! 📈📉
- **Réduction de Dimensionnalité :** L'ACP est notre artiste de l’espace, réduisant la dimensionnalité des données avant l'attaque des algorithmes de clustering. 🎨🔍
- **Détection des Colinéarités :** Avec le facteur d'inflation de la variance (VIF), nous traquons les colinéarités entre les variables. Pas de doublons dans notre équipe ! 🔍👥

## Résultats :
Après moult essais et analyses, le modèle de régression logistique a été couronné vainqueur 🏆 grâce à sa performance légèrement supérieure au modèle k-means (consultez les scores F1 et d'exactitude). Un script Python a été concocté pour effectuer le prétraitement nécessaire à la prédiction de l'authenticité des billets, directement à partir d'un fichier source. Magique, non ? ✨🧙‍♂️

## Conclusion :
En somme, ce projet démontre une approche complète et amusante de la détection des faux billets. Nous avons intégré une multitude de techniques de machine learning pour le prétraitement et l'analyse prédictive. La régression logistique est notre championne 🥇, offrant un modèle robuste et précis pour distinguer les billets authentiques des contrefaits. Rejoignez-nous dans cette quête contre la contrefaçon et devenez, vous aussi, un expert de la détection de faux billets ! 🕵️‍♀️💸
