# MyServer
La liste de tous mes services.





La quasi-totalité de ces services tournent sur un seul serveur dédié hébergé chez [OneProvider](https://oneprovider.com/fr/node/1). Le serveur tourne sous Debian 10 avec [Docker](https://www.docker.com/), [Docker-Compose](https://docs.docker.com/compose/), [Portainer](https://www.portainer.io/) et [Traefik](https://traefik.io/). J'utilise mon script post-installation pour faire l'installation du serveur, installer les utilitaires indispensables, changer le ports SSH, etc ...

  

# Les services



- Partage de textes ([Hastebin](https://hastebin.com/about.md) // *Alternative à Pastebin*) : [hastebin.presher.fr](https://hastebin.presher.fr)
- Partage d'images ([Chevereto](https://chevereto.com/) // *Alternative à Imgur*) : [img.presher.fr](https://img.presher.fr)
- Partage de fichiers ([Jirafeau](https://framalibre.org/content/jirafeau) // *Alternative à Wetransfert*) : [send.presher.fr](https://send.presher.fr)
- Raccourcisseur d'URL ([Yourls](https://yourls.org/) / [Kutt](https://kutt.it/) // *Alternative à bit.ly*) : [ppmc.me](https://ppmc.me)
- Serveur vocal [TeamSpeak](https://www.teamspeak.com/en/) : [ts3.presher.fr](ts3://ts3.presher.fr)
- Interface web du serveur TeamSpeak ([ts-website](https://github.com/Wruczek/ts-website)) : [tsweb.presher.fr](https://tsweb.presher.fr)
- Statistique du serveur TeamSpeak ([Ranksystem](https://ts-ranksystem.com/)) : [ts3rank.presher.fr](https://ts3rank.presher.fr)
- Bot du serveur TeamSpeak ([Sinusbot](https://www.sinusbot.com/)) : [sinusbot.presher.fr](https://sinusbot.presher.fr)
- Serveur vocal [Mumble](https://www.mumble.info/) : [mumble.presher.fr](https://mumble.presher.fr)
- Client web du serveur Mumble ([Mumble-Web](https://github.com/Johni0702/mumble-web)) : [web-mumble.presher.fr](https://web-mumble.presher.fr)
- Bot du serveur Mumble ([MumbleDJ](https://github.com/matthieugrieger/mumbledj))
- Partages de ressources IT ([Filebrowser](https://github.com/filebrowser/filebrowser) modifié) : [partages.presher.fr](https://partages.presher.fr)
- Partages de ressources IT avec lien direct ([Apache](https://httpd.apache.org/)) : [partages-directs.presher.fr](https://partages-directs.presher.fr)
- Page Status de mes services ([CachetHQ](https://github.com/CachetHQ/Cachet)) : [status.presher.fr](https://status.presher.fr)
- Un concentrateur de messagerie ([Ferdi](https://getferdi.com/) // *Alternative à Franz*)
- Gestionnaire de mot de passes ([Bitwarden](https://bitwarden.com/) // *Alternatice à Dashlane*)
- Cloud privé ([NextCloud](https://nextcloud.com/) // *Alternative à GoogleDrive*)
- Gestionnaire de taches & rappels ([Nextcloud Task](https://nextcloud.com/) // *Alternative à Todo de Micosoft*)
- Gestionnaire de notes ([Nextcloud Note](https://nextcloud.com/) // *Alternatice à Keep de Google*)
- Interface générale des services ([Organizr](https://organizr.app/))
- Sauvegarde de photos ([OwnPhotos](https://github.com/hooram/ownphotos) / [PhotoPrism](https://photoprism.app/) // Alternative à Google Photo)
- Sauvegarde de serveurs & ordinateurs ([UrBackup](https://www.urbackup.org/))
- Serveur mail ([Poste.io](poste.io) // *Alternative à Gmail*)
- Client web-mail ([Roundcube](https://roundcube.net/) // *Alternative à Gmail*)
- Gestionnaire de repo et CI/CD ([Gitlab](https://about.gitlab.com/))
- Partage de formations ([Filebrowser](https://github.com/filebrowser/filebrowser) modifié)
- Éditeur de texte en ligne ([VSCode](https://hub.docker.com/r/codercom/code-server))
- Serveur de streaming ([Plex](https://www.plex.tv/fr/) // *Alternative à Netflix*)
- Système de téléchargement automatique :
	- Catalogue de demandes ([Ombi](https://ombi.io/))
	- Indexeur de torrents ([Jackett](https://github.com/Jackett/Jackett))
	- Bypass de Cloudflare ([Cloudproxy](https://github.com/RyuzakiH/CloudflareSolverRe))
	- Gestion du téléchargement des films (Radarr)
	- Gestion du téléchargement des séries (Sonarr)
	- Serveur de téléchargement ([rTorrent](https://github.com/rakshasa/rtorrent) avec [Flood](https://github.com/Flood-UI/flood))
	- Automatisation du renommage des fichiers ([FileBot](https://www.filebot.net/))
	- Supervision de Plex ([Tautulli](https://tautulli.com/))
	- Interface Grafana pour Plex ([Varken](https://github.com/Boerderij/Varken))
- Passerelle de connexions RDP, VNC, SSH ([Guacamole](https://guacamole.apache.org/))
- Supervision de mes services ([Zabbix](https://www.zabbix.com/) // *Alternative* [Centreon](https://centreon.com/) / [LibreNMS](https://librenms.org/) )
- Automatisation de ma page Status ([Zabbix-CachetHQ](https://github.com/qk4l/zabbix-cachet))
- Affichage des données ([Grafana](https://grafana.com/))
- Agrégateur de logs ([Loki](https://grafana.com/oss/loki/))
- Concentrateur pour les équipements Unifi ([Controleur Unifi](https://hub.docker.com/r/linuxserver/unifi-controller))
- Récupération des données Unifi et envoi vers Grafana ([Unifi Poller](https://github.com/unifi-poller/unifi-poller))
- Serveur de domotique ([Jeedom](https://www.jeedom.com/site/fr/))
- Wiki personnel ([BookStack](https://www.bookstackapp.com/))
- Interface Web de gestion de serveur ([CockPit](https://cockpit-project.org/running)) 
- Serveur de portail captif ([PFSense](https://www.pfsense.org/))



## Pour un usage professionel
- Gestionnaire de service d'assistancce ([GLPI](https://glpi-project.org/fr/))
- Supervision de services ([Zabbix](https://www.zabbix.com/) // *Alternative* [Centreon](https://centreon.com/) / [LibreNMS](https://librenms.org/) )
- Controleur de domaine ([ActiveDirectory](https://docs.microsoft.com/fr-fr/windows-server/identity/ad-ds/active-directory-domain-services))
- Serveur de virtualisation ([]() // *Alternative [Proxmox]() / []()*)
- Serveur DHCP
- Sreveur de déploiement ([FOG]())
- Serveur de téléphonie IP ([]())
- Ansible
- Serveur de base de données ([Lotus]())
- Serveur de gestion de projets ([Odoo]())
- Sreveur mail exhange/ibm ([]())
-



# Les sites internet

- [Labo-Tech.fr](https://labo-tech.fr/) : partages de connaissances autour de l'IT ([Wordpress](https://fr.wordpress.org/))
- [MickaelAsseline.com](https://mickaelasseline.com/) : CV & Portfolio ([Wordpress](https://fr.wordpress.org/))
- [Csgo.papamica.fr](https://csgo.papamica.fr/) : profil de joueurs Counter Strike (HTML/CSS/JS)
- [SoleneCheymol.com](https://solenecheymol.com/) : CV & Portfolio (HTML/CSS/JS)
- [PlumCulture.fr](https://plumculture.fr/) : blog autour de la culture contemporaine ([Wordpress](https://fr.wordpress.org/))
- [Cyprienmescouilles.ovh](http://cyprienmescouilles.ovh/) : site troll pour un confrère (HTML/CSS/JS)
















Cela fait maintenant plusieurs mois que je suis passé sous Linux sur l'ensemble de mes ordinateurs (sauf 1, essentiel pour le gaming et l'utilisation de certains logiciels dont la suite Adobe).

  

## La distribution

Le premier choix complexe fut celui de la distribution que j'allais choisir. Mon raisonnement fut simple : quitte à avoir du changement, autant en profiter pour apprendre ! Dans mon quotidien j'utilise Debian et CentOS pour mes serveurs, je ne voulais donc pas partir sur ces solutions. 
Durant mes recherches j'ai découvert le magnifique principe de distribution "Rolling Release", ce qui signifie : pas de mise à jours majeures, l'OS évolue au fur et à mesure ! Le référent dans ce domaine c'est [ArchLinux](https://www.archlinux.org/), mais son installation est totalement manuelle et je n'étais pas totalement à l'aise avec ça (malgré plusieurs essais), c'est pour cela que je me suis tourné vers sa distribution petite sœur : [Manjaro](https://manjaro.org/) !

**Avantages :** Simplicité d'installation, les gestionnaires de paquets Pacman et Yay, les paquets AUR, la communauté, le RollInRealease

**Inconvénients :** Je cherche encore ...
Plus généralement : la suite Office et Adobe me manque, mais c'est commun à toutes les distributions Linux.

  

## L'environnement de bureau

Ayant utilisé Kali ou encore Debian et Fedora en version WorkStation à plusieurs occasion sous XFCE, c'est donc tout naturellement que je me suis tourné vers cet environnement de bureau à l'installation de Manjaro. Les principaux avantages : rapidité, légèreté, simple et bien documenté. Principal inconvénient durant mon utilisation : ne supporte pas nativement mon écran 49 pouces.

Mais voilà, après plusieurs mois, j'ai fini par faire le tour de XFCE, et comme à mon habitude : si je n'apprend plus ou ne découvre plus rien, j'ai besoin de changements !

Et c'est à aussi un des gros avantages de Linux, en quelques commandes, je peux changer d'environnement de bureau ! Après quelques recherches, c'est vers KDE que je jette mon dévolu ! Et croyez moi : je ne suis pas déçu ! Je retrouve tous les avantages de XFCE, avec bien plus de personnalisations, des outils adéquates à mon utilisation et une interface plus jolie en générale ! Ah j'ai failli oublié : le support de mon écran 49 pouces nativement !

**Avantages :** tout plein

**Inconvénients :** pour le moment aucun (4 mois d'utilisation)

## Les logiciels & applications
- VSCode (Editeur )
- flamshot ou ShareX (implémenté avec Hastebin, Plik et ) (Utilitaire de screenshot)
- Ferdi (Concentrateur de messagerie)
- Termius (Client SSH avec synchronisation Cloud)
- VirtualBox (VM Windows & MacOS)
- AngryIP Scanner (*Alternative à Advanced-IP-Scanner sur Windows*)
- Brave (Navigateur internet basé sur Chronium)
- Teamviewer (Connexion à distance)
- Script getip (Améliore la commande ip -a)
- Cloudstation (Synchronisation continue de mes documents essentiels)
- Stacer (Gestionnaire des taches graphique)
- Mailspring (Client mails // *Alternative à Outlook*)
- WPS 2019 (Suite de bureautique // *Alternative à la suite Office*)
- GParted (Gestionnaire de partition graphique)
- Yakuake (Permet d'avoir toujours un terminal sous la main)
- NESSUS (sous Docker // Scan de sécurité)
- Blue Proximity (Verrouille mon ordinateur quand je m'éloigne)
- fusuma (Ajoute les geste trackpad personnalisables)
- Plank (Une barre de lancement rapide comparable à celle de MacOS)
- OpenVPN (Client VPN)
- Docker (Evidemment .. ;))
- Aether (Change l'interface de connexion)
- Dolphin (Gestionnaire de fichiers)
- Gimp (Editeur d'images // *Alternative à PhotoShop*)
- Photoflare (Editeur d'image // *Alternative à PhotoFiltre*)
- Steam (Pour le jeu, de temps en temps)
- VLC (Pour lire les fichiers vidéo)
- TimeMachine (Sauvegarde automatique de mon ordinateur)

# Quelques liens utiles
Mon CV & Portfolio : [mickaelasseline.com](https://mickaelasseline.com)</br>
Mon Profil LinkedIn : [Mickael Asseline](https://www.linkedin.com/in/mickael-asseline/)</br>

Mon GitLab : [git.papamica.fr](https://git.papamica.fr) </br>
Mon repo Github pour mes docker-compose : [github.com/PAPAMICA/docker-compose-collection](https://github.com/PAPAMICA/docker-compose-collection)</br>
Mon repo Github pour mes scripts : [github.com/PAPAMICA/scripts](https://github.com/PAPAMICA/scripts)</br>
Mon repo Github pour mes templates :  [github.com/PAPAMICA/templates](https://github.com/PAPAMICA/templates)</br>
Mon site Labo-Tech : [Labo-Tech.fr](https://Labo-Tech.fr)</br>

