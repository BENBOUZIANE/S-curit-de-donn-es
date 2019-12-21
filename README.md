# Sécurit-de-données

## atgnupg(rida_BENBOUZIANE)
Les échanges d'information ne sont pas sûrs. En particulier, le courrier électronique (émail) peut être lu par des tierces personnes, et on n'est jamais sûr de la provenance réelle d'un émail. Il est possible d'utiliser des procédés cryptographiques. En particulier, il existe des méthodes à clés asymétriques, permettant soit de signer (authentifier) un texte, soit de le chiffrer (le rendre illisible au monde entier). GnuPG est une des implémentations utilisant un tel système. Il a l'énorme avantage en comparaison avec son équivalent propriétaire PGP d'être un logiciel libre et de reposer sur la norme OpenPGP. De plus, le créateur de PGP, Philip Zimmermann, a rejoint récemment le groupe OpenPGP. Cet atelier va présenter l'utilisation de GnuPG, ainsi que toute la philosophie qui tourne autour du système de chiffrement à clé publique. 

## kerberos(rida_benbouziane)
La sécurité et l'intégrité d'un système au sein d'un réseau peut être une lourde tâche. En effet, elle peut monopoliser le temps de plusieurs administrateurs rien que pour effectuer le suivi des services en cours d'exécution sur un réseau et surveiller la manière selon laquelle ils sont utilisés. De plus, l'authentification des utilisateurs auprès des services réseau peut s'avérer être une opération dangereuse lorsque la méthode utilisée par le protocole est par essence nonsécurisée, comme c'est la cas avec les protocoles FTP et telnet lors du transfert de mots de passe de manière non-cryptée sur le réseau. Kerberos représente un moyen d'éliminer le besoin de protocoles qui utilisent des méthodes d'authentification vulnérables, permettant ainsi de renforcer la sécurité réseau en général. 

## openssh(rida_benbouziane)
OpenSSH  est un ensemble d'outils informatiques libres permettant des communications sécurisées sur un réseau informatique en utilisant le protocole SSH 
OpenSSH chiffre tout le trafic (mots de passe y compris), via une combinaison astucieuse de chiffrement symétrique et asymétrique. OpenSSH fournit également d'autres méthodes d'authentification alternatives au traditionnel mot de passe.  

## openssl(rida_benbouziane)
openssl est une boîte à outils de chiffrement comportant deux bibliothèques (libcrypto fournit les algorithmes cryptographiques et libssl implémente le protocole de communication Transport Layer Security (TLS) ainsi que son prédécesseur Secure Sockets Layer (SSL)) et une interface en ligne de commande(openssl).

## openvpn(rida_benbouziane)
openvpn : est l’un des logicielles open source les plus populaires et les plus utilisées qui implémente des technologies de réseau privé virtuel (VPN) pour créer des connexions point à point sécurisées ou de site à site dans des configurations routées ou pontées. Il utilise un protocole de sécurité personnalisé qui utilise SSL / TLS pour l'échange de clés. 
## parefeu(rida_benbouziane)

## SNORT(rida_BENBOUZIANE)
Snort est un système de détection d'intrusion (ou NIDS) libre publié sous licence GNU GPL. 
Snort est un système de détection d'intrusion sur réseau créé par Martin Roesch.  
Snort est un renifleur de paquets qui surveille le trafic réseau en temps réel, en examinant chaque paquet de près pour détecter une charge dangereuse ou des anomalies suspectes.  
Snort est basé sur libpcap (pour la capture de bibliothèque), un outil largement utilisé dans les analyseurs et les renifleuNrs de trafic TCP / IP.  
Grâce à l'analyse de protocole, à la recherche de contenu et à la correspondance, Snort détecte les méthodes d'attaque, notamment le déni de service, le dépassement de mémoire tampon, les attaques CGI, les analyses de port furtif et les problemes de SMB. Lorsqu'un comportement suspect est détecté, Snort envoie une alerte en temps réel à Syslog, à un fichier "d'alertes" séparé ou à une fenêtre contextuelle. Le groupe NSS, une organisation européenne de tests de sécurité des réseaux, a testé Snort ainsi que les produits de système de détection d'intrusion (IDS) de 15 fournisseurs majeurs, dont Cisco, Computer Associates et Symantec.  
## VPN IPsec(Rida BENBOUZIANE)

Un VPN (Virtual Private Network) est un réseau virtuel s'appuyant sur un autre réseau comme Internet. Il permet de faire transiter des informations, entre les différents membres de ce VPN, le tout de manière sécurisée. 
On peut considérer qu'une connexion VPN revient à se connecter en réseau local mais en utilisant Internet. On peut ainsi communiquer avec les machines de ce réseau en prenant comme adresse de destination, l'adresse IP local de la machine que l'on veut atteindre. 
Il existe plusieurs types de VPN fonctionnant sur différentes couches réseau, voici les VPN que nous pouvons mettre en place sur un serveur dédié ou à la maison : 
ipsec : Plus efficace que le PPTP en termes de performance, mais aussi très contraignant au niveau de la mise 
en place 
