# TP Git & GitHub - Gestion de Versions en Binôme

## 1. Présentation du Projet
Ce projet est réalisé dans le cadre du cours de développement en BTS SIO. 
L'objectif est de simuler un flux de travail collaboratif en utilisant Git (local) et GitHub. Dans ce projet j'ai repris un projet que j'avais déjà fait en local sans utiliser git puis copier les ligne de code pour simuler le workflow.

## 2. L'Équipe
* Étudiant A : Matisse sur pc perso(Gestion du dépôt distant et de la structure globale)
* Étudiant B : Matisse sur pc du lycée (gestion du style css ) 

## 3. Workflow utilisé
Nous avons suivi le workflow recommandé en entreprise:
1. Création de 4 branche spécifique pour chaque fonctionnalité.
* branch body
* branch css
* branch navbar
* branch footer
2. Développement et commits fréquents, les commits fréquents sont une garantie de sécurité pour ne jamais perdre de fichiers.
3. Publication des branche sur GitHub (`git push`).
4. Création d'une **Pull Request** pour revue de code.
5. Fusion (Merge) vers la branche principale `main`.

## 4. Gestion des Conflits 
Nous avons simulé et résolu un conflit sur le fichier `index.html`.
* Cause : Modification simultanée de la même ligne sur deux branches différentes `body` et `main`.
* Résolution : Utilisation des marques Git (`<<<<<<<`, `=======`) pour choisir la version finale, suivie d'un commit de résolution.

## 5. Livrables
* j'ai 13 commîtes effectué
* j'ai crée 4 branche 
* j'ai résolu un conflit
* j'ai un README.md explicatif

## 5. Commandes Principales Utilisées
* `git init` : c'est elle qui crée le dossier caché .git et commence la surveillance.
* `git status` : Vérifier l'état des fichiers.
* `git add .` : prépare les fichiers pour le commit.
* `git commit : prend une “photo” du projet.
* `git log --oneline` : Visualiser l'historique simplifié.
* `git pull` : Récupérer les mises à jour du binôme avant de travailler.
* `git push` : Envoyer les modifications sur le serveur distant.