# P6_Classification_automatique
## Classification automatique d’objets de biens de consommation 
![P6_1](https://user-images.githubusercontent.com/71134226/117356126-b1c83880-aeb3-11eb-9f3d-bf1615bbdb85.gif)
![P6_2](https://user-images.githubusercontent.com/71134226/117356161-bc82cd80-aeb3-11eb-82a0-2dc39b21e985.gif)

L’entreprise __"Place de marché”__, qui souhaite lancer une marketplace e-commerce.
Sur la place de marché, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.

Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit.

Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

## Les données
Jeu de données d’articles avec le lien pour télécharger la photo et une description associée.

## Mission
- réaliser une première étude de faisabilité d'un moteur de classification d'articles basé sur une image et une description pour l'automatisation de l'attribution de la catégorie de l'article.

- analyser le jeu de données en réalisant un prétraitement des images et des descriptions des produits, une réduction de dimension, puis un clustering. 
Les résultats du clustering seront présentés sous la forme d’une représentation en deux dimensions à déterminer, qui ’illustrera le fait que les caractéristiques extraites permettent de regrouper des produits de même catégorie.

## Contraintes
- Afin d’extraire les features, mettre en œuvre a minima un algorithme de type SIFT / ORB / SURF.
- Un algorithme de type CNN Transfer Learning peut éventuellement être utilisé en complément, s’il peut apporter un éclairage supplémentaire à la démonstration.
![p6_3](https://user-images.githubusercontent.com/71134226/117356222-ca385300-aeb3-11eb-9444-7b0918364f95.gif)
![p6_4](https://user-images.githubusercontent.com/71134226/117356354-e936e500-aeb3-11eb-855f-107e16e76e2f.gif)
