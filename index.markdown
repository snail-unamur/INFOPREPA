---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Bienvenu aux cours préparatoire d'informatique !
---

Vous trouverez sur ce site web tout le matériel nécessaire pour les différentes séances des cours, ainsi que quelques pointeurs vers d'autres resources utiles pour les études en informatique.

## Partie 1 : Devenir un·e power user

### 1-1 C’est quoi l’informatique ?

**Activité Turing Tumble** : Vas sur la version en ligne de [Turing Tumble](https://tumble-together.herokuapp.com/) et essaye de résoudre les puzzles \#1, \#5 et \#11 : [https://tumble-together.herokuapp.com/](https://tumble-together.herokuapp.com/).

![Turing Tumble printscreen 1](img/turingtumble1.jpg)![Turing Tumble printscreen 2](img/turingtumble2.jpg)

([documentation](https://upperstory.com/turingtumble/assets/educator-guide-2021.pdf))

**Activité Binary Game** : Vas sur [https://learningcontent.cisco.com/games/binary/index.html](https://learningcontent.cisco.com/games/binary/index.html) pour résoudre le plus de puzzles le plus vite possible avant que la pile de nouveaux puzzles ne déborde (on parle d'*overflow* en informatique ;-)).

![Binary Game printscreen](img/binarygame.jpg)

### 1-2 Utiliser l’ordinateur comme un·e power user

**Activité Jeu de piste en ligne de commande** :

Télécharge le fichier suivant [tresor_chateau.zip](tresor_chateau.zip) et dézipe le dans ton dossier utilisateur (`/home/tonidentifiant/`). Si tu veux le faire sans utiliser la souris, ouvre un terminal de commande et tape les commandes suivantes pour télécharger le fichier sur ta machine depuis le site web :
```bash
cd
wget https://snail-unamur.github.io/INFOPREPA/tresor_chateau.zip
```
La commande `ls` devrait normalement faire apparaître le fichier `tresor_chateau.zip` dans la liste des fichiers. Tu peux maintenant déziper le fichier à l'aide de la commande suivante :
```bash
unzip tresor_chateau.zip
```
La commande `ls` devrait maintenant faire apparaître le dossier `tresor_chateau`. Pour démarrer le jeu, rends toi dans ce dossier et lis le premier indice à l'aide des commandes suivantes :
```bash
cd tresor_chateau
cat panneau01.txt
```

*Pro tip : dans un terminal de commande, la [touche de tabulation](https://fr.wikipedia.org/wiki/Touche_de_tabulation) permet de compléter automatiquement la fin de la commande. Par exemple, `cd tres` + tabulation complétera la commande en `cd tresor_chateau`, pour autant qu'aucun autre dossier commençant par `tres` se trouve dans le répertoire courant.*

(adapté depuis [Le trésor du chateau: Jeu de piste en ligne de commande sous Linux](https://www.enseignons.be/preparation/86760/) de Cédric Libert)

## Partie 2 : Devenir un·e développeur·euse

### 2-1 La programmation et ses paradigmes


### 2-2 Introduction à l’algorithmique


## Autres resources utiles

- [Éduquer au numérique. 12 clés pour comprendre l'informatique](https://www.politeia.be/fr_BE/shop/18533-eduquer-au-numerique-12-cles-pour-comprendre-l-informatique-11619) (livre)
 

