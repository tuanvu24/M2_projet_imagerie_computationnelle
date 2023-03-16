# M2_projet_imagerie_computationnelle
## Réseaux de Neumann pour la restauration d’image avec application aux images ultrasonore

Notre projet qui s'est inspiré à partir d'un projet déjà developpé auparavant
https://github.com/dgilton/neumann_networks_code  
https://github.com/dgilton/iterative_reconstruction_networks

## Jeu de données
- Celeba dataset. Lien de téléchargement: 
https://drive.google.com/drive/folders/0B7EVK8r0v71pTUZsaXdaSnZBZzg?resourcekey=0-rJlzl934LzC-Xp28GeIBzQ

- Breast ultrasound image dataset. Lien de téléchargement: 
https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset 

Nous avons déjà ces données sur le Drive partagé si vous utilisez notre google colab.

## Comment ça marche
- Avec google colab (https://drive.google.com/drive/folders/1XyiyQwervSAdEZfYqCOLD7hYI5Z6GKGJ?usp=sharing), nous avons 1 fichier qui fait le test 'gaussian_blur' avec des données de celeba, 2 fichiers pour le test 'gaussian_blur' et 'gaussian_blur_nonoise' avec des images ultrasonores.
- Avec les codes en local, il faut télécharger les jeux de données au dessus et changer les paths qui se trouve dans gaussian_blur_neumann_celeba_test.py et gaussian_blur_neumann_celeba_train.py. Puis vous lancez le fichier gaussian_blur_neumann_celeba_test.py

## Résultat/Train location
- trained_model: qui contient les modèles entrainé en fichier .ckpt
- result_test: qui contient l'image originale, l'image floutée et l'image de reconstruction pour chaque image entrée
- ui_dataset: contient le dataset de Breast ultrasound image dataset
- img_align_celeba: contient le dataset de celeb_a

## Explication du code
