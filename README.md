# Image-Retrieval-Project

Le jeu de données Holidays est un ensemble d'images public  qui contient principalement des photos de vacances personnelles. Le jeu de données contient
1491 images au total : 500 requêtes et 991 images pertinentes correspondantes. Pour ce projet, j'ai redimensionné les images en 16*16*3.

1- Premièrement j'ai implémenté un système basique d'image retrieval en utilisant les pixels de l'image directement comme caractéristiques est l'idée la plus simple pour calculer la similarité entre deux images à savoir, la distance entre les pixels.

2- Puis j'ai Calculé la performance globale sur 500 requêtes.

3- Pour Améliorer les descripteurs d'images et les métriques de similarité, j'ai implémenter d'autres descripteurs tels que : Cosine distance, LBP, HOG, Color Histogram.

4- Et en fin j'ai implémenté une version simplifiée du Bag Of Visual Worss.
