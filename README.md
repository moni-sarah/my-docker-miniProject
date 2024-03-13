# My-docker-miniProject

#  Docker Infrastructure 

## Objectives
Les objectifs de ce projet pratique sont de démontrer la gestion d'une infrastructure Docker, notamment l'amélioration d'un processus de déploiement d'applications existant, la gestion des versions de l'infrastructure et la mise en œuvre des meilleures pratiques pour l'infrastructure Docker.

## Infrastructure
- **Système d'exploitation :** CentOS 7.6
- **Environnement :** Docker installé sur une seule machine ou une machine virtuelle.
- **Sécurité :** Le pare-feu et autres mécanismes de sécurité ne doivent pas être désactivés sans justification.

## Application
L'application, nommée « student_list », est composée de deux modules :
1. **API REST** : fournit une liste d'étudiants avec leur âge basée sur un fichier JSON.
2. **Web App** : permet aux utilisateurs finaux d'accéder à la liste des étudiants.

## Fichiers fournis
- **Dockerfile** : utilisé pour créer les images de l'API et de l'application Web.
- **docker-compose.yml** : définit les services et leurs configurations pour le déploiement.
- **requirements.txt** : contient les packages Python requis pour l'API.
- **student_age.json** : fichier JSON contenant les noms et âges des étudiants.
- **student_age.py** : Code source de l'API en Python.
- **index.php** : page PHP permettant aux utilisateurs finaux d'interagir avec le service.

## Instructions
1. Assurez-vous que Docker est installé sur la machine CentOS 7.6 ou la machine virtuelle.
2. Clonez le référentiel contenant le code source de l'application.
3. Accédez au répertoire contenant le Dockerfile et docker-compose.yml.
4. Créez les images Docker à l'aide de « docker-compose build ».
5. Déployez l'application à l'aide de `docker-compose up`.
6. Accédez à l'application Web via un navigateur Web à l'adresse « http://localhost ».


