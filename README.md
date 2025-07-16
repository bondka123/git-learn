Créer un dossier appelé learn_git.
mkdir learn_git
Cd (changer de répertoire) dans le dossier learn_git.
cd learn_git
Créer un fichier appelé third.txt.
touch third.txt
Initialiser un dépôt git vide.
git init
Ajouter third.txt à la staging area.
git commit -m "adding third.txt"
git add third.txt
Commiter avec le message "adding third.txt".
git commit -m "adding third.txt"
Vérifiez votre validation avec git log.
git log
Créez un autre fichier appelé fourth.txt.
touch fourth.txt
Ajoutez fourth.txt à la staging area.
git add fourth.txt
Vérifiez avec le message "adding fourth.txt"
git commit -m"adding fourth.txt"
Enlevez le fichier third.txt.
rm third.txt
Ajoutez cette modification à la staging area. (En utilisant la commande "git add ."
git add .
Commiter avec le message "removing third.txt".
git commit -m "removing third.txt"
Vérifiez vos commits en utilisant git log.
git log
Changez vos paramètres globaux pour core.pager=cat - vous pouvez en savoir plus ici.
git config --global core.pager cat


Écrivez la commande appropriée pour lister toutes les configurations globales pour git sur votre machine.
git log

Vous pouvez taper git config --global pour savoir comment faire.
git config --global --list
