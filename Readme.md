# SitePeinture
Site web qui présente des peintures  (Symphony) 
<<<<<<< HEAD

## Environement  de Developpement 

## Pré-requis
* PHP PHP 7.4.9
* docker
* composer
* docker-compose
* Symfony CLI

* Symfony require
'''bash
symfony check:requirements
'''

# Etapes:
* 1- model de donnée 
* 2- mise en place du projet Symfony
   * création du projet Symphony 5 
   symfony new projectName --full
   * dépot github 
* 3- Intégration Continue github 
   * création du dossier .github/workflows
   * fichier github-ci.yml : ci-image-docker, ci-php, ci-Symfony 

* 4- environement de développement avec Docker et Symfony server
    docker , docker-compose
    symfony CLI, PHP 7.4.9

   * base de donnée avec docker:
    - dockeriser la base de donnée 
    symfony console make:docker:database
    - creer les conteneurs mailer et databse(mysql)
'''bash
docker-compose up -d
'''
    - lancer le server symfony 
'''bash
    symfony serve -d 
'''
=======
Etapes:
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
>>>>>>> 03de74d60c6cd5ae73265a167c116a56d5d8c898
