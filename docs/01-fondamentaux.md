# 01 — Fondamentaux (ne pas skip)

Avant le “pentest style Hollywood”, il faut des bases solides.

## 1) Informatique générale

- Comment marche un OS (processus, fichiers, utilisateurs, permissions)
- Différence client / serveur
- HTTP basique (requête, réponse, cookies, sessions)

**Objectif :** lire une doc technique sans paniquer.

## 2) Choix du système : pourquoi j’ai pris Parrot OS

Beaucoup commencent sur **Kali Linux** — c’est très bien.  
Moi, j’ai choisi **Parrot OS** pour être un peu **différent**, et parce que ça colle mieux à un usage quotidien + labs.

### Avantages de Parrot (pour moi)

- Usage quotidien plus confortable qu’une distro “100 % offensive”
- Souvent plus léger sur des machines modestes
- Forte orientation privacy / posture éthique
- Outils cyber déjà présents (pentest, forensics, OSINT…)
- Base Debian (écosystème stable)
- Un choix assumé : en junior, savoir **expliquer pourquoi** ton OS > suivre la mode sans réfléchir

### Comparaison rapide

| Système | Points forts | Limite fréquente |
|---------|--------------|------------------|
| **Parrot OS** | Équilibre lab + quotidien, privacy, outils inclus | Moins “standard corporate” que Kali |
| **Kali Linux** | Référence pentest, grosse communauté | Moins pensé comme desktop du quotidien |
| **Ubuntu / Debian** | Idéal pour apprendre Linux proprement | Stack sécu à installer soi-même |
| **Windows seul** | Logiciels du quotidien | Moins naturel pour le tooling pentest |

> La distro n’est pas une identité. **Linux + méthode**, oui.

## 3) Linux (obligatoire)

Sur Parrot / Kali / Debian / Ubuntu :

- Terminal au quotidien
- `ls`, `cd`, `grep`, `find`, `chmod`, `ps`, `ss`/`netstat`
- Utilisateurs, sudo, services
- Lire des logs

**Exercice :** administre ta propre machine. Casse, répare, recommence.

## 4) Réseau

- IP, MAC, DNS, DHCP
- TCP vs UDP
- Ports courants (22, 80, 443, 445…)
- Modèle simplifié : “paquet → service → appli”

**Outils d’apprentissage :** Wireshark (observer), labs Cisco Packet Tracer / docs réseau.

## 5) Programmation (minimum utile)

Pas besoin d’être dev senior, mais :

- Lire du **Python** / **Bash**
- Comprendre un peu de **JavaScript** (web)
- Savoir lire une requête HTTP et un JSON

**Exercice :** petit script qui parse un fichier de ports ou un export Burp.

## Checklist étape 01

- [ ] J’ai choisi mon OS et je sais **pourquoi** (ex. Parrot)
- [ ] Je suis à l’aise en terminal Linux
- [ ] Je comprends IP / DNS / HTTP
- [ ] Je peux expliquer une requête GET/POST
- [ ] Je sais lire un message d’erreur sans abandonner
