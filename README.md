# repo-tp-1

# TP Git avec VLADIMIR – Repo TP 1

##Objectif du TP
Ce projet a pour objectif de découvrir et pratiquer les bases de Git et GitHub en utilisant la ligne de commande et VS Code.

## Prérequis
- Git installé
- Un compte GitHub
- VS Code installé


## Installation de Git


# Télécharger Git depuis le site officiel
https://git-scm.com/downloads
executer le .exe

#Commandes utilisées 
git init	Initialise un dépôt Git local
git status	Affiche l’état des fichiers
git add .	Ajoute tous les fichiers à l’index
git commit -m "msg"	Crée un commit
git branch	Liste les branches
git switch -c develop	Crée et change de branche
git merge develop	Fusionne develop dans main
git remote add origin	Lie le repo local à GitHub
git push -u origin main	Envoie le code sur GitHub
ssh -T git@github.com	Teste l’authentification SSH

#Workflow
main : branche stable (production)
develop : branche de développement
Une modification est faite sur la branch develop , elle est envoyée vers GITHUB, puis, nous mergeons la branch main avec la branch develop 

```
main
 └── develop
```
