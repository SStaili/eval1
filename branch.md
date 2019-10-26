>git branch XXXXX
Permet de créer une branche avec le nom correspondant à XXXXX


>git checkout XXXXX
Permet de se deplacer dans la branche XXXXX


>git checkout -b XXXXXXXX
Crée une branche et se deplace dedans 


>git branch -d [nom de votre branche]
Supprime la branche concernée 


>git branch -D [nom de votre branche]
Force la suppression d'une branche 


>git merge dev
Permet de fusionner des branches
En faisant git checkout YYYYY juste avant et la commande git merge XXXXX on va merger XXXXX dans YYYYY



>git stash 
Prend l'état du répertoire de travail, fichiers modifiés, index. Puis l'enregistre dans la pile des modifications non finies que l'on peut réappliquer n'importe quand


>git stash list
permet de lister sur la branche les différents stash


>git stash apply
récupère le contenue du stash et l'applique 


>git stash drop 
Supprime le conten de la remise


>git tag
Affiche la list des tags

>git tag -l 'XXXXX.xx'
Cherche un tage particulier


>git show vx.x
Permet de voir un tag annoté


>git remote
permet de lister les dépots distants 


>git remote add [alias] [chemin_du_serveur_distant]
Permet d'ajouter un dépot distant 


>git remote rm [alias]
Permet de supprimer un dépot distant 


>git remote rename [alias] [new_alias]
Permet de renommer un dépot distant 


>git fetch origin
permet de recupérer la branche distante (et cela se fait localement et son fusionner avec sa branche master )


>git log master..origin/master
permet de comparer les différences entre master local et master distant (après un fetch)


>git pull 
cette commande est l'équivalent des "git fetch origin + git merge origin/master" 


>git push [nom-distant] [nom-de-branche]
La commande permet de publier une branche distante


>git remote show origin 
Permet d'inspecter un dépôt distant 
