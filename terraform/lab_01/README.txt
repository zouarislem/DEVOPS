Le fichier variables.tf a pour but de déclarer deux variable :
la variable filename qui est un fichier nommé "filename".
la variable content qui est de type string et qui va etre affichier dans le fichier filename.

Le fichier main.tf, la ressource nommé "games" va referencier ces deux variables.