Liste des fonctions et leurs utilitées :

>git config --global user.name Tony
>git config --global user.email tony@tony.fr
Ces deux fonctions permettent de s'enregistrer dans .gitconfig en tant qu'utilisateur


>git config --global core.editor vim 
Pour choisir un editeur de texte lors des commit


>git init 
Cette fonction permet d'initialiser un projet GIT en créant le dossier .git/


>git status 
Permet de verifier que tout fonctionne bien et avoir un aperçu de l'etat actuel du dépot GIT (fichiers suivis, commits,...)


>git add
Permet d'indexer un fichier 


>git rm --cached
Permet de désindexer un fichier 


>git commit 
La commande qui permet de faire des commits, en ajoutant: -m "contenu" , le commit sera fait sans ouvrir un editeur 


>git log
Permet de voir un historique des commit et de voir les clefs de hachage


> git log --oneline
> git shortlog
Permet de voir le dernier GIT effectué


>git help
Permet d'afficher les commandes basique de GIT et leurs utilités


>git mv mon_ancien_fichier mon_nouveau_fichier
Permet de changer le nom du fichiers


>git rm mon_fichier
Permet de supprimer un fichier suivi de GIT


>git ls-files
une commande qui permet de voir tout les fichiers suivis 


>
