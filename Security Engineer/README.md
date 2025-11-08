# Security Engineer
<img width="230" alt="image" src="https://github.com/user-attachments/assets/d9e47916-ad6a-4e6b-bddc-358740ba1423" />

## Description
J'ai complété le module **Security Engineer** sur TryHackMe pour acquérir les compétences nécessaires à la conception, l'évaluation et la protection d'infrastructures, de systèmes et d'applications. Ce parcours m'a permis de comprendre l'ingénierie de la sécurité sous plusieurs angles : architecture sécurisée, durcissement, gestion des risques, sécurité logicielle et réponse aux incidents. L'objectif est d'être capable d'identifier proactivement les risques, de proposer des mesures techniques et organisationnelles et d'intervenir comme premier répondant en cas d'incident.

---

## Contenu du module
<img width="170"  alt="image" src="https://github.com/user-attachments/assets/7f881358-c072-4e5f-a439-88420db4782d" />

### 1. Introduction à l'ingénierie de la sécurité
- **Security Engineer Intro** : panorama des missions et du rôle d'ingénieur sécurité en entreprise.  
- **Security Principles** : principes fondamentaux (sécurité par défaut, principe du moindre privilège, défense en profondeur).  
- **Introduction to Cryptography** : rappels sur chiffrement symétrique/asymétrique, certificats, PKI et signatures.  
- **Identity and Access Management** : gestion des identités, authentification, autorisation, MFA et lifecycle des comptes.

Ces éléments posent les bases pour concevoir des systèmes sécurisés et établir des politiques d'accès robustes.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/c69e7968-db62-4cd3-91f2-739a18c55675" />

### 2. Menaces et gestion des risques
- **Governance & Regulation** : compréhension des exigences réglementaires, normes et rôles GRC.  
- **Threat Modelling** : techniques de modélisation des menaces (STRIDE, DREAD, attaque surface analysis) pour prioriser les mitigations.  
- **Risk Management** : identification, évaluation et traitement des risques (accept, mitigate, transfer, avoid).  
- **Vulnerability Management** : cycle de vie des vulnérabilités : discovery, triage, patching, exceptions et reporting.

J'ai appris à traduire les risques techniques en décisions business et à structurer des programmes de remédiation.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/cb3f5a2a-7796-48c9-80f7-b719edd9bdd7" />

### 3. Sécurité réseau et système
- **Secure Network Architecture** : segmentation, micro-segmentation, zones de sécurité, firewalling et conception défensive.  
- **Linux System Hardening** : durcissement (sysctl, permissions, services minimaux, mise à jour automatique, audit).  
- **Microsoft Windows Hardening** : GPO, sécurité des comptes, baselines Windows et surveillance.  
- **Active Directory Hardening** : contrôleurs de domaine, délégations, protections contre l'élévation de privilèges et abus d'AD.  
- **Network Device Hardening** : sécurisation des équipements (switches, routeurs, VPN concentrators).  
- **Network Security Protocols** : TLS, IPsec, 802.1x, sécurisation des canaux.  
- **Virtualization and Containers** : séparation des tenants, best practices pour VM et conteneurs, surface d'attaque Docker/Kubernetes.  
- **Intro to Cloud Security** : modèles de responsabilité partagée, IAM cloud, chiffrement, logging et cloud-native controls.  
- **Auditing and Monitoring** : logs essentiels, collecte centralisée, alerting et métriques de sécurité.

Ces labs m'ont permis d'appliquer des mesures concrètes de durcissement et de concevoir des architectures résilientes.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/7663ff5d-418d-49e9-9e4a-4d972365b7c7" />

### 4. Sécurité logicielle
- **OWASP Top 10 / API Security** : compréhension et remédiation des vulnérabilités web et API (injections, auth flaws, etc.).  
- **SSDLC** : intégrer la sécurité dans le cycle de développement (politiques, gates, revues).  
- **SAST / DAST** : scan statique et dynamique, triage des résultats et intégration dans CI.  
- **Weaponizing Vulnerabilities** : comprendre l'impact des vulnérabilités pour mieux prioriser les correctifs.  
- **Introduction to DevSecOps** : shift-left, tests automatiques, secrets management et pipelines sécurisés.  
- Labs spécifiques (Mother's Secret, Traverse) : exercices pratiques sur sécurisation et test d'environnements.

J'ai développé une approche pragmatique pour réduire la dette de sécurité applicative et automatiser la gouvernance du code.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/3b21e5c8-5605-48bb-a1df-48ce554ecc5f" />

### 5. Gestion des incidents
- **Intro to IR and IM** : rôles, playbooks et phases d'une réponse aux incidents.  
- **Logging for Accountability** : définition des logs critiques, rétention, traçabilité et preuves.  
- **Becoming a First Responder** : tâches du premier intervenant : containment, collecte d'artefacts, escalation.  
- **Cyber Crisis Management** : coordination, communication, gestion de crise et interactions avec les équipes légales/communication.

J'ai appris à construire des runbooks opérationnels et à exécuter des premières étapes d'investigation et de confinement.

---

## Travaux pratiques et laboratoires
- Durcissement d'instances Linux et Windows via checklist et GPO.  
- Architecture réseau sécurisée et segmentation de zones.  
- Scans SAST/DAST sur applications d'exemple, triage et remédiation.  
- Scénarios de threat modelling et exercices de gestion des risques.  
- Simulations IR : collecte d'artefacts, logs, snapshots et génération de rapports d'incident.  
- Intégration de contrôles DevSecOps dans pipelines CI/CD (exemples de checks SAST, secrets scanning).

Ces travaux m'ont apporté de l'expérience concrète dans la conception et l'opération d'environnements sécurisés.

---

## Compétences clés acquises
- Conception d'architectures réseau et systèmes sécurisées.  
- Durcissement Windows, Linux et Active Directory.  
- Mise en place et gouvernance de pipelines DevSecOps sécurisés (SAST/DAST, secrets).  
- Modélisation des menaces et gestion des risques.  
- Développement et exécution de playbooks d'incident et première réponse.  
- Compréhension opérationnelle des contrôles cloud et des dispositifs de monitoring.

---

## Outils et technologies utilisés
`GPO` · `SAST/DAST tools` · `Docker` · `Kubernetes (intro)` · `Nmap` · `Burp Suite` · `Wireshark` · `PowerShell` · `Bash` · `ELK` · `Wazuh` · `Sysmon` · `Cloud IAM concepts`

---

## Certificat
[Voir le certificat Security Engineer](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-RABDLXREIO.pdf)

---

