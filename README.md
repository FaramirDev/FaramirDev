# Systèmes, Réseaux & Infrastructures | Automatisation & Cybersécurité

<p align="left">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=for-the-badge&logo=microsoft&logoColor=white" alt="Windows Server" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Cisco-175BA0?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <br />
  
  <a href="https://www.linkedin.com/in/alexis-rousseau-admin/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

## ---------- À propos ---------

Administrateur Systèmes & Infrastructures avec 5 ans d'expérience en environnements critiques, je dédie aujourd'hui mon savoir-faire à l'administration et à la sécurisation des infrastructures SI.

Spécialiste du **durcissement (Hardening)** et de la **défense réseau** (Stormshield, Cisco, VPN), je maîtrise **l'IaC et l'automatisation** (Ansible, Python, Terraform) pour assurer le Maintien en Condition Opérationnelle (MCO), la conformité et la gestion des accès selon les principes **Zero Trust** et du **moindre privilège**.

Mon parcours de 5 ans en tant que **Lead Technique/DevOps** dans l'industrie du VFX m'a apporté une grande rigueur opérationnelle. C'est au contact d'environnements exigeants, où la confidentialité des données est une priorité absolue, que j'ai développé un vif intérêt pour l'architecture système. Ma force réside dans ma capacité à coupler une forte culture du développement logiciel avec une gestion rigoureuse des infrastructures de production.

**Valeur ajoutée :** Résolution d'incidents critiques (L2/L3), déploiement de parcs hétérogènes (Linux/Windows), et développement d'outils de sécurité sur mesure.

---

## ---------- Expertise Techniques ----------

| Domaine                    | Technologies maitrisées                                                       |
|----------------------------|-------------------------------------------------------------------------------|
| **Systemes & Cloud**       | Linux (Debian/RH), Windows Server (AD/GPO), Azure/AWS, Docker, VMware         |
| **Réseaux & Security**     | Architecture Cisco (VLAN, OSPF), IPv4/IPv6, VPN (IPsec/SSL), Stormshield, Audit ANSSI    |
| **Automatisation & Dev**   | Python, Ansible (IaC), Bash, PowerShell, Git, SQL                    |
| **Supervision & Ops**      | Nagios, GLPI, CrowdSec, Wireshark, Nginx                                      |

---

## ---------- Focus Projet : Sécurité Défensive & Développement Cyber ----------

### 🛡️ [Projet Sentinel SIEM & HIDS](https://github.com/FaramirDev/projet-sentinel-siem-hids) - Solution unifiée d'analyse d'événements et de gestion de la sécurité

**Objectif :** Développer une solution légère et modulaire pour centraliser la visibilité de la sécurité d'un hôte Linux, automatiser l'analyse des vulnérabilités locales/réseau et bloquer activement les menaces en temps réel.

**Architecture du projet :**
Le **projet Sentinel SIEM** est l'aboutissement d'une suite de briques logicielles indépendantes regroupées au sein d'une application web de monitoring.

