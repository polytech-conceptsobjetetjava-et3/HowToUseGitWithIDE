Programmation Java @ Et3
<br>
Polytech Paris-Saclay | 2020-21

___

Voici un petit tutoriel pour mettre en place un projet Github sur Eclipse. Je précise qu'ici, l'ordinateur est configuré en anglais, donc bien évidemment, les commandes seront peut-être en français pour certains d'entre vous.

# Comment utiliser Git avec Eclipse ?

1. Connectez-vous à GitHub et rendez-vous sur la page de vos répertoires.

> <br><div align="center"><img src="images/step1.jpg"></img></div><br>

2. Ajoutez un nouveau répertoire

> <br><div align="center"><img src="images/step2.jpg"></img></div><br>

2bis. Créez un nouveau répertoire

> <br><div align="center"><img src="images/step2bis.jpg"></img></div><br>

2ter. Vous devriez arriver sur la page du répertoire créé

> <br><div align="center"><img src="images/step2ter.jpg"></img></div><br>

3. Dans Eclipse, créez un nouveau projet Java

> <br><div align="center"><img src="images/step3.jpg"></img></div><br>

3bis. Nommez-le et validez

> <br><div align="center"><img src="images/step3bis.jpg"></img></div><br>

3ter. Ne créez pas de module

> <br><div align="center"><img src="images/step3ter.jpg"></img></div><br>

4. Ouvrez le nouveau projet dans l'explorateur Système

> <br><div align="center"><img src="images/step4.jpg"></img></div><br>

5. Ouvrez le répertoire

> <br><div align="center"><img src="images/step5.jpg"></img></div><br>

6. Ouvrez Git Bash dans ce répertoire (clic droit -> Git Bash Here)

> <br><div align="center"><img src="images/step6.jpg"></img></div><br>

7. Entrez la première commande indiquée sur la page de votre répertoire GitHub :

> ```
> echo "# TPNoteIHM" >> README.md
> ```
> 
> Cela devrait créer un fichier README.md
> 
> <br><div align="center"><img src="images/step7.jpg"></img></div><br>

7bis. Entrez les autres commandes indiquées sur la page de votre répertoire GitHub 

> Dans mon cas :
> 
> ```
> git init
> git add README.md
> git commit -m "first commit"
> git remote add origin https://github.com/EugenieBrasier/TPNoteIHM.git
> git push -u origin master
> ```
> 
> Vous pourriez avoir besoin d'entrer vos identifiants GitHub
> 
> <br><div align="center"><img src="images/step7bis.jpg"></img></div><br>

8. Actualisez la page de votre répertoire GitHub

> <br><div align="center"><img src="images/step8.jpg"></img></div><br>

8bis. Vous devriez voir votre fichier README.md apparaître

> <br><div align="center"><img src="images/step8bis.jpg"></img></div><br>

9. Dans Eclipse, faites un clic droit sur le projet et sélectionnez "Share Project ..."

> <br><div align="center"><img src="images/step9.jpg"></img></div><br>

9bis. L'IDE devrait automatiquement reconnaître le répertoire .git, vous pouvez donc valider

> <br><div align="center"><img src="images/step9bis.jpg"></img></div><br>

9ter. Vous devriez voir apparaître le nom du répertoire GitHub ainsi que la branche (master)

> <br><div align="center"><img src="images/step9ter.jpg"></img></div><br>

10. Ouvrez le fichier .gitignore

> <br><div align="center"><img src="images/step10.jpg"></img></div><br>

10bis. Assurez-vous que le répertoire de compilation y figure (bonne pratique : on évite au maximum de mettre du code compilé sur une plateforme de versioning ;))

> <br><div align="center"><img src="images/step10bis.jpg"></img></div><br>

11. Créez les éléments de votre projet sur Eclipse (ici, une classe)

> <br><div align="center"><img src="images/step11.jpg"></img></div><br>

12. "Commitez" votre projet (clic droit -> Team -> Commit)

> Vous utiliserez principalement deux commandes :
> - Commit & Push, pour envoyer vos éléments vers le répertoire GitHub
> - Pull pour mettre à jour la version du projet se trouvant sur votre ordinateur
> 
> <br><div align="center"><img src="images/step12.jpg"></img></div><br>

13. Déplacez les éléments à "commiter" depuis "Unstaged changes" jusque "Staged changes"

> <br><div align="center"><img src="images/step13.jpg" ></img></div><br>

13bis. Entrez un message pour votre commit, puis "poussez" vos changements vers votre répertoire GitHub en cliquant sur "Commit and Push ..."

> <br><div align="center"><img src="images/step13bis.jpg"></img></div><br>

13ter. Vous pouvez fermer la fenêtre informative qui s'affiche

> <br><div align="center"><img src="images/step13ter.jpg"></img></div><br>

14. En actualisant la page de votre répertoire, vous devriez trouver votre projet :trophy: :trophy: :trophy:

> <br><div align="center"><img src="images/step14.jpg"></img></div><br>

___

D'autres techniques, peuvent être utilisées (e.g. [OpenClassrooms](https://openclassrooms.com/fr/courses/6106191-installez-votre-environnement-de-developpement-java-avec-eclipse/6250116-utilisez-eclipse-pour-envoyer-des-corrections-sur-github)
