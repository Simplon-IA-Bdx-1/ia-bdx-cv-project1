# Brief projet Zoo Galactique (classification d'images Kaggle)


Premier projet de Computer Vision, nous nous focaliserons sur la classification d'images qui est le problème le plus courant dans ce domaine.

A lire en guise d'introduction pour avoir une idée des problématiques principales résolues par le CV :

[5 computer vision techniques](https://heartbeat.fritz.ai/the-5-computer-vision-techniques-that-will-change-how-you-see-the-world-1ee19334354b)

## Les datasets

Nous utiliserons 3 datasets :

1.Sign Language Digits

2.Fashion MNIST

3.Galaxy Zoo

### Sign Language Digits

Il s'agit de photos de mains formant les 10 chiffres en langage des signes.

Le dataset est disponible [ici](https://www.kaggle.com/hamishdickson/preprocessing-images-with-dimensionality-reduction/data)

### Fashion MNIST

Une base d'images de vêtements fournie par Zalando, qui se trouve [ici](https://www.kaggle.com/zalando-research/fashionmnist)

### Galaxy Zoo

Une base d'images extraites du projet [Galaxy Zoo](https://www.zooniverse.org/projects/zookeeper/galaxy-zoo/).

Les données sont volumineuses, elles seront fournies sur clé USB (ou téléchargement :
[galaxy zoo data](https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/data)).


# 

# Choix de l'environnement de travail

Les développements se feront dans des notebooks Jupyter. Il y a 2 possibilités :

- Installer Anaconda sur sa machine et travailler en local dans un répertoire que l'on mettra sur github à terme
-

- Ouvrir un compte gratuit sur [Azure Notebooks](https://notebooks.azure.com/), si vous avez déjà un compte personnel microsoft vous pouvez l'utiliser. Ensuite créer un notebook.

# Atelier sur le thème de la réduction de la dimensionnalité

Regarder ce site d'introduction : [Dimensionality Reduction](https://idyll.pub/post/dimensionality-reduction-293e465c2a3443e8941b016d/)

Puis lire [cet article](https://www.analyticsvidhya.com/blog/2018/08/dimensionality-reduction-techniques-python/)
 sur 12 techniques de RdD :

Un notebook exemple d'application de PCA dont on pourra s'inpirer par la suite : [Notebook PCA](https://www.kaggle.com/hamishdickson/preprocessing-images-with-dimensionality-reduction)

## Quelques méthodes de réduction de dimensionnalité appliquées à des images

Activité en 6 groupes de 4 (ou 8 groupes de 3).

Préambule rapide sur la logique d'utilisation de scikit-learn.

Utiliser scikit-learn pour mettre en pratique sur les datasets 1 et 2 les méthodes suivantes :

PCA

ICA

t-SNE

UMAP

Chaque groupe se focalisera sur un seul couple dataset-méthode différent.

On essaiera de mettre en évidence des clusters dans un plot en 2 dimensions avec chaque exemple représenté par un symbole ou une couleur lié à sa classe.

Restitution par groupes, comparaison, différences entre les méthodes...

# Classification d'images sans CNN

Activité en binôme.

Appliquer des SVM ou XGBOOST aux datasets 1 et 2 pour la classification. Chaque binôme se focalisera sur un couple dataset-méthodes.

Evaluer la performance de l'algorithme choisi.

Dans un deuxième temps, les binômes SVM s'associeront aux binômes XGBOOST pour moyenner les prédictions et comparer les résultats avec les méthodes seules.

A noter que ces résultats pourront servir de baseline par la suite.


# Challenge Galaxy Zoo

## Inspection des données


## Préparation des données

Algorithmes de compression des images

## Transfer learning

Choix d'un modèle sur étagère

Choix du périmètre de transfer learning en fonction de la taille du sous-ensemble choisi

Application sur un sous-ensemble de Galaxy Zoo, recherche répartie sur plusieurs groupes d'un optimum entre :

* la compression des images
* les étages de l'architecture exclus de l'apprentissage

## Data augmentation

Justification et rapide panorama des principales techniques

Application au dataset Galaxy Zoo

## Récapitulatif des techniques utilisées et des résultats
