---
title: "Fondamentaux : Linux, réseau, bases (ne pas skip)"
description: "Avant le pentest style film, il faut des bases solides — et un choix d’OS assumé. Voici mon socle."
category: Étape 01
reading_time: 8
---

Avant le “pentest style Hollywood”, il faut des bases solides.

## Informatique générale

- Comment marche un OS (processus, fichiers, utilisateurs, permissions)
- Différence client / serveur
- HTTP basique (requête, réponse, cookies, sessions)

**Objectif :** lire une doc technique sans paniquer.

## Choix du système : pourquoi j’ai pris Parrot OS

Beaucoup commencent directement sur **Kali Linux** — et c’est très bien.  
Moi, j’ai choisi **Parrot OS** pour être un peu **différent**, et surtout parce que ça colle mieux à ma façon de travailler au quotidien.

### Pourquoi Parrot (mon choix)

- **Usage quotidien possible** : plus pensé pour bosser / apprendre sans vivre uniquement en “mode attaque”
- **Légèreté** : souvent plus confortable sur des machines modestes
- **Éthique & privacy** : orientation claire sécurité / anonymat / posture responsable
- **Outils cyber déjà là** : pentest, forensics, OSINT… sans tout installer à la main
- **Base Debian** : même écosystème stable que beaucoup de distros pro
- **Se démarquer** : en junior, montrer que tu as **choisi** ton environnement (et que tu sais pourquoi) > suivre le troupeau sans réfléchir

### Par rapport aux autres (sans “guerre de distros”)

| Système | Points forts | Limite fréquente |
|---------|--------------|------------------|
| **Parrot OS** | Équilibre lab + quotidien, privacy, outils inclus | Moins “star” que Kali en entreprise |
| **Kali Linux** | Standard pentest très connu, énorme communauté | Plus “outil d’audit” que desktop du quotidien |
| **Ubuntu / Debian vanilla** | Stable, simple pour apprendre Linux | Il faut installer/configurer la stack sécu soi-même |
| **Windows seul** | Logiciels courants | Moins naturel pour le tooling pentest classique |

> Peu importe la distro : ce qui compte, c’est que tu **maîtrises Linux**.  
> Parrot, c’est mon terrain de jeu — Kali reste excellent, Ubuntu aussi pour apprendre.

## Linux (obligatoire)

Sur Parrot / Kali / Debian / Ubuntu :

- Terminal au quotidien
- `ls`, `cd`, `grep`, `find`, `chmod`, `ps`, `ss`/`netstat`
- Utilisateurs, sudo, services
- Lire des logs

**Exercice :** administre ta propre machine. Casse, répare, recommence.

## Réseau

- IP, MAC, DNS, DHCP
- TCP vs UDP
- Ports courants (22, 80, 443, 445…)
- Modèle simplifié : “paquet → service → appli”

## Programmation (minimum utile)

- Lire du **Python** / **Bash**
- Comprendre un peu de **JavaScript** (web)
- Savoir lire une requête HTTP et un JSON

## Checklist

- [ ] J’ai choisi mon OS et je sais **pourquoi** (ex. Parrot)  
- [ ] À l’aise en terminal Linux  
- [ ] Je comprends IP / DNS / HTTP  
- [ ] Je peux expliquer GET/POST  
- [ ] Je sais lire une erreur sans abandonner  
