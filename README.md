## Déploiement d'un proxy Squid sur OPNsense

### 🦑 Présentation du projet

Ce projet présente la mise en place d'un **proxy web Squid** sur un pare-feu **OPNsense** afin de centraliser et contrôler l'accès Internet d'un réseau local.  

L'objectif est de déployer un **forward proxy explicite**, couramment utilisé en entreprise pour filtrer la navigation web, contrôler l'accès à certains sites et améliorer la sécurité du réseau.  
Le proxy est configuré pour écouter les requêtes provenant du réseau LAN et permet d'appliquer différentes règles de contrôle d'accès grâce à l'utilisation d'**ACL (Access Control Lists)**.  

Le projet inclut également la configuration des **règles de pare-feu nécessaires** ainsi que le **déploiement automatique du proxy via une GPO Active Directory**, permettant d'appliquer la configuration proxy à l'ensemble des postes du domaine.  

### Objectifs du projet

- Comprendre le fonctionnement d'un **forward proxy**  
- Déployer et configurer un proxy web  
- Gérer les accès via des **ACL**  
- Mettre en place des règles de filtrage web  
- Intégrer un service réseau dans une infrastructure Active Directory  
- Automatiser la configuration des postes clients via **Group Policy**  

### Compétences mises en pratique

Ce projet m'a permis de travailler sur plusieurs aspects de l'administration système et réseau :  

- Administration d'un pare-feu **OPNsense**  
- Déploiement et configuration de **Squid Proxy**  
- Gestion du trafic HTTP et HTTPS  
- Mise en place de **listes de contrôle d'accès (ACL)**  
- Configuration de règles **Firewall**  
- Déploiement de paramètres réseau via **GPO**  

### Contexte

Ce projet fait partie de mon **portfolio en administration système, réseau et cybersécurité** et a pour objectif de démontrer ma capacité à déployer et intégrer un service réseau dans un environnement
d'entreprise.
