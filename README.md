# GU3SS-NUMB3R

Le projet GU3SS-NUMB3R à pour but d'introduire le langage de programmation **Brainfuck** (que l'on remplacera par BF par souci de simplicité) en codant un jeu du type "Guess number", où il faudra deviner un nombre généré aléatoirement avec des indications "il est trop grand", "il est trop petit"

Pour rendre le code plus lisible le code, il sera commenté avec des "//" qui indiqueront qu'il s'agira d'un commentaire.
A noter que tout les commentaires ne contiendront pas les caractères non-inclus dans la table ASCII 8-bits et les 8 caractères nécéssaires au BF (.,<>-+[])
De plus le '+' (opérateur d'addition) sera remplacé par '&', le '-' (opérateur de sosutraction) sera remplacé par '\_', le reste des caractères seront indiqué entre crochets, par exemple pour '[' on écriras {crochet_ouvrant} 

A partir de **input** les cases auront une utilité spécifique:
- case 1: pointeur pour les boucles
- case 2: pointeur des lettres majuscules
- case 3: pointeur des lettres minuscules
- case 4: pointeur pour les caractères de tabulation
- case 5: pointeur pour les chiffres et symboles

![erreur lors du chargement de l'image](https://raw.githubusercontent.com/L4KK4S/GU3SS-NUMB3R/main/.img/schema_pointeurs.png)


### Introduction
- **print** : Ce programme permet d'expérimenter les bases pour afficher des caractères [ici](https://github.com/L4KK4S/GU3SS-NUMB3R/blob/main/print.b)

### Outils & liens utiles

**Code Ascii 8-bits avec les caractères asociés**
![erreur lors du chargement de l'image](https://raw.githubusercontent.com/L4KK4S/GU3SS-NUMB3R/main/.img/ascii_8_bits_table.png)

**Liens**
* [**Compileur brut**](https://www.tutorialspoint.com/execute_brainfk_online.php)
* [**Visualiseur**](https://ashupk.github.io/Brainfuck/brainfuck-visualizer-master/index.html#)
