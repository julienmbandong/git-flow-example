# git-flow-example
1- La commande 'git flow init' a permit d'initailier le repo.
2- La commande 'git flow feature start feature_branch' -> création d'une nouvelle branche feature feature_branch à partir de sa branche parente 'develop'  pour démarrer une nouvelle fonctionnalité.
3- Lorsque la fonctionnalité de la branche 'feature_branch' est finie, il faut exécuter la commande 'git flow feature finish feature_branch pour terminier la branche de fonctionnalité. En d autres termes, c'est un merge vers la branche local\develop'.
4- Exécuter les commandes habituelles de git notamment 'git add [filename...]', la commande 'git commit -m message', la commande 'git push -u origin develop'.
5- Creation de la branche release -> livraison 'git flow release start 0.1.0', mise à jour de la branche. Si l'organisation met l'accent sur la revue de code, cette étape est propice à la création d'une pull request.
6- Pour terminer une branche release, la commande 'git flow release finish 0.1.0'.
7- Creation de la branche hotfix (gestion de bug sur la branche main) à partir de main -> commande 'git flow hotfix start hotfix_branch'.