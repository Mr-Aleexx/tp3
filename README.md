**Nom :** Hazet Alex

**Groupe :** Equipe 01

**Année :** 2025

**IUT Le Havre - Cours GIT**

# Compte-rendu TP3 Introduction GIT



## 1. Inviter des collaborateurs dans un dépôt personnel


Pour cette exercice, Je serais Porthos et Liam sera Porthos.

- J'ai modifié les fichiers du TP2. Et synchronisé le dépôt distant avec mon dépôt local.
- J'ai fais la commande *git pull*.
- Les dépôts sont synchroniser de son côté comme du miens.

- Il a créernouveau repositoire.
- Je l'ai partagée avec Athos.
- On a chacun cloner le projet


## 2. Développement d'un projet java en équipe


Mes dépôt et les siens étaient synchroniser. On a chacun copiez les fichiers donné. On les as 
synchroniser avec le dépôt distant. Chacun de nous à compléter sa partie. Alex a mis sa version sur 
le dépôt distant, je l'ai récupérer. J'ai compilé et le test afficher le résultat voulu. Ensuite j'ai 
mis l'ensemble des fichiers sur le dépôt distant et Alex les as récupérer.


## 3. Gérer des nouvelles fonctionnalités à l’aide des branches


### 3.1 Tester le concept de branche avec un exemple simple

Lorsque j'ai fais *git branch*, j'ai vu que j'étais dans le main.

La commande *git log --graph --oneline --all --decorate --topo-order* permet de voir les modifications.

La commande *git checkout -b test* nous a fait crée une nouvelle branch et s'y rendre.

En faisant *git branch* j'ai vu que j'étais dans la branch test.

Pour changer de branch, il faut faire la commande *git checkout `Nom de la branche`*.

Etant sur Windows, j'ai utliser la commande *New-Item test.txt -ItemType File* pour crée le fichier.

J'ai validé les changements du dépôt local. Quand je suis retounée sur la branch main, je ne voyais 
plus la branch test. En faisant *git log --graph --oneline --all --decorate --topo-order*. J'ai 
vu qu'une fourcette a été produite.

On se retrouve avec une branch principal (main), et une branch secondaire (test).

### 3.2. Fusionner la branche de test dans la branche principale

On va dans la branch principal avec *git checkout main*.

Pour fusionner deux branch il faut faire *git merge `Nom de la branch qu'il faut fusionner`*.
Cette commande va fusionner la branch passer en paramètre avec la branch où on se trouve.

Après avoir fusionner, si on fait *ls*, on voit que le contenue de la branch fusionner est 
apparût au niveau où on se trouve.

J'ai crée *PorthosCoin.java* et Liam a crée *AthosCoin.java*. Nous avons chacun fusionner la branch 
crée avec notre branch main chacun de notre côté. Alex a *push* ses fichiers, j'ai ensuite *pull* pour 
récupérer ses fichiers, j'ai *commit*, puis *push* mes fichiers sur le dépôt distant.

Désormais, les dépôt local et distant sont synchroniser.