
# commandes git

git init : créer un dépot g it
git commit -m " " xxx : enregistrer des changements, le -m " " sert à montrer le changement effectué (il ne peut pas y avoir de vide entre les " " ) et le xxx sert à mettre le nom du fichier modifié si il y en a que un seul, sinon on peut laisser vide
git merge xxx : permet de fusionner les branches, il faut être sur la branche de destination avant de faire le merge et marquer quelle branche on veut fusonner avec l'actuelle
git branch -a : permet d'afficher toutes les branches même les cachées
git branch : permet d'afficher les branchees visibles
git branch abc : permet de créer la brancche abc
git checkout abc : permet d'aller sur la branche abc
git clone + lien ssh : permet de cloner le repertoire git sur l'ordinateur (il faut être dans le dossier voulu avant de faire le git clone)
git add . : met tout le contenu du dossier actuel dans le répertoire de travail avant une validation
git push : exporte les branches locales vers les branches distantes

#autre commandes utile

cd x : permet de se déplacer dans le dossier x
cd .. : permet de se déplacer dans le dossier précédent
cd x/y : permet de se déplacer directement dans le dossier y qui se trouve dans le dossier x sans devoir faire 2 commandes différentes
touch xx.txt : permet de créer le fichier xx.txt
mkdir: permet de créer un nouveau dossier
nano xxx : permet d'ouvrir le fichier xxx avec un éditeur de texte (fonctionne aussi par exemple avec atom xxx)

#markdown

langage de balise léger permettant d'offrir un syntaxe facile à lire et à écrire, ce document peut être converti en html, pdf ou en d'autres formats

##petit tips

*xxx* ou _xxx_ permet de mettre le contenu entre * * et _ _ en italique (balise html <em>)
# h1
##  h2
### h3
####  h4
#####  h5
######  h6

liste à puce:
* pommes
* poires
    * compote

liste ordonnée:
1. un
2. deux
