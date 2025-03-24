# Projet SAE 501 – Concevoir, réaliser et présenter une solution technique

## 💡 Présentation personnelle du projet  
Dans le cadre de la SAE 501, nous avons travaillé en groupe sur un projet imposé, centré sur la **conception et le déploiement d’une infrastructure réseau complète** pour une entreprise fictive répartie sur plusieurs sites (siège, site distant, Internet).  
Même si le sujet nous a été attribué, ce projet a représenté une **véritable opportunité d’apprentissage**, notamment pour mettre en pratique nos compétences réseau et systèmes dans un contexte proche du réel.

Travailler en équipe nous a permis de **répartir les responsabilités**, de croiser nos approches, et d’approfondir notre compréhension des **enjeux techniques liés à la connectivité, la sécurité, et la gestion des services IT**.  
C’était également un bon exercice de coordination, de rigueur, et de gestion de projet, avec des livrables techniques à fournir tout au long de la SAE.

---

## 🌐 Infrastructure réseau  
L’architecture proposée était définie dans le cahier des charges, avec une segmentation réseau avancée et l’interconnexion de plusieurs sites.

### 🔹 Configuration des équipements réseau  
- Paramétrage des **switches, routeurs et firewall**.  
- Gestion des **VLANs** pour isoler les différents services.  
- Implémentation de **protocoles de redondance** pour assurer la continuité des services.

### 🔹 Gestion des VLANs  
| VLAN | Utilisation           |
|------|------------------------|
| 10   | Serveurs              |
| 20   | Clients               |
| 30   | DMZ                   |
| 40   | WiFi invité           |
| 50   | IoT                   |
| 99   | Management réseau     |

### 🔹 Protocoles et services réseau  
- **OSPF et BGP** pour le routage dynamique.  
- **FHRP** pour la redondance des passerelles.  
- Plan d’adressage détaillé et **DHCP avec réservation**.  
- Sécurisation des accès via **SSH et VPN**.

---

## 🖥️ Services IT  
Notre groupe a également déployé et administré plusieurs serveurs Linux et Windows pour héberger les services critiques.

### 🔹 Gestion des utilisateurs  
- **Active Directory** pour centraliser les comptes et les droits.  
- Mise en place de **GPO** pour sécuriser et standardiser les postes clients.

### 🔹 Services réseau et de fichiers  
- Déploiement des services essentiels : **DHCP, DNS, Web, Mail**.  
- Partage de fichiers via **Samba et DFS**, avec gestion des quotas.  
- **Sauvegardes automatisées** à l’aide de rsync et de volumes iSCSI.

### 🔹 Messagerie et accès à distance  
- Serveur de messagerie compatible avec Active Directory.  
- Accès distant sécurisé via **Webmail et VPN OpenVPN**.

---

## 🔒 Sécurité et supervision  
La sécurisation de l’architecture était au cœur des enjeux du projet.

### 🔹 Firewall et filtrage  
- Utilisation d’un **firewall Stormshield ou Linux** selon les cas.  
- Règles de filtrage strictes, segmentation réseau rigoureuse.  
- **Détection et blocage** des accès suspects via des outils de surveillance.

### 🔹 Supervision  
- Mise en place d’une solution de **monitoring centralisée**.  
- Collecte de logs, alertes automatiques et vérification de la disponibilité des services.

---

## 🛠️ Déploiement et méthodologie  
Nous avons travaillé en environnement virtualisé, en utilisant **VMware ESXi** et **Proxmox** pour simuler les différents sites et services.

Des **tests réguliers** ont permis de valider la cohérence et la fiabilité de nos choix techniques.

Chaque étape a été documentée avec soin pour produire des livrables professionnels :  
- **Plan d’adressage**  
- **Configurations des équipements**  
- **Procédures de déploiement**  

---

🚀 **Ce projet nous a permis, en tant qu’équipe, de consolider nos compétences en réseaux et systèmes, de faire face à des contraintes techniques concrètes, et d’expérimenter des solutions robustes et sécurisées adaptées à une infrastructure d’entreprise.**

💬 **Sur un plan plus personnel**, ce projet a représenté un vrai défi. La charge de travail était importante, et il a fallu apprendre à se coordonner efficacement, répartir les tâches, et faire face aux imprévus techniques comme organisationnels.  
Mais malgré la difficulté, cela a été une **expérience extrêmement enrichissante**, tant sur le plan **technique** – avec la mise en œuvre de technologies avancées – que **relationnel**, en apprenant à travailler à plusieurs sur un projet complexe, à s’écouter, à se soutenir et à avancer ensemble.
