# Commandes sur le terminal

Liste de quelques commandes de bases pour naviguer sur le terminal et 
manipuler des fichiers / dossiers.

>Les commandes listées fonctionnent sur un environnement **Unix** / **Linux**,
elles ne conviennent pas toutes à un environnement **Windows**.
Sur **Windows**, utiliser **Git Bash** ou **Cmder**.

Syntaxe des commandes:
````sh
programme commande --option argument
````

##Navigation

Connaitre le dossier actuel:
```sh
pwd
```

Connaitre l'utilisateur actuel:
````sh
whoami
````

Se déplacer dans un dossier
````sh
cd /chemin/absolu
cd chemin/relatif
cd ~/mon-dossier
````

>Le caractère '~' représente le *répertoire* d'accueil de l'utilisateur.

Lister les fichiers et dossiers:
````sh
ls
ls -l
ls _la
````

##Manipulation de fichiers et dossiers

Créer un fichier vide:
````sh
touch mon-fichier.txt
````

Afficher le contenu d'un fichier:
````sh
cat mon fichier.txt
````

Déplacer un fichier
````sh
mv mon-fichier.txt destination/nouveau-nom.txt
````

Supprimer un fichier
````sh
rm mon-fichier.txt
````

Créer un dossier
````sh
mkdir mon-dossier
````

Supprimer un dossier
````sh
rm -rf mon dossier
````

>Les options 'r' (recursif) et 'f'
