# Answers of Bastien Micheloud bastienmicheloud

## Basics

### Task 1

Il y a le  fichier answer.md qui est le fichier contenant les réponses des différentes tâches. Il y a ensuite un dossier img qui contient l'image du graph git utilisée dans le fichier answer.md. Il y a le dossier .git qui contient tous les dossier et fichiers liés au fonctionnement de git. C'est à dire les informations requises pour notre référentiel distant, le contrôle des versions, les validations ...

### Task 2

Pour le git status, il indique que nous sommes toujours sur la branche main. Mais il détecte qu'il y a un fichier non-suivi : le fichier README.md venant d'être créé. Il indique que rien n'a été ajouté au commit, mais qu'il y a un fichier non-suivi (il propose de l'ajouter en faisant "git add")

Pour le git log oneline, rien n'a changé. Le hash du commit n'a pas changé, le commit actuel (HEAD) est toujours sur la branche main. Le dernier commit est l'initial commit.

Le git log oneline n'a pas changé car nous n'avons pas fait de commit depuis le commit initial et le status indique le nouveau status puisque nous avons ajouté un nouveau fichier et que nous ne l'avons pas encore add.

### Task 3

Le git status indique que nous sommes toujours sur la branche main. Il indique désormais que le fichier README est add, mais il n'est pas encore commit. Il indique aussi que le fichier answer.md n'est pas suivi, car nous ne l'avons pas add.

### Task 4

Le git status indique que le fichier README.md  a été modifié. Les 2 fichiers (README.md et answers.md) ne sont pas stage, il faudra donc les add les 2 pour ensuite pouvoir les commit.

### Task 5

Cette ligne envoie les informations des différents commits. La première chaîne de caractère est le hash du commit, c'est un identifiant unique pour chaque commit. HEAD est un pointeur qui indique le commit actuellement checkout, il pointe vers l'endroit du repo où le commit doit être effectué. Main est le nom de la branche principale de notre repo Git. Cela signifie que le commit actuel est sur Main. Et finalement après les parenthèses, on a le texte du commit.

### Task 6

Les fichiers sont revenus comme lors de l'initial commit quand on a checkout sur l'initial. Et ils sont revenus comme on était quand on a checkout sur le dernier commit.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)

1. develop : nom de la branche. C'est une branche distincte de main.

2. Hash du commit : L'identifiant du commit

3. Message du merge : Indique que la branche feature-auth à été  fusionnée avec develop

4. Auteur du commit : C'est ByteMe Bob qui a effectué le merge.

5. Dernière version du main, version actuelle du main

6. Megre de feature-auth avec develop

7. Checkout de feature-auth depuis main

8. Merge de la branche develop avec main

9. Checout de la branche develop depuis main

10. Initial commit