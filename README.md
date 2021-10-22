# Comment Choisir le Modèle Approrié à Un Problème de AI

Le Machine Learning, aussi appelé apprentissage automatique en français, est une forme d’intelligence artificielle permettant aux ordinateurs d’apprendre sans avoir été programmés explicitement à cet effet.

En Machine Learning, il existe une tonne de modèles: La régression logistique, les arbres de décision,
les support vector machine, les k-nerest neighbors, les random forests, les réseaux de neurones, ....

Bref il est difficile faire son choix parmi toutes ces possibilités, dans ce document nous allons explorer quelques possibibilité de critère de choix de modèle pour selectionner le bon modèle pour son projet en machine learning.

## Conseil #1

Ne travailler qu'avec les modèles que l'on comprend vraiment. Car nous permet d'optimiser et regler ses hyper paramètres et ensuite cela nous permet également d'éviter d'utiliser un modèle dans un context qu'il n'est pas adapté pour ne pas avoir des comportements anormaux sans qu'on ne les comprennent.

Il vaut mieux du bon travail sur un modèle basique que du mauvais travail sur des modèles sofistiqués.

## Conseil #2

Par les modèles que vous comprenez, commencez toujours par implementer le plus simple possible. Car la plupart des modèles sofistiqués consomment beaucoup de ressources et prennent beacoups de temps pour exécuter et complexes à regler.

## Exemple

Par exemple si vous travailliez sur un modèle de régression commencez toujour par:
* LinearRession
* Lasso
* Ridge
  
Si vous travailliez sur problème de classification commencez par:
* LogisticRegression
* LinearSVC
* KNeighborsClassifier
  
Car ce sont des modèles simples, facile à entrainer et facile regler également.

## Critère de choix du modèle d'un Data Scientiste
Quelles sont les critères qui permettent à un Data Scientiste de choisir un modèle plutôt qu'un autre.
Par exemple choisir un arbre decision plutôt qu'une régression Logistique.

## Critère #1: Quantité de données

Le premier critère de choix d'un modèle est la quantité de donée avec laquelle nous travaillons.

### Modèle adaptés aux gros Datasets

![image 1](images/1.png)
![image 2](images/2.png)

### Modèle adaptés aux petits Datasets

![image 3](images/3.png)

Qu'est ce qui explique cela, le fonctionnent des algorithmes (d'où le premier conseil #1: ne travaillez qu'avec des algorithme qu'on comprend).
