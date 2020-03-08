# Tchat


Ceci est une application client-serveur de chat.

Pour l'utiliser, lancez un terminal, allez dans le dossier Tchat dans le projet et lancez la commande "javac -d . \*/\*.java"

Ensuite dans un terminal au même endroit lancez la commande "java TestServeur" pour lancer le serveur

Puis dans un autre terminal lancez la commande "java TestFenetre &" pour lancer un client (vous pouvez l'utiliser plusieur fois dans le même terminal)


Pour avoir accès à la documentation lancez la commande "javadoc -d ../doc \*/\*.java" puis ouvrez index.html dans le dossier doc



Liste des fonctionnalités :

  - Conversation entre plusieurs utilisateur :
    Les clients peuvent se connecter et envoyer des messages à tous les autres clients.
    Les clients ont tous un nom different, si un client essaye de se connecter avec un nom déjà pris il sera refusé
    Les clients peuvent être différenciés par leurs nom et une couleur
    
  - Messages privés :
    Les clients peuvent à l'aide de l'interface graphique choisir à qui envoyer un message.
    Les choix disponibles sont :
      - "groupe" envoyer des messages à tout le monde
      - "message privé" "nom du destinataire" envoyer des messages à un destinataire uniquement
  
  
Inconveniants :

  - Les couleurs
    Les couleurs des clients ne sont prises que parmis 7 couleurs, on peut donc avoir des clients avec la même couleurs
    
  - Fermeture du serveur
    Pour fermer le serveur il faut lui envoyer un signal logiciel (Ctrl + c), les clients seront déconnectès mais pas prévenus
  
