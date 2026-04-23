# 🛡️ Alexis Rousseau

## Ingénieur Systèmes, Réseaux & Infrastructures | Automatisation & Cybersécurité

---
## ---------- À propos ---------
**Ingénieur Systèmes & Infrastructures** avec un parcours de **5 ans en ingénierie de pipelines VFX** (Développement, Lead & DevOps), j'apporte aujourd'hui mon expertise à la conception et à la sécurisation des environnements IT critiques.

Ma force réside dans ma capacité à coupler une culture **Développement** avec une gestion rigoureuse des **Infrastructures Systèmes et Réseaux**. J'approche chaque projet avec une philosophie "**Automation & Security by Design**".

- **Spécialité** : Industrialisation de workflows complexes, IaC (Ansible) et durcissement (Hardening) de systèmes Linux/Windows.

- **Valeur ajoutée**: Résolution d'incidents critiques (L2/L3), gestion de la haute disponibilité et déploiement de parcs informatiques hétérogènes.
---
## ---------- Expertise Techniques ----------

| Domaine                    | Technologies maitrisées                                                       |
|----------------------------|-------------------------------------------------------------------------------|
| **Systemes & Cloud**       | Linux (Debian/RH), Windows Server (AD/GPO), Azure/AWS, Docker, VMware         |
| **Réseaux & Security**     | Architecture Cisco (VLAN, OSPF), IPv4/IPv6, VPN (IPsec/SSL), Stormshield, Audit ANSSI    |
| **Automatisation & Dev**   | Python, Ansible (IaC), Bash, PowerShell, Git, SQL                    |
| **Supervision & Ops**      | Nagios, GLPI, CrowdSec, Wireshark, Nginx                                      |

---
---
## ---------- Réalisations Techniques & Projets d'Infrastructure ----------
Sélection de projets d'infrastructure et de sécurité simulant des environnements de production réels.

## -- ☁️ Infrastructures Cloud & Systèmes Hybrides --
###  📂 [Projet d'Architecture Cloud & Migration Haute Disponibilité](https://github.com/FaramirDev/projet-migration-cloud-nimbus)

- **Objectif** : Concevoir une infrastructure résiliente sur un fournisseur Cloud (AWS) pour garantir la continuité de service.

- **Réalisations** : Configuration complete de l'architecture AWS. VPC, Subnet, SG, AWS ECS Fargate, RDS, Backup, S3, IAM, Cognito, WAF.

- **Stack** : Cloud Provider, Sécurité Cloud, Supervision.

### 📂 [Projet d'Industrialisation Ansible - Parc Hybride & Stratégie de Backup](https://github.com/FaramirDev/projet-ansible-hybrid-parc-automatisation) 

- **Objectif** : Automatiser le déploiement et la sécurisation d'un parc mixte (Windows/Linux) pour un studio de production.

- **Réalisations** : Industrialisation via Ansible, Audit de Sécurité du Parc et Serveur, Mise en place d'une politique de sauvegarde 3-2-1 avec Veeam, et chiffrement des données sensibles (Cryptomator).

- **Stack** : Ansible, Python, PowerShell, Active Directory, Veeam, Linux/Windows.

## -- 🌐 Réseaux & Interconnexions Critiques --
### 📂 [Projet Conception d'un Backbone Réseau Multi-sites](https://github.com/FaramirDev/projet-cisco-architecture-network-secure)

- **Objectif** : Créer une infrastructure réseau robuste pour une société multi-sites avec haute disponibilité.

- **Réalisations** : Routage dynamique OSPF, redondance de passerelle (HSRP), agrégation de liens (EtherChannel) et segmentation fine par VLAN.

- **Stack** : Cisco IOS, Routage L3, Switching L2, IPv4, Plan d'adressage complexe.

### 📂 [Projet d'Accès Distant Sécurisé & Intégration de Nouvelles Entités](https://github.com/FaramirDev/projet-vpn-stormshield-ad-security)

- **Objectif** : Raccorder de nouveaux sites distants au SI central en garantissant la confidentialité des flux.

- **Réalisations** : Configuration de pare-feu Stormshield, mise en place de tunnels VPN IPsec et SSL, et extension de l'annuaire Active Directory (RODC).

- **Stack** : Stormshield, VPN, Windows Server, AD DS, Filtrage applicatif.

### 📂 [Projet d'Ingénierie de Migration vers IPv6](https://github.com/FaramirDev/projet-ipv6-migration-dualstack)

- **Objectif** : Assurer la transition d'une infrastructure existante vers la norme IPv6 sans interruption de service.

- **Réalisations** : Déploiement en Dual-Stack, configuration des protocoles de routage IPv6 et sécurisation du voisinage réseau.

- **Stack** : IPv6, Cisco, Routage Dual-Stack.

## -- 🛡️ Cybersécurité & Durcissement (Hardening) --
### 📂 [Projet Sécurisation d'Infrastructures Web - Wordpress](https://github.com/FaramirDev/projet-web-infrastructure-wordpress-security)
- **Objectif** : Protéger des services Web (Extranet) contre les menaces externes et les intrusions.

