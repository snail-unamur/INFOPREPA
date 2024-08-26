---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Bienvenu aux cours préparatoire d'informatique !
---

Vous trouverez sur ce site web tout le matériel nécessaire pour les différentes séances des cours, ainsi que quelques pointeurs vers d'autres resources utiles pour les études en informatique.

------------------------------------------------------------

## Partie 1 : Devenir un·e power user

### 1-1 C’est quoi l’informatique ?

**Activité *Turing Tumble* :** Vas sur la version en ligne de [Turing Tumble](https://tumble-together.herokuapp.com/) et essaye de résoudre les puzzles \#1, \#5 et \#11 : [https://tumble-together.herokuapp.com/](https://tumble-together.herokuapp.com/).

![Turing Tumble printscreen 1](img/turingtumble1.jpg)
![Turing Tumble printscreen 2](img/turingtumble2.jpg)

([documentation](https://upperstory.com/turingtumble/assets/educator-guide-2021.pdf))

**Activité *Binary Game* :** Vas sur [https://learningcontent.cisco.com/games/binary/index.html](https://learningcontent.cisco.com/games/binary/index.html) pour résoudre le plus de puzzles le plus vite possible avant que la pile de nouveaux puzzles ne déborde (on parle d'*overflow* en informatique ;-)).

![Binary Game printscreen](img/binarygame.jpg)

### 1-2 Utiliser l’ordinateur comme un·e power user

**Activité *Jeu de piste en ligne de commande* :**

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

**Resources supplémentaires** :

- [Bash scripting cheatsheet](https://devhints.io/bash)
- [Introduction au Script Bash (avec exemples)](https://www.hostinger.fr/tutoriels/introduction-au-script-bash-avec-exemples)

------------------------------------------------------------

## Partie 2 : Devenir un·e développeur·euse

### 2-1 Introduction à l’algorithmique

Lors de la dernière séance, nous avons vu avec vous les briques de base de la programmation. Ces briques apparaissent dans la plupart des langages de programmation ([impérative](https://fr.wikipedia.org/wiki/Programmation_impérative)) comme le Python ou le Java. Pour faciliter les choses, on te propose de sauvegarder la *cheat sheet* (*aide-mémoire* en français) suivante qui reprends les différents concepts (une [version .pdf est disponible ici](cheatsheet-bases-programmation.pdf)) :

![Cheat sheet reprenant les bases de la programmation](img/cheatsheet-bases-programmation.jpg)

**Exemple *Financement participatif* :** Cet exemple est utilisé dans le cours pour illustrer les différentes étapes de la conception d'un algorithme permettant d'automatiser une tâche donnée. Voici l'énoncé de l'exercice en français :

> Sur une plateforme de financement participatif, chaque utilisateur·trice décide librement d’un montant qu’il ou elle souhaite investir dans un projet qui lui tient à cœur. L’utilisateur·trice reçoit en retour certains avantages en fonction de la somme investie. Ces avantages sont cumulatifs : une personne qui investit 100€ a droit à recevoir au moins les même avantages qu’une personne qui investit 99€ ou moins.
>
> Dans le cadre d’une campagne pour lancer une nouvelle artiste, vous devez implémenter une suite d’instructions qui, à partir d’un montant donné, affiche les avantages octroyés suivants :
>  - à partir de 50€ : envoi d’un poster dédicacé (avantage 1);
>  - à partir de 500€ : possibilité de passer 30 minutes avec l’artiste (avantage 2);
>  - à partir de 5000€ : concert privé pour max. 20 personnes de votre choix (avantage 3).
>  - Si l’utilisateur·trice ne donne pas suffisamment pour avoir un avantage, il faut l’avertir.


**Activité *Bootstrapping your Python skills* :** Pour découvrir le langage Python, on te propose d'aller sur le [Jupyter Notebook créé par nos soins](https://colab.research.google.com/drive/15CcHpemDYJcn2KOhdoFAEEY-riRKAXQ2?usp=sharing). Les *notebooks* (ou *calepins* en français) sont des environnement de développement dédiés à l'apprentissage d'un langage de programmation. Ce calepin a été conçu pour découvrir les bases du langage Python.

Pour te faciliter la vie par la suite, voici une *cheat sheet* avec les briques de base de la programmation en Python (une [version .pdf est disponible ici](cheatsheet-bases-python.pdf)) :

![Cheat sheet reprenant les bases de la programmation en Python](img/cheatsheet-bases-python.jpg)

### 2-2 L'environnement de développement



## Autres resources utiles

- [Éduquer au numérique. 12 clés pour comprendre l'informatique](https://www.politeia.be/fr_BE/shop/18533-eduquer-au-numerique-12-cles-pour-comprendre-l-informatique-11619) (livre, aussi disponible en prêt à la [BUMP](https://www.unamur.be/fr/bump))
