Automatisation de Création d'Infrastructure Azure

Ce projet utilise Jenkins et Azure CLI pour automatiser la création d'une infrastructure Azure.

Pipeline Jenkins

Le fichier Jenkinsfile définit un pipeline avec deux étapes :

  - Création du Groupe de Ressources Azure : Crée un groupe de ressources dans la région "northeurope".

  - Création de la Machine Virtuelle Azure : Crée une machine virtuelle dans le groupe de ressources avec l'image Ubuntu LTS et des disques de données.
