# Concevoir, réaliser et présenter une solution technique

Ce projet, réalisé dans le cadre d'une SAE, consiste à concevoir et déployer une infrastructure réseau complète pour une entreprise fictive, WorldSkills Lyon 2024 (WSL2024). L'objectif est d'assurer la connectivité et la sécurisation des services informatiques sur plusieurs sites (siège, site distant, Internet). Il inclut la configuration des équipements réseau, l’administration des services IT et la mise en place de solutions de sécurité.

Infrastructure réseau
--- L’architecture repose sur une segmentation réseau avancée et l’interconnexion de plusieurs sites ---

Configuration des équipements réseau : switches, routeurs et firewall avec gestion des VLANs et routage.
Gestion des VLANs : isolation des services (serveurs, clients, DMZ, IoT, WiFi invité, management).
Protocoles et services réseau :
Routage avec OSPF et BGP.
Redondance avec FHRP.
Gestion des adresses IP avec DHCP.
Sécurisation des connexions avec SSH et VPN.
Services IT

--- Mise en place et administration de serveurs sur Linux et Windows ---

Active Directory : gestion des utilisateurs et des permissions.
Serveurs DHCP et DNS : gestion dynamique des adresses IP et résolution de noms.
Infrastructure de stockage : partage de fichiers (Samba, DFS) et gestion des sauvegardes (rsync, iSCSI).
Messagerie sécurisée : serveur de mail avec authentification Active Directory et webmail.
Gestion des accès à distance : VPN sécurisé avec OpenVPN.
Sécurisation et supervision

--- La sécurité du réseau et des services a été une priorité ---

Firewall (Stormshield ou Linux) : contrôle des flux entre les réseaux internes et l'Internet.
Contrôle d’accès et durcissement des configurations : filtrage des accès SSH, segmentation réseau stricte, bannissement automatique des connexions suspectes.
Supervision et monitoring : gestion centralisée des équipements et services critiques.
Méthodologie et validation

--- Le projet a été mené de manière structurée avec des validations régulières ---

Utilisation d’environnements virtualisés : VMware ESXi et Proxmox pour simuler l’infrastructure.
Tests et mise en production : validations progressives des configurations réseau et services.
Documentation complète : plans d’adressage, configurations détaillées et procédures de déploiement.

Ce projet démontre une maîtrise avancée des technologies réseau et systèmes pour la mise en place d'une infrastructure fiable, sécurisée et évolutive.
