![Git Logo](https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png)
# DemoGit

## Liens utiles
**Documentation Git : ** https://git-scm.com/doc

**GitHub : ** https://github.com/

**Commandes Git de base**

1. `init` Initialise un dépot git dans le dossier courant
2. `config --global user.name "Mon nom"` Permet de configurer le nom d'utilisateur pour le dépot
3. `config --global user.email "monadresse@email.com"` Permet de configurer l'adresse email pour le dépot
4. `add nomdufichier` Ajoute le fichier *nomdufichier* à l'index
5. `commit -m "mon message commit"` Permet de commit une modification sur le dépot
6. `status` Affiche le statut du dépot (si il y'a un commit en attente)
7. `branch nomdelabranche` Crée la branche spécifiée
8. `checkout nomdelabranche` Se déplace sur la branche *nomdelabranche*
9. `merge nomdelabranche` Fusionne les modifications de la branche *nomdelabranche* sur celle en cours (master)
10. `remote add origin https://github.com/puertasg/tp1-formation.git
` Ajoute le dépot *tp1-formation* appartenant à *puertasg*
11. `pull origin master` Récupère la branche master sur le dépot distant
12. `push` Met à jour le dépot distant grâce aux modifications faites sur le local
13. `clone` Clone un dépot dans un nouveau dossier
14. `log` Liste les commit effectués sur le dépot
