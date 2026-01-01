# 🛡️ Mini-Projets de Cybersécurité

Bienvenue dans ce dépôt GitHub regroupant une série de **mini-projets pratiques en cybersécurité**, réalisés sur environnement local (Linux/VM) dans le cadre d’un apprentissage autodirigé.

Ces projets ont pour but de :
- Mettre en pratique des techniques offensives et défensives
- Mieux comprendre le fonctionnement des outils réseau/sécurité
- Simuler des scénarios réels d'attaque et de détection

---

##  Contenu du dépôt

Chaque dossier contient un rapport complet au format Markdown ou Word, avec captures d’écran, explications des commandes et résultats observés.

| Projet | Description |
|--------|-------------|
|  **Bruteforce avec Hydra** | Attaque par force brute sur un formulaire web DVWA, analyse réseau + logs Apache. |
|  **HTTP Flood local** | Génération de trafic massif avec ab pour observer saturation réseau (iftop, nethogs, glances). |
|  **Scan de vulnérabilités avec Nikto** | Analyse de surface d’attaque du serveur web local, interprétation des failles et headers manquants. |
|  **IDS simple avec Scapy** | Système de détection d’intrusion via sniffing ICMP/TCP : detection SYN, FIN, XMAS, Null scan, ICMP Flood. |
|  **Mini-Honeypot + Analyse d’évènements** | Déploiement d'un faux service attractif + observation/sauvegarde des événements suspects générés. |
| **Analyse de la censure DNS par pays** | Requêtes DNS manuelles avec `dig` sur des serveurs de différents pays pour observer la censure ou les anomalies de résolution. |
|  **Audit de sécurité d’une image Docker** | Scan d’une image locale avec Trivy (CVE) et Dockle (bonnes pratiques Docker), dans une logique DevSecOps. |
|  **Déploiement sécurisé avec Ansible** | Playbook Ansible pour installer Apache, désactiver des services inutiles, configurer UFW et créer un utilisateur non-root : automatisation DevSecOps. |
---

##  Outils utilisés

- `Hydra`, `Nikto`, `Nmap`, `WhatWeb`, `Glances`, `Iftop`, `Nethogs`
- `Python + Scapy`
- `iptables`, `curl`, `tail`, `Apache2`, `DVWA`
- Systèmes : Ubuntu 22.04 (VM ou WSL)

---

##  Objectifs pédagogiques

- Comprendre le fonctionnement des attaques courantes (bruteforce, scan, DoS)
- Apprendre à détecter et analyser les effets de ces attaques
- Maîtriser les outils de sécurité et d’administration réseau
- Développer de bonnes pratiques de documentation technique

---

##  Licence

Ces projets sont réalisés à des fins éducatives et n'ont pas vocation à être utilisés en environnement de production.


---

