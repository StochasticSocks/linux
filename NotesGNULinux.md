# Notes sur les systèmes GNU/Linux

## Cadre général


## Gestion des paquets sous Archlinux

### Configuration de base de pacman

Liste des miroirs : comment choisir sur la base de la vitesse de téléchargement et mettre à jour la mirrorlist ?



### Commandes de base pacman

* Mise à jour de l'ensemble du système :

       sudo pacman -Syu

* Installer des paquets :

        sudo pacman -S *paquet1 paquet2 paquet3*

* Supprimer des paquets :
    * Sans éliminer les dépendances :

            sudo pacman -R *paquet*

    * En éliminant les dépedances :
    
            sudo pacman -Rs *paquet*
