# Projet SAE 501 – Concevoir, réaliser et présenter une solution technique 

## Description  
Ce projet, réalisé dans le cadre d'une SAE, consiste à concevoir et déployer une infrastructure réseau complète pour une entreprise fictive, **WorldSkills Lyon 2024 (WSL2024)**.  
L'objectif est d'assurer la **connectivité et la sécurisation des services informatiques** sur plusieurs sites (siège, site distant, Internet). Il inclut :  
- La **configuration des équipements réseau** (switches, routeurs, firewall).  
- L’**administration des services IT**.  
- La **mise en place de solutions de sécurité** adaptées aux besoins de l’organisation.  

---

## 🌐 Infrastructure réseau  
L’architecture repose sur une segmentation réseau avancée et l’interconnexion de plusieurs sites.  

### 🔹 Configuration des équipements réseau  
- Paramétrage des **switches, routeurs et firewall** avec gestion des VLANs et routage.  
- Mise en place de **protocoles de redondance** pour assurer la haute disponibilité.  

### 🔹 Gestion des VLANs  
- **Segmentation des services** :  
  - **VLAN 10** : Serveurs  
  - **VLAN 20** : Clients  
  - **VLAN 30** : DMZ  
  - **VLAN 40** : WiFi invité  
  - **VLAN 50** : IoT  
  - **VLAN 99** : Management  

### 🔹 Protocoles et services réseau  
- **Routage dynamique** : OSPF et BGP.  
- **Redondance** : FHRP pour garantir la continuité des services.  
- **Gestion des adresses IP** : DHCP avec réservation et plan d’adressage optimisé.  
- **Sécurisation des connexions** : SSH et VPN pour les accès distants.  

---

## 🖥️ Services IT  
Mise en place et administration de serveurs sur **Linux et Windows**.  

### 🔹 Gestion des utilisateurs et authentification  
- **Active Directory** : Gestion centralisée des utilisateurs et permissions.  
- Définition des **stratégies de groupe (GPO)** pour sécuriser les postes.  

### 🔹 Services réseau et stockage  
- Hébergement des services critiques : **DHCP, DNS, Web, Mail**.  
- **Partage de fichiers sécurisé** : Samba et DFS avec quotas et restrictions d’accès.  
- **Sauvegarde automatisée** : Utilisation de rsync et solutions iSCSI.  

### 🔹 Messagerie et accès à distance  
- **Serveur de mail sécurisé** (SMTP, IMAP) avec authentification Active Directory.  
- **Webmail accessible depuis l’externe**.  
- **VPN OpenVPN** pour sécuriser les connexions distantes.  

---

## 🔒 Sécurisation et supervision  
La sécurité du réseau et des services a été une priorité.  

### 🔹 Firewall et contrôle d’accès  
- **Firewall (Stormshield ou Linux)** pour filtrer et sécuriser les flux réseau.  
- **Filtrage des accès SSH**, segmentation réseau stricte et bannissement automatique des connexions suspectes.  

### 🔹 Monitoring et supervision  
- **Gestion centralisée** des équipements et services critiques.  
- Mise en place d’**alertes et logs** pour détecter les comportements anormaux.  

---

## 🔧 Méthodologie et validation  
Le projet a été mené de manière structurée avec des validations régulières.  

### 🔹 Déploiement et tests  
- Utilisation d’**environnements virtualisés** : VMware ESXi et Proxmox.  
- **Tests et validation** progressive des configurations réseau et systèmes.  

### 🔹 Documentation et livrables  
- **Plan d’adressage** détaillé.  
- **Configurations réseau et procédures** de mise en production.  

---

🚀 **Ce projet illustre une maîtrise avancée des technologies réseau et systèmes, combinant sécurité, haute disponibilité et évolutivité.**  
