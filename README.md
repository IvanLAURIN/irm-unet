# irm-unet
Segmentation de tissus tumoraux sur le dataset BraTS 2019

## Introduction
L'ensemble de programmes disponibls sur ce dépôt permet l'entraînement de modèles de réseaux de neurones pour la segmentation de tissus tumoraux dans des IRMs de cerveaux issus de la base de données BraTS 2019.

Ces programmes sont fournis sous la forme de Notebooks Jupyter. La documentation de ces programmes est incluse dans les notebooks.

## Configuration
Les programmes sur ce dépôt ont été conçus et testés avec la configuration suivante : 
-  Python 3.10
-  Pandas 1.5
-  NiBabel 5.0
-  NiLearn 0.10
-  CUDA Toolkit 11.2
-  CuDNN 8.1
-  Tensorflow 2.10
-  Matplotlib 3.7
-  Scikit-learn 1.2

## Pré-traitement
Avant de lancer l'entraînement des modèles, il est nécessaire d'exécuter le notebook de pré-traitement intitulé **Preprocessing.ipynb**. Ce notebook se charge du téléchargement de la base d'images

## Traitement d'images 2D
Le notebook intitulé **U-Net 2D.ipynb** permet le traitement de tranches 2D au sein des images 3D de la base. Les données d'entrée peuvent être multi-modales.

## Traitement d'images 3D
Le notebook intitulé **U-Net 2D.ipynb** permet le traitement des volumes 3D de la base. Les données d'entrée peuvent être multi-modales.