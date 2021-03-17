Programmation Java @ Et3
<br>
Polytech Paris-Saclay | 2020-21

___

Voici un petit tutoriel pour mettre en place un projet Github sur Eclipse ou IntelliJ. Je précise qu'ici, l'ordinateur est configuré en anglais, donc bien évidemment, les commandes seront peut-être en français pour certains d'entre vous.

# Comment utiliser Git avec Eclipse ?

1. Connectez-vous à GitHub et rendez-vous sur la page de vos répertoires.

> <br><div align="center"><img src="images/eclipse_step1.jpg"></img></div><br>

2. Ajoutez un nouveau répertoire

> <br><div align="center"><img src="images/eclipse_step2.jpg"></img></div><br>

2bis. Créez un nouveau répertoire

> <br><div align="center"><img src="images/eclipse_step2bis.jpg"></img></div><br>

2ter. Vous devriez arriver sur la page du répertoire créé

> <br><div align="center"><img src="images/eclipse_step2ter.jpg"></img></div><br>

3. Dans Eclipse, créez un nouveau projet Java

> <br><div align="center"><img src="images/eclipse_step3.jpg"></img></div><br>

3bis. Nommez-le et validez

> <br><div align="center"><img src="images/eclipse_step3bis.jpg"></img></div><br>

3ter. Ne créez pas de module

> <br><div align="center"><img src="images/eclipse_step3ter.jpg"></img></div><br>

4. Ouvrez le nouveau projet dans l'explorateur Système

> <br><div align="center"><img src="images/eclipse_step4.jpg"></img></div><br>

5. Ouvrez le répertoire

> <br><div align="center"><img src="images/eclipse_step5.jpg"></img></div><br>

6. Ouvrez Git Bash dans ce répertoire (clic droit -> Git Bash Here)

> <br><div align="center"><img src="images/eclipse_step6.jpg"></img></div><br>

7. Entrez la première commande indiquée sur la page de votre répertoire GitHub :

> ```
> echo "# TPNoteIHM" >> README.md
> ```
> 
> Cela devrait créer un fichier README.md
> 
> <br><div align="center"><img src="images/eclipse_step7.jpg"></img></div><br>

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
> <br><div align="center"><img src="images/eclipse_step7bis.jpg"></img></div><br>

8. Actualisez la page de votre répertoire GitHub

> <br><div align="center"><img src="images/eclipse_step8.jpg"></img></div><br>

8bis. Vous devriez voir votre fichier README.md apparaître

> <br><div align="center"><img src="images/eclipse_step8bis.jpg"></img></div><br>

9. Dans Eclipse, faites un clic droit sur le projet et sélectionnez "Share Project ..."

> <br><div align="center"><img src="images/eclipse_step9.jpg"></img></div><br>

9bis. L'IDE devrait automatiquement reconnaître le répertoire .git, vous pouvez donc valider

> <br><div align="center"><img src="images/eclipse_step9bis.jpg"></img></div><br>

9ter. Vous devriez voir apparaître le nom du répertoire GitHub ainsi que la branche (master)

> <br><div align="center"><img src="images/eclipse_step9ter.jpg"></img></div><br>

10. Ouvrez le fichier .gitignore

> <br><div align="center"><img src="images/eclipse_step10.jpg"></img></div><br>

10bis. Assurez-vous que le répertoire de compilation y figure (bonne pratique : on évite au maximum de mettre du code compilé sur une plateforme de versioning ;))

> <br><div align="center"><img src="images/eclipse_step10bis.jpg"></img></div><br>

11. Créez les éléments de votre projet sur Eclipse (ici, une classe)

> <br><div align="center"><img src="images/eclipse_step11.jpg"></img></div><br>

12. "Commitez" votre projet (clic droit -> Team -> Commit)

> Vous utiliserez principalement deux commandes :
> - Commit & Push, pour envoyer vos éléments vers le répertoire GitHub
> - Pull pour mettre à jour la version du projet se trouvant sur votre ordinateur
> 
> <br><div align="center"><img src="images/eclipse_step12.jpg"></img></div><br>

13. Déplacez les éléments à "commiter" depuis "Unstaged changes" jusque "Staged changes"

> <br><div align="center"><img src="images/eclipse_step13.jpg" ></img></div><br>

13bis. Entrez un message pour votre commit, puis "poussez" vos changements vers votre répertoire GitHub en cliquant sur "Commit and Push ..."

> <br><div align="center"><img src="images/eclipse_step13bis.jpg"></img></div><br>

13ter. Vous pouvez fermer la fenêtre informative qui s'affiche

> <br><div align="center"><img src="images/eclipse_step13ter.jpg"></img></div><br>

14. En actualisant la page de votre répertoire, vous devriez trouver votre projet :trophy: :trophy: :trophy:

> <br><div align="center"><img src="images/eclipse_step14.jpg"></img></div><br>


# Comment utiliser Git avec IntelliJ ?

1. Connectez-vous à GitHub et rendez-vous sur la page de vos répertoires.

> <br><div align="center"><img src="images/intellij_step1.jpg"></img></div><br>

2. Ajoutez un nouveau répertoire

> <br><div align="center"><img src="images/intellij_step2.jpg"></img></div><br>

2bis. Créez un nouveau répertoire

> <br><div align="center"><img src="images/intellij_step2bis.jpg"></img></div><br>

