>git --no-pager log --oneline
Permet d'afficher les log et sortir de la commande 


>git --no-pager log -X --oneline
Similaire au précédent mais en affichant les X derniers commits


>git log --author "Antoine07"
Permet de consulter les commits d'un auteur en particulier 


>git log --since=1.day
>git log --before="2019-09-01"
Permet de consulter les commits depuis les dates respectivement données


>git log XXXXX.txt
Permet de consulter l'hisotrique d'un fichier en particulier


>git log -p XXXXXX.txt
Permet de voir les ajout/suppression de lignes sur un fichier


>git log --stat XXXXXX.txt
Permet de visualiser les statistiques des modifications des fichiers et de savoir combien de ligne de code ont été modifiées ou ajoutées sur un fichier/projet 


>git log -E -i --grep='XXXX'
La commande suivante permet de rechercher des logs. 
E expression pour rechercher les occurences et i pour insensible à la majuscule/minuscule


>git diff
permet lorsque l'on fait une modification dans un fichier avant de l’indexé de visualiser les modifications


>git diff --cached
affichera les différences entre le dernier commit et l’index 


>git diff HEAD~X
Recule de X commit en arrière 


>git diff HEAD~X HEAD
Si on souhaite visualiser les différences entre le HEAD et un état antérieur du dépôt, par exemple X commits


>git diff --stat
Faire des stats sur les différence opéré dans les fichiers


>git restore
Annule les modifications dans l’espace de travail


>git restore --stagede 
si on refait la modification et que l’on ajoute le fichier dans l’index


>git reset HEAD~1
Reviens au dernier commit 


>git reset --soft HEAD~1
Annule le dernier commit et met tout dans la staging area sans perte


>git reset "numéro de log"
se déplacera sur le commit concerné en annulant les autres commits sans perte


>git reste –hard        
supprile le commit avec les fichiers (dangereux)


>git checkout "numéro de log"'
remet un fichier dans son état avant le numéro de log concerné 


>git revert
Annule un comit et ajoute un commit d'annulation 








