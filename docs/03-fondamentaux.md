# 03 — Fondamentaux (ne pas skip)

Avant le “pentest style Hollywood”, il faut des bases solides.

> Avant : [choix du système](01-choix-systeme.md) et [Bandit](02-maitrise-linux-bandit.md).

## 1) Informatique générale

- Comment marche un OS (processus, fichiers, utilisateurs, permissions)
- Différence client / serveur
- HTTP basique (requête, réponse, cookies, sessions)

**Objectif :** lire une doc technique sans paniquer.

## 2) Linux (obligatoire)

Sur Parrot / Kali / Debian / Ubuntu :

- Terminal au quotidien
- `ls`, `cd`, `grep`, `find`, `chmod`, `ps`, `ss`/`netstat`
- Utilisateurs, sudo, services
- Lire des logs

**Exercice :** administre ta propre machine. Casse, répare, recommence.

## 3) Réseau

- IP, MAC, DNS, DHCP
- TCP vs UDP
- Ports courants (22, 80, 443, 445…)
- Modèle simplifié : “paquet → service → appli”

**Outils d’apprentissage :** Wireshark (observer), labs Cisco Packet Tracer / docs réseau.

## 4) Programmation (minimum utile)

Pas besoin d’être dev senior, mais :

- Lire du **Python** / **Bash**
- Comprendre un peu de **JavaScript** (web)
- Savoir lire une requête HTTP et un JSON

**Exercice :** petit script qui parse un fichier de ports ou un export Burp.

## Checklist étape 02

- [ ] Je suis à l’aise en terminal Linux
- [ ] Je comprends IP / DNS / HTTP
- [ ] Je peux expliquer une requête GET/POST
- [ ] Je sais lire un message d’erreur sans abandonner