* **📂 [Module 1 -Sentinel-Health (Audit Système)](https://github.com/FaramirDev/Projet-Audit-Health-Shield-Linux) :** Audit de santé système avec exécution périodique (Cron), détection des écarts de configuration selon un référentiel de sécurité et alertes Discord en cas d'anomalies.

* **📂 [Module 2 - Sentinel-NetPulse (Scan & Cartographie)](https://github.com/FaramirDev/Projet-Audit-Network-Scanner-Linux) :** Outil de reconnaissance réseau pour identifier les hôtes actifs, cartographier les ports ouverts et analyser les bannières de services. Génération de rapports au format JSON.

* **📂 [Module 3 - Sentinel-Defender (HIDS Daemon)](https://github.com/FaramirDev/Projet-Defender-Sentinel-Log-HIDS-Linux) :** Daemon Service d'arrière-plan analysant les logs d'authentification (SSH), appliquant un bannissement dynamique des adresses IP malveillantes via `iptables` (IPS) et transmettant les alertes en temps réel.

* **📂 [Module 4. Sentinel SIEM & HIDS ( Centralisation & UI)](https://github.com/FaramirDev/projet-sentinel-siem-hids) :** Interface web développée sous Python (Streamlit) permettant la visualisation des métriques de sécurité, la centralisation des logs d'audit et la remédiation rapide des incidents.

**Stack technique :** Python 3, Streamlit, Linux Security, Daemons, Cron, API Discord, JSON.

<img src="captures/demo_sentinel.gif" width="800" alt="Dashboard Sentinel">

---

## ---------- Réalisations Techniques & Projets d'Infrastructure ----------

Sélection de projets d'infrastructure et de sécurité simulant des environnements de production réels.

### ☁️ Infrastructures Cloud & Systèmes Hybrides

* **📂 [Projet Architecture Cloud & Migration Haute Disponibilité](https://github.com/FaramirDev/projet-migration-cloud-nimbus)**
    * ***Réalisations :*** Conception et déploiement d'une infrastructure résiliente sur AWS (VPC, Subnets, Security Groups, ECS Fargate, RDS, S3, IAM, WAF).

    * *Stack :* AWS, IAM, Security Groups, Supervision.

* **📂 [Projet d'Industrialisation Ansible - Parc Hybride & Stratégie de Backup](https://github.com/FaramirDev/projet-ansible-hybrid-parc-automatisation)**
    * ***Réalisations :*** Automatisation de la configuration d'un parc mixte (Windows/Linux), audit de sécurité, politique de sauvegarde 3-2-1 avec Veeam et chiffrement des données.

    * *Stack :* Ansible, Python, PowerShell, Active Directory, Veeam.

### 🌐 Réseaux & Interconnexions Critiques

* **📂 [Projet Conception d'un Backbone Réseau Multi-sites](https://github.com/FaramirDev/projet-cisco-architecture-network-secure)**
    * ***Réalisations :*** Routage dynamique OSPF, redondance de passerelle (HSRP), agrégation de liens (EtherChannel) et segmentation fine par VLAN.

    * *Stack :* Cisco IOS, Routage L3, Switching L2, IPv4.

* **📂 [Projet d'Accès Distant Sécurisé & Intégration de Nouvelles Entités](https://github.com/FaramirDev/projet-vpn-stormshield-ad-security)**
    * ***Réalisations :*** Raccordement de sites distants via pare-feu Stormshield, tunnels VPN IPsec / SSL et extension Active Directory (RODC).

    * *Stack :* Stormshield SNS, VPN IPsec/SSL, Windows Server, AD DS.

* **📂 [Projet d'Ingénierie de Migration vers IPv6](https://github.com/FaramirDev/projet-ipv6-migration-dualstack)**
    * ***Réalisations*** : Déploiement en Dual-Stack, configuration des protocoles de routage IPv6 et sécurisation du voisinage réseau.

    * *Stack :* IPv6, Cisco IOS.

### 🛡️ Cybersécurité & Durcissement (Hardening)
* **📂 [Projet Sécurisation d'Infrastructures Web - Wordpress](https://github.com/FaramirDev/projet-web-infrastructure-wordpress-security)**
    * ***Réalisations*** : Hardening de serveurs Nginx/Apache, authentification centralisée via LDAP et chiffrement TLS.

    * *Stack* : Linux, Nginx, LDAP, SSL/TLS, MySQL.

* **📂 [Projet Sécurisation & Durcissement d'Infrastructures Web (CrowdSec)](https://github.com/FaramirDev/projet-web-infrastructure-security-crowdsec)**
    * ***Réalisations*** : Hardening de serveurs Nginx/Apache, implémentation d'un IPS/IDS avec CrowdSec/Fail2ban, authentification centralisée via LDAP et chiffrement TLS.

    * *Stack :* Linux, Nginx, LDAP, CrowdSec, SSL/TLS.

* **📂 [Projet d'Audit & Organisation d'un Réseau Local](https://github.com/FaramirDev/projet-lan-design-technical-documentation)**
    * ***Réalisations*** : Création du Document d'Architecture Technique (DAT), schématisation logique/physique et mise en place des services réseau (DHCP/DNS).

    * *Stack :* Méthodologie d'audit, Visio/Draw.io, TCP/IP.

---

## ---------- Expériences Passées (Expertise Ops & Automatisation) ----------

Avant de me spécialiser en Administration Système & Cybersécurité, j'ai évolué pendant 5 ans dans des environnements de production VFX exigeants à haute disponibilité (ex: Studio Miraculous).

* **Automatisation & CI/CD :** Conception de frameworks Python/Bash pour l'industrialisation de pipelines critiques. Réduction des erreurs humaines et gain d'efficacité opérationnelle de 40%.

* **Gestion d'Infrastructure & MCO :** Optimisation, monitoring et gestion de fermes de calcul distribué (Renderfarms). Gestion de flux de données massifs et de la performance système (I/O, CPU/RAM) sous Linux.

* **Résolution d'Incidents (L2/L3) :** Maintien en Condition Opérationnelle (MCO) sous forte pression et gestion des accès sécurisés pour des équipes de production internationales.

---
## ---------- Me contacter ----------
- **LinkedIn** : [Alexis Rousseau](https://www.linkedin.com/in/alexis-rousseau-admin/)

- **Email** : alexisrousseau.work@proton.me