- **Réalisations** : Hardening de serveurs Nginx/Apache, authentification centralisée via LDAP et chiffrement TLS.

- **Stack** : Linux, Nginx, LDAP, SSL/TLS, MySQL.

### 📂 [Projet Sécurisation & Durcissement d'Infrastructures Web - Crowdsec](https://github.com/FaramirDev/projet-web-infrastructure-security-crowdsec)
- **Objectif** : Protéger des services Web (Intranet/Extranet) contre les menaces externes et les intrusions.

- **Réalisations** : Hardening de serveurs Nginx/Apache, implémentation d'un IPS/IDS avec CrowdSec/Fail2ban, authentification centralisée via LDAP et chiffrement TLS.

- **Stack** : Linux, Nginx, LDAP, CrowdSec, SSL/TLS, MySQL.

### 📂 [Projet d'Audit & Organisation d'un Réseau Local](https://github.com/FaramirDev/projet-lan-design-technical-documentation)
- **Objectif** : Auditer et refondre l'architecture d'un réseau local pour en améliorer la sécurité et la scalabilité.

- **Réalisations** : Création du Document d'Architecture Technique (DAT), schématisation logique/physique et mise en place des services de base (DHCP/DNS).

- **Stack** : Méthode de gestion de projet, Visio/Draw.io, TCP/IP, Services réseau.

---
## ---------- Projet Python ----------  
### 📂 [Projet Defender Sentinel HIDS sous Python - Linux  ](https://github.com/FaramirDev/Projet-Audit-Network-Scanner-Linux)
- **Objectif** : Réaliser un outil HIDS sous python permettant de suivre l'activité des connexions SSH et de bannir automatique les potentielles attaque par brutes forces. 

- **Realisation** : Réalisation de Defender Sentil permettant de fournir des logs et suivre l'activité des connexions au systeme avec un blocage automatique sur le noyaux si détection de brute force avec une Remonté d'Alerte sur Serveur discord. 

### 📂 [Projet Audit Scan Network Vulnerability sous Python - Linux ](https://github.com/FaramirDev/Projet-Audit-Network-Scanner-Linux)
- **Objectif** : Cartographier un segment réseau (lan) et analyser les expositions des services sur chaques Hotes decouvert. Comprendre et Analyser les expositions des potentiels vecteurs.

- **Realisation** : NetPulse-Audit est un outil d'exploration réseau développé en Python. Permet de générer un fichier Json de l'ensemble de la cartographie réseau découvert. 

- **Avertissement Legal** : Cet outil est conçu pour un usage strictement pédagogique et professionnel dans le cadre d'audits de sécurité autorisés. L'auteur décline toute responsabilité en cas d'usage malveillant. Nous rappelons qu'il strictement interdit de scanner un réseau sans y avoir été autorisé par le propriétaire.

### 📂 [Projet Audit Health Shield sous Python - Linux ](https://github.com/FaramirDev/Projet-Audit-Health-Shield-Linux)
- **Objectif** : Auditer le Serveur/Client Linux de manière automatique, fournir des logs régulier pour un historique et suivi complet. Monitoring & Scan systeme

- **Realisation** : Outil d'automatisation d'**Audit** systeme avec **remonté d'alerte** sur Serveur **Discord**. Scan réalisé a travers un **référentiel** établis. Rapport de Log en sortie **json** de l'ensemble Audité. Automatisation d'execution via **cron**. Monitoring Systeme.

### 📂 [Projets Python Divers](https://github.com/FaramirDev/python-labs)
- **Objectif** : Manipulation de données

- **Realisation** : Ensemble de projet autours de la manipulation et transformation de donnée sous python. 

---
## ---------- Expériences Passées (Ingénierie Systèmes & Workflow) ----------
*Avant de me spécialiser en Admin Sys & Cyber, j'ai piloté des infrastructures techniques pour des productions internationales à haute disponibilité (ex: Studio Miraculous).*

- **Industrialisation & Automatisation** : Conception de frameworks **Python/Bash** permettant l'automatisation de pipelines critiques. Gain d'efficacité opérationnelle de **40%** via la réduction drastique des tâches manuelles et des erreurs humaines.

- **Administration (Renderfarms)** : Optimisation, monitoring et gestion de fermes de calcul distribué. Expertise en gestion de flux de données massifs et en performance système (I/O, CPU/RAM) sous Linux.

- **Leadership Technique & MCO**: Encadrement d'équipes techniques et gestion du Maintien en Condition Opérationnelle (MCO) sous forte pression. Résolution d'incidents critiques en temps réel pour garantir le respect des deadlines de production.
---
## ---------- Veille & Labs ----------
- **Labs** : AWS - TryHackMe & Root-Me. 

- **Communauté** : Veille constante sur les bulletins de l'ANSSI.

---
## ---------- 📫 Me contacter ----------
- **LinkedIn** : [Alexis Rousseau](https://www.linkedin.com/in/alexis-rousseau-admin/)

- **Email** : alexisrousseau.work@proton.me
