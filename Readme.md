# SitePeinture
Site web qui présente des peintures  (Symphony) 
# Etapes:
1- model de donnée 
2- mise en place du projet Symfony
   * création du projet Symphony 5 
   * dépot github 
3- Intégration Continue github 
   * création du dossier .github/workflows
   * fichier github-ci.yml : ci-image-docker, ci-php, ci-Symfony 

4- environement de développement avec Docker et Symfony server
    docker , docker-compose
    symfony CLI, PHP 7.4.9

    * base de donnée avec docker:
    symfony console make:docker:database