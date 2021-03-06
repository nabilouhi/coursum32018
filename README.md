# coursum32018
support pour les étudiants de M1 et M2 Miashs à l'UM3 

**Notions de Master 1 - intégration de données connectées**

Le but de ce cours est de forger une première culture de ce qu'est le Web et la problématique de l'interopérabilité.
Les étudiants doivent réaliser un premier mashup uniquement en code client.

_Définitions :_

* Web ( http, URI, HTML ) : Le web c'est une application basée sur le réseau internet. Il permet d'échanger des informations via un protocole de communication ( http ) entre un client et un serveur. Les informations ( ou données ) sont représentées dans un format par exemple, originellement le html pour représenter des documents hypertexte, mais d'autres formats sont utilisés ( json, xml, txt, jpg, css, javascript ... ). Chaque Ressource ( dont les pages des documents hypertextes ) sont identifiés de manière unique par une URI.
* HTTP : (hypertext transfer protocol) protocole de communication entre client et serveur définissant les méthodes ( GET, PUT, POST, DELETE, HEAD, OPTIONS, TRACE, CONNECT ) que le client peut demander au serveur d'exécuter sur une ressource définie par son URI.  
* REST : c'est une redéfinition des méthodes HTTP qui restreint la portée de chaque méthode et en simplifie la définition / l'utilisation.
* URI / URL : Une URI (Uniform Resource Identifier) est un identifiant d'une ressource, une URL (Uniform Resource Locator) est une adresse vers la ressource. Une adresse est ce qui permet de définir un lien, ou d'accéder à une ressource via le protocole http. 
* un lien : c'est ce qui permet de passer d'une ressource à une autre. Se concrétise par la balise "a" en html et l'attribut "href".
* hypertexte : c'est le système de navigation entre des Ressources par des liens. Un document hypertexte est une collection de Ressources liées entre elles. A comparer à un livre dans lequel la suite d'opération de navigation est de tourner et lire les pages dans l'ordre. Dans un document hypertexte, la suite d'opération de navigation est une collection de liens à parcourir. 
* Ressource : n'importe quoi qui est identifié par une URI.
* interopérabilité : c'est quand des programmes sont capables de communiquer entre eux, ce qui implique la définition d'un protocole de communication et de formats de données connus et partagés par ces programmes.
* mashup : c'est une application qui mélange des données provenant de plusieurs sources.
* client : c'est l'application qui envoie une requête et qui attend une réponse.
* serveur : c'est l'application qui écoute et attend les requêtes et renvoie une réponse à une requête.
* Réponse :
* Requéte :
* Route http : c'est la définition d'une URL sur laquelle une opération peut être effectuée par le serveur à la demande du client selon une méthode http et aboutissant à une réponse.
* API Web : (Application Programming Interface) Collection de routes http que propose le serveur aux clients. 
* parsing de données : parcourir une donnée pour en extraire ce qui nous intéresse, éventuellement le traduire dans un autre format.
* langage de programmation : c'est un langage qui permet d'écrire un programme (une application), donc de décrire des opérations à faire exécuter par le système.
* langage de description : c'est un langage qui permet de mettre en forme des données, de décrire un modèle de données.
* négociation de contenus : c'est l'opération entre le client et le serveur leur permettant de s'accorder sur le format de données renvoyé par le serveur au client.
* web statique
* web dynamique

_Technologies utilisées :_

* http
* html
* URI / URL
* git
* github ( et githupage )
* javascript
* fetch
* XMLhttprequest
* XML
* RDF
* JSON
* le DOM

_La consigne du Projet :_
Faire un mashup qui récupére des données de plusieurs API ( au moins 2 ) uniquement en code client, en utilisant fetch ( et éventuellement XMLhttprequest ) hébergé en githubpage.

**Notions de Master 2 - OpenData**

Le but de ce cours est d'approfondir la culture de ce qu'est le Web en abordant les notions de Web de données, de Web Sémantique et d'OpenData. En s'inspirant des one page application, le code client devra faire des fetch vers l'API développée.
Les étudiants doivent réaliser un deuxième mashup cette fois-ci en code serveur avec node.js.

_Définitions :_

* Web de données : c'est une vision dans laquelle le web est un moyen d'accès à des données les rendant réutilisables. C'est voir le web comme une grande base de données.
* OpenData : démarche d'ouverture des données sur le web. L'opendata par rapport au web des données en utilise ses mécaniques et ajoute des libertés de réutilisation. C'est une démarche notamment adoptée par les administrations publiques ou collectivités territoriales afin de garantir la transparence des administrations aux citoyens. La réutilisabilité des données permet la mise en place de nouveaux services ou nouvelles applications.
* Web Sémantique : c'est une vision du web de données où les relations entre les ressources sont typées et ont une sémantique explicitée. Ce qui définit des formats de données très verbeux (au sens accessible à tout le monde car très fourni) par exemple RDF. 
* one page application : 

_La consigne du Projet :_
Faire un mashup qui récupére des données de plusieurs API ( au moins 2 ) en code client-serveur, en utilisant fetch et request hébergé sur heroku.
Développer sa propre API avec au moins une route en GET et une route en POST.

_Technologies utilisées :_

* mongodb
* mongolab
* node.js
* npm
* heroku
* SPARQL
* templating ejs
* request ( node.js )
* markdown
