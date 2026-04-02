
<!-- Banner (format large) -->
<p align="center">
    <img
        src="assets/banner.jpeg"
        alt="Cybersécurité • Réseaux • Administration Système"
        width="100%"
        style="max-width: 1600px; height: 190px; object-fit: cover; object-position: center; display: block; border-radius: 8px;"
    />
</p>


<h1 align="center">Bienvenue dans mon espace</h1>
<p align="center">
    Développeur orienté cybersécurité, réseaux et administration système — Linux, C/C++, Python.  
    Focus : sécurité offensive/défensive, durcissement système, monitoring réseau et outillage CLI.
</p>

<!-- Badges rapides -->
<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=000" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
</p>

## Projets notables

* [INFO-F201 – Chat IPC & Réseau avec Bot](https://github.com/braad0/Chat-IPC-and-Reseau) — Chat local via pipes nommés + serveur TCP multi-clients.  
  Stack : C, pthreads, sockets, Bash.  
  Points clés : IPC, signaux, threads, scripts automatiques.

* [cybersec-toolkit](https://github.com/braad0/cybersec-toolkit) — Collection d'outils offensifs développés from scratch en Python.
  * [**credaudit**](https://github.com/braad0/cybersec-toolkit/tree/main/cred-audit) — Brute force multi-protocoles (SSH/FTP/HTTP) via sockets raw, zéro dépendance externe, rapports JSON/CSV.
  * [**passwd-audit**](https://github.com/braad0/cybersec-toolkit/tree/main/passwd-audit) — Craqueur de hash hors ligne contre `/etc/shadow`, détection automatique d'algorithme (yescrypt/sha512/bcrypt...), multi-threadé.

  * [**MyThreat-Intel-aggregator**](https://github.com/braad0/MyThreat-Intel-aggregator) — Enrichissement automatique d'IoCs via VirusTotal,     AbuseIPDB et AlienVault OTX.
      Stack : Python, requests, python-dotenv.
      Points clés : détection automatique du type d'IoC, requêtes parallèles, verdict automatique, rapports JSON/CSV.

  * [**DevSecOps-pipeline-secure**](https://github.com/braad0/DevSecOps-pipeline-secure) — Pipeline CI/CD de sécurité automatisé sur une app     Python volontairement vulnérable (OWASP Top 10).
      Stack : GitHub Actions, Bandit, pip-audit, TruffleHog, flake8.
      Points clés : 5 jobs en parallèle, matrice Python 3.10/3.11/3.12, security gates, rapport JSON/Markdown généré automatiquement.

## Stack
* Langages : C, C++, Python, Bash
* Outils : Linux, Git, Make, Docker
* Réseau : Sockets TCP, multithreading, synchro (mutex/sémaphores)
* Sécurité : Brute force, hash cracking, protocoles réseau, audit offensif/défensif

## Stats
![Streak](https://streak-stats.demolab.com?user=braad0&theme=transparent)
![Stats](https://github-readme-stats.vercel.app/api?username=braad0&show_icons=true&theme=transparent)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=braad0&layout=compact&theme=transparent)

## Articles / Notes
* [Comment j'ai construit un chat TCP en C](#)
* [Pipes nommés vs sockets : quel choix ?](#)

