Exercice pipeline
=================

## Démarche

J'ai créé un nouveau fichier **devops-pipeline.yaml** dans le dossier `.github/workflows` afin de lancer un **scan IaC** avec **Checkov**, un **scan de vulnérabilité** avec **Trivy**, ainsi qu'une analyse **SonarCloud** (et non pas **Sonarqube**, car c'est bien plus simple et léger à utiliser).

##