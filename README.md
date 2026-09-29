<h1 align="center">Ethan Joets</h1>
<h3 align="center">Étudiant Master Cyber-Défense & Sécurité de l'Information · UPHF Valenciennes</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/ethan-joets"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ethanj010304@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Recherche-Alternance%20Cybersécurité%20Sept.%202026-1A5276?style=flat-square&labelColor=1A5276&color=2E86C1" alt="Alternance"/>
  <img src="https://img.shields.io/badge/Zone-Valenciennes%20%2F%20Lille-2E7D32?style=flat-square" alt="Zone"/>
  <img src="https://img.shields.io/badge/Focus-Sécurité%20×%20IA%20×%20Systèmes-6C3483?style=flat-square" alt="Focus"/>
</p>

---

## 🧑‍💻 À propos

Étudiant en **Master Cyber-Défense & Sécurité de l'Information** (UPHF, Valenciennes), je travaille à l'intersection de la **sécurité offensive/défensive**, du **développement sécurisé** (Go, Rust, Python) et de l'**IA appliquée à la sécurité**.

- 🛡️ **Blue & Red team** — j'aime autant construire des détections que comprendre comment on les contourne.
- 🤖 **IA × Sécurité** — j'explore l'usage des LLM locaux pour outiller le pentest et l'analyse (projet **ARIA**), et le *federated learning* sécurisé pour la santé (projet **FedSecHealth**).
- 🔐 **Dev sécurisé** — stage chez **L&Smart (Anzin)** : coffre-fort cryptographique en Go, déploiement de honeypots, simulation d'environnements IoT pour tester la sécurité réseau.

Je pratique régulièrement sur **HackTheBox** et **TryHackMe**, et je documente mes apprentissages ici.

> 🎯 **Je recherche une alternance de 2 ans en cybersécurité à partir de septembre 2026** — SOC, pentest, DevSecOps, GRC ou Cloud Security. Zone Valenciennes / Lille. Ouvert à tout échange.

---

## 🔧 Stack technique

**Sécurité**
![Wazuh](https://img.shields.io/badge/Wazuh-3665D3?style=flat-square&logo=wazuh&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=flat-square)
![Metasploit](https://img.shields.io/badge/Metasploit-2A2E3B?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT&CK-C1272D?style=flat-square)
![Vault](https://img.shields.io/badge/HashiCorp_Vault-000000?style=flat-square&logo=vault&logoColor=white)

**Développement**
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Cloud & DevSecOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)

**Réseaux & Systèmes**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)
![GNS3](https://img.shields.io/badge/GNS3-00A98F?style=flat-square)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)

---

## 📂 Projets

> Chaque projet répond à : *quel problème il règle · comment il marche · quels résultats · ce que j'en ai appris.*

### 🤖 ARIA — Assistant de pentest assisté par IA locale
Assistant qui orchestre des outils de reconnaissance et d'exploitation en **lab**, piloté par un **LLM local** (aucune donnée envoyée à un tiers). Génère un rapport structuré à la fin d'une session.
`Python` · `Ollama / llama.cpp` · `Docker` · **usage éthique — environnements de test uniquement**

### 🔐 FedSecHealth — Federated Learning sécurisé pour la santé
Entraînement collaboratif de modèles sans partage des données patients. Étude d'attaques (poisoning, inférence) et de défenses (agrégation robuste, differential privacy).
`Python` · `PyTorch` · `Flower`

### 🗝️ Coffre-fort cryptographique — Go / HashiCorp Vault
Stockage sécurisé avec chiffrement **AES-256**, système de fichiers chiffré monté de façon transparente via **FUSE**, authentification multi-utilisateurs et droits granulaires via Vault.
`Go` · `HashiCorp Vault` · `FUSE` · `Linux`

### 🛡️ Lab SOC — Wazuh SIEM
SOC personnel pour la détection d'intrusions : Wazuh manager + agents (Linux/Windows), règles d'alerte custom, dashboards, mapping **MITRE ATT&CK**.
`Wazuh` · `VirtualBox` · `Ubuntu` · `Windows`

### 🔄 Pipeline DevSecOps
CI/CD sécurisé avec scan à chaque push : vulnérabilités containers (**Trivy**), SAST (**Bandit**), détection de secrets (**Gitleaks**).
`GitHub Actions` · `Docker` · `Trivy` · `Bandit` · `Gitleaks`

### 🌐 Infrastructure réseau segmentée
Architecture virtualisée : segmentation VLAN, DMZ, firewall **OPNsense**, routage Cisco, VPN site-à-site.
`GNS3` · `OPNsense` · `Cisco IOS`

### 🎯 Writeups CTF
Machines HackTheBox / TryHackMe résolues : reconnaissance → énumération → exploitation → privesc → leçons apprises.

---

## 🎓 Certifications

| Certification | Organisme | Statut |
|---|---|---|
| Introduction to Cybersecurity | Cisco | ✅ Obtenue |
| EUNICE Cybersecurity | Programme européen | ✅ Obtenue |

---

## 📊 Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tag59&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tag59&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>

---

## 📫 Me contacter

Activement à la recherche d'une **alternance en cybersécurité (2 ans, sept. 2026)** — Valenciennes / Lille.

- 📧 **Email** : ethanj010304@gmail.com
- 💼 **LinkedIn** : [linkedin.com/in/ethan-joets](https://www.linkedin.com/in/ethan-joets)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Tag59&color=1A5276&style=flat-square&label=Visiteurs" alt="Profile views"/>
</p>
