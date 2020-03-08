# Tchat


Ceci est une application client-serveur de chat.

Pour l'utiliser, lancez un terminal, allez dans le dossier Tchat dans le projet et lancez la commande "javac -d . \*/\*.java"

Ensuite dans un terminal au même endroit lancez la commande "java TestServeur" pour lancer le serveur

Puis dans un autre terminal lancez la commande "java TestFenetre &" pour lancer un client (vous pouvez l'utiliser plusieurs fois dans le même terminal)


Pour avoir accès à la documentation lancez la commande "javadoc -d ../doc \*/\*.java" puis ouvrez index.html dans le dossier doc



Liste des fonctionnalités :

  - Connexion :
    Pour se connecter les client doivent remplir les champs "Nom", "IP", "port", puis appuyer sur le bouton Connection
    Le Tchat s'ouvrira uniquement quand le serveur aura accepté le client

  - Conversation entre plusieurs utilisateur :
    Les clients peuvent se connecter et envoyer des messages à tous les autres clients.
    Les clients ont tous un nom different, si un client essaye de se connecter avec un nom déjà pris il sera refusé.
    Les clients peuvent être différenciés par leurs nom et une couleur.
    
  - Messages privés :
    Les clients peuvent à l'aide de l'interface graphique choisir à qui envoyer un message.
    Les choix disponibles sont :
      - "groupe" envoyer des messages à tout le monde
      - "message privé" "nom du destinataire" envoyer des messages à un destinataire uniquement
  
  
Inconvénient :

  - Les messages privés
    Quand un client reçoit un message privé il ne peut pas faire la différence avec un message normal.

  - Les couleurs
    Les couleurs des clients ne sont prises que parmis 7 couleurs, on peut donc avoir des clients avec la même couleurs.
    
  - Fermeture du serveur
    Pour fermer le serveur il faut lui envoyer un signal logiciel (Ctrl + c), les clients seront déconnectès mais pas prévenus.
  
  - Test sur ordinateurs séparés
    Aucun test n'a été efféctué avec deux machines différentes, je ne sais donc pas si ça marche.
    
  - Difficulté pour lancer l'application
    Pour lancer l'application il faut utiliser un terminal et lancez des commandes, ce qui est peu pratique
    
