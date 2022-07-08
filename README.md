
##  Création d'un API RESTful en Node.js (avec Express.js)

Il s'agit d'un projet d'imitation d'API ensuite adapté à la fédération togolaie de football pour en faire le leur afin de pouvoir traiter les informations des joueurs par différentes méthodes. Ce projet à été fait sans base de données, juste la modelisation et le controleur qui ont été mis en avant. Le projet après s'être realisé a été hebergé sur Heroku et envoyé sur github.

##  Le liens vers le repos github 

*  https://github.com/Massahgenesis/API_FTF


##  Installation des outils necessaires pour la création de l'API
                (les outils utilisés)
                
    ### Nodes.js
    ### Installation npm – Node Package Manager
    ### Nvm – Node Version Manager
    ### Le terminal pour l'execution des commandes necessaires
    ### Postman (pour tester l'API)
    ### Heroku (pour l'hebergement du site)
     
     Tous ces outils ont permis de mettre en place un environnement favorable afin de rendre      effectif le projet.
     
     
    ## Les Fonctionnalités de l'API et tes tavec les différentes methodes
    
    ### GET method
    
    Cette methode est utilisée pour chercher les information du jour à partir de l'identifiant
    
    <img width="726" alt="get:heroku" src="https://user-images.githubusercontent.com/102354727/177833372-840d0412-0b1f-4bd5-a793-d6cd5f42018d.png">
    
    
    ### POST method
    
    cette methode permet de creation de nouvelles données pour un joueur
    
<img width="688" alt="post" src="https://user-images.githubusercontent.com/102354727/177834479-9e970adb-8b4c-4a20-b34b-8a8051f7c660.png">


### PUT method

cette methode consiste à modifier les données d'un joueur

<img width="694" alt="put:heroku" src="https://user-images.githubusercontent.com/102354727/177834749-975edf17-3fcd-4cab-94f9-5af191e41ac2.png">


### DELETE method

cette methode permet de supprimer les données d'un joueur.

<img width="1067" alt="Capture d’écran 2022-07-08 à 08 13 10" src="https://user-images.githubusercontent.com/102354727/177950508-964051d5-c982-4856-a64a-6f0e8f5c5ad6.png">



##LE SCRIPT

Les package npm venus avec intallation du npm install de l'api immité et des fichiers crées dans lequels on met un script ou on ajoute ou modifie selon ce que l'on veut de l'API et du fichier dans lequel l'on se trouve.

GET,POST,PUT et DELETE, toutes ces requetes se font sous un certains nombres de conditions intégrées au code. Ces conditions sont entre autres le nom affichage des informations démandées avec un message en retour signalant la source du probleme.
en exemple cette image:

<img width="774" alt="get_local:error" src="https://user-images.githubusercontent.com/102354727/177837786-7d63ad47-e5bc-490c-b2bb-61a485eba835.png">

Aussi une requete bien faite qui aboutit les codes de convention s'affichent pour effectivement confirmer l'effectivité de la requete.



