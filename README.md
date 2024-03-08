# Mon Application React

Ce projet est une application React basique faite pour être exécutée dans un environnement Docker pour le développement. 
Il inclut un hot reload pour le développement interactif.
Les modifications apportées aux fichiers dans le dossier /client/src sur votre machine hôte seront automatiquement répercutées dans le conteneur, permettant ainsi un développement interactif avec hot reload.

## Instructions
Pour lancer en mode "développement"
```bash
docker compose -f docker-compose.dev.yml up --build 
