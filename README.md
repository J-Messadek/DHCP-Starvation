⚠️ DHCP Starvation Simulation Script (Scapy)

    Ce script est strictement à but pédagogique et ne doit être utilisé que dans un environnement de test isolé. Il permet de simuler une attaque de type DHCP Starvation en envoyant des requêtes DHCP Discover avec des adresses MAC falsifiées, à des fins d’analyse réseau locale.

❗ AVERTISSEMENT IMPORTANT
🚨 Interdiction d’usage sur des réseaux publics

Ce script envoie de faux paquets DHCP Discover (spoofing d'IP + MAC) pour saturer un serveur DHCP en épuisant son pool d’adresses IP disponibles. Il peut perturber le service DHCP d’un réseau, rendant impossible pour les machines légitimes d’obtenir une adresse IP.

⚠️ Son exécution en dehors d’un environnement local (lab, VM, réseau isolé) constitue une violation éthique et légale.

L’auteur de ce dépôt décline toute responsabilité en cas de mauvaise utilisation.
🎯 Objectif pédagogique

    Comprendre le fonctionnement d’une attaque DHCP Starvation.

    Apprendre à générer des paquets DHCP Discover falsifiés avec Scapy.

    Observer l’épuisement du pool d'adresses IP du serveur DHCP dans un environnement contrôlé via des outils comme Wireshark.

📦 Dépendances

    Python 3.x

    Scapy

pip install scapy
