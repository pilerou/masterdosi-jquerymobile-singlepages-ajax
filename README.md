Cet exercice vise à réaliser l'architecture suivante :
![Cinématique d'écrans](/schema_architecture.PNG)

Un projet de base est fourni et présente des commentaires avec des TODO précisant les améliorations à apporter.

Ce projet rentre dans le cadre de le cadre du cours sur les solutions mobiles du Master DOSI de l'Université de Bretagne Occidentale.
 
Pré-requis
----------------
### Disposer d'un serveur http

Disposer d'un serveur http local pour desservir les sources.
En ouvrant les fichiers en local, les navigateurs tels que Chrome considèreront les liens comme des failles Cross Origin.
Si vous ne disposez pas de serveur http sur votre poste mais que vous disposez de Node JS, effectuez les opérations suivantes :
`npm install http-server -g`

Vous disposerez alors de la possibilité de lancer un serveur http en prenant pour base le répertoire dans lequel vous vous trouvez en tapant simplement :
`http-server`

### Avoir lancé le service Node JS helloworld en local
Le service et sa procédure d'installation sont disponibles ici :
https://github.com/pilerou/masterdosi-helloworld-nodejs

Installation des sources
----------------
Téléchargez le projet en local et dézippez-le [Zip du projet](https://github.com/pilerou/masterdosi-jquerymobile-singlepages-ajax/archive/master.zip)

Votre répertoire de travail est le répertoire `base`

Ouvrez une console et tapez 
`cd [chemin]/base` où chemin est le chemin dans lequel vous avez dézippé le projet
`http-server`

Votre serveur tourne normalement sur le port 8080 :
> Starting up http-server, serving ./ on port: 8080
 
Vérification de l'installation
----------------
Ouvrir votre navigateur. Appelez l'url : 
http://localhost:8080/accueil.html
LA page d'accueil s'affiche.

Développement
----------------
3 étapes sont à réaliser et sont mentionnées par des commentaires commençant par "TODO" :
- Etape 1 dans le fichier accueil.html, il convient d'ajouter un lien vers la page page_deux.html
- Etape 2 dans le fichier accueil.html, il convient d'ajouter une popup et de l'ouvrir lorsqu'on clique sur un lien
- Etape 3 dans le fichier page_trois.html, il convient d'effectuer le traitement pour appeler le serveur en Ajax

Correction
----------------
La correction est visible en suivant le lien : [Correction](https://github.com/pilerou/masterdosi-jquerymobile-singlepages-ajax/tree/master/correction)

