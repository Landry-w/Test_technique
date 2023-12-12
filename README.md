# Test_technique
# Projet de Classification des Maladies du Riz en Égypte

## Objectif
Ce projet vise à développer un modèle de machine learning pour classifier les images de riz cultivé en Égypte selon les types de maladies. Le modèle sera construit en utilisant PyTorch et évalué sur la plateforme Zindi.

## Évaluation
La mesure d'évaluation de ce défi est la perte de journal.

## Ressources
- [Lien vers la compétition Zindi](https://zindi.africa/competitions/microsoft-rice-disease-classification-challenge)
- [Tutoriels PyTorch](https://pytorch.org/tutorials/)
- [Understanding PyTorch with an Example](https://towardsdatascience.com/understanding-pytorch-with-an-example-a-step-bystep-tutorial-81fc5f8c4e8e)
- [PyTorch Examples](https://pytorch.org/tutorials/beginner/pytorch_with_examples.html)

## Structure du Projet
- `notebook.ipynb`: Notebook contenant le code complet du projet.
- `submission_capture.png`: Capture d'écran de la soumission sur Zindi.
- `predictions.csv`: Fichier CSV contenant les prédictions du modèle sur l'ensemble de test.
- `model_weights.pth`: Fichier contenant les poids du modèle entraîné.

## Indication
Le notebook soumis contient une mise du script permettant de générer le fichier .csv des probilités de prediction. 
L'idée est d'apporter une touche innovente permettant de recuperer automatiquement le fichier .pth optimal permettant d'obtenir les meilleures probabilités plutôt que l'approche précédantes qui visait généré fichier par fichier et à soumèttre ensuite le fichier .csv resultant à la plateforme Zindi pour l'obtention du score. Nous vous indiquerons egalement les mises à jour à venir. 

## Approche utilisée
L'approche utilisée pour la realisation de ce projet est l'apprentissage par transfert de pytorch qui consiste au choix d'un modèle pré-entrainé (ResNet50 dans notre cas) et à l'adapter à notre use case.
