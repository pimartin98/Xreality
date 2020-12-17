Comme le projet unity contient des fichiers de gros formats, quelques configuration avec lfs sont nécessaires.

Pour les utilisateurs Windows :
Premièrement, il faut se rendre sur la page https://git-lfs.github.com/ pour télécharger l'extension de ligne de commande de lfs.

Sur le git bash :

$ git lfs install
pour indiquer sur quels fichier utiliser lfs
$ git lfs track "*"
Pour des configuration manuelles :
$ git add .gitattribute
$ git add <--all> <nom du dossier/ficher à ajouter>

Pour vérifier quels sont les fichiers qui prennent le plus d'espace dans le repository
$ git lfs migrate info

Convertion des fichier à LFS
$ git lfs migrate import

$ git push


