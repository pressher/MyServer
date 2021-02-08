# MyServer
La liste de tous mes services.





Un serveur dédié hébergé chez [OneProvider](https://oneprovider.com/fr/node/1). Le serveur tourne sous Debian 10 avec [Docker](https://www.docker.com/), [Docker-Compose](https://docs.docker.com/compose/), [Portainer](https://www.portainer.io/) et [Traefik](https://traefik.io/). J'utilise mon script post-installation pour faire l'installation du serveur, installer les utilitaires indispensables, changer le ports SSH, etc ...

  

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


  