2ter. Vous devriez arriver sur la page du répertoire créé

> <br><div align="center"><img src="images/intellij_step2ter.jpg"></img></div><br>

3. Dans IntelliJ, créez un nouveau projet Java

> <br><div align="center"><img src="images/intellij_step3.jpg"></img></div><br>
> <br><div align="center"><img src="images/intellij_step3bis.jpg"></img></div><br>
> <br><div align="center"><img src="images/intellij_step3ter.jpg"></img></div><br>

3bis. Nommez-le et validez

> <br><div align="center"><img src="images/intellij_step3quater.jpg"></img></div><br>

4. Ouvrez le nouveau projet dans l'explorateur Système

> <br><div align="center"><img src="images/intellij_step4.jpg"></img></div><br>

5. Ouvrez le répertoire

> <br><div align="center"><img src="images/intellij_step5.jpg"></img></div><br>

6. Ouvrez Git Bash dans ce répertoire (clic droit -> Git Bash Here)

> <br><div align="center"><img src="images/intellij_step6.jpg"></img></div><br>

7. Entrez la première commande indiquée sur la page de votre répertoire GitHub :

> ```
> echo "# TPNoteIHM" >> README.md
> ```
> 
> Cela devrait créer un fichier README.md
> 
> <div align="center"><img src="images/intellij_step7.jpg"></img></div><br>


7bis. Entrez la deuxième commande indiquée sur la page de votre répertoire GitHub :

> ```
> git init
> ```
> 
> Cela devrait créer un répertoire ".git"
> 
> <div align="center"><img src="images/intellij_step7bis.jpg"></img></div><br>

7ter. Entrez les autres commandes indiquées sur la page de votre répertoire GitHub 

> Dans mon cas :
> 
> ```
> git add README.md
> git commit -m "first commit"
> git branch -M main
> git remote add origin https://github.com/EugenieBrasier/TPNoteIHM.git
> git push -u origin main
> ```
> 
> Vous pourriez avoir besoin d'entrer vos identifiants GitHub
> 
> <div align="center"><img src="images/intellij_step7ter.jpg"></img></div><br>

8. Actualisez la page de votre répertoire GitHub. Vous devriez voir votre fichier README.md apparaître

> <br><div align="center"><img src="images/intellij_step8.jpg"></img></div><br>

9. Dans le répertoire du projet, ajoutez un nouveau fichier texte

> <br><div align="center"><img src="images/intellij_step9.jpg"></img></div><br>

9bis. Renommez ce fichier en ".gitignore"

> <br><div align="center"><img src="images/intellij_step9bis.jpg"></img></div><br>

9ter. Ajoutez-y le répertoire de compilation (bonne pratique : on évite au maximum de mettre du code compilé sur une plateforme de versioning ;))

> <br><div align="center"><img src="images/intellij_step9ter.jpg"></img></div><br>
10. Créez les éléments de votre projet sur Eclipse (ici, une classe)

> <br><div align="center"><img src="images/intellij_step10.jpg"></img></div><br>

10bis. Nommez-la et validez

> <br><div align="center"><img src="images/intellij_step10bis.jpg"></img></div><br>

10ter. Ajoutez du contenu à votre classe

> <br><div align="center"><img src="images/intellij_step10ter.jpg"></img></div><br>

11. L'IDE devrait automatiquement reconnaître le répertoire .git. "Commitez" votre projet (clic droit -> Git -> Commit Directory ...)

> Vous utiliserez principalement deux commandes :
> - Commit & Push, pour envoyer vos éléments vers le répertoire GitHub
> - Pull pour mettre à jour la version du projet se trouvant sur votre ordinateur
> 
> <br><div align="center"><img src="images/intellij_step11.jpg" ></img></div><br>

11bis. Selectionnez les changements à "commiter", ajoutez un message de "commit" explicite et cliquez sur "Commit and Push ..."

> <br><div align="center"><img src="images/intellij_step11bis.jpg" ></img></div><br>

11ter. Une fenêtre de preview s'ouvrira. Vous pouvez alors valider l'envoi en cliquant sur "Push"

> <br><div align="center"><img src="images/intellij_step11ter.jpg" ></img></div><br>

12. Une fenêtre vous demandant d'entrer vos identifiants pourrait s'ouvrir, cliquez alors sur "Log In in Github ..."

> <br><div align="center"><img src="images/intellij_step12.jpg" ></img></div><br>

12bis. Vous serez alors redirigés vers une page web. Cliquez sur "Authorize in Github"

> <br><div align="center"><img src="images/intellij_step12bis.jpg"></img></div><br>

12ter. Puis, validez l'autorisation en cliquant sur "Authorize JetBrains"

> <br><div align="center"><img src="images/intellij_step12ter.jpg"></img></div><br>

13. Actualisez la page de votre répertoire Github. Vous devriez trouver votre projet :trophy: :trophy: :trophy:

> <br><div align="center"><img src="images/intellij_step13.jpg"></img></div><br>

___

D'autres techniques, peuvent être utilisées (e.g. [Eclipse](https://openclassrooms.com/fr/courses/6106191-installez-votre-environnement-de-developpement-java-avec-eclipse/6250116-utilisez-eclipse-pour-envoyer-des-corrections-sur-github), [IntelliJ](https://www.jetbrains.com/help/idea/set-up-a-git-repository.html#put-existing-project-under-Git))
