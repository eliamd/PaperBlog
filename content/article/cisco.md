---
title: "Bulletin d'Alerte du CERT-FR : Multiples Vulnérabilités dans Cisco IOS XE"
date: 2023-11-22
draft: false
author: ["Eliam"]
images:
- https://kentindell.github.io/assets/images/detective-story/device2.jpg
---

## Bulletin d'Alerte du CERT-FR

Le CERT-FR a publié un bulletin alertant de vulnérabilités dans Cisco IOS XE, un système d'exploitation pour réseaux. Ces vulnérabilités permettent :

- Contournement des politiques de sécurité
- Exécution de code à distance
- Élévation de privilèges

Des correctifs sont disponibles pour certaines versions, mais pas toutes. En attendant, il est conseillé de désactiver l'interface Web de gestion. Les informations détaillées et les recommandations sont disponibles dans les bulletins de sécurité de Cisco et du CERT-FR.


### Gestion du Document
- **Référence :** CERTFR-2023-ALE-011
- **Titre :** [MàJ] Multiples vulnérabilités dans Cisco IOS XE
- **Date de la première version :** 17 octobre 2023
- **Date de la dernière version :** 02 novembre 2023
- **Source(s) :** Bulletin de sécurité Cisco cisco-sa-iosxe-webui-privesc-j22SaA4z du 16 octobre 2023
- **Pièce(s) jointe(s) :** Aucune(s)

### Risque(s)
- Contournement de la politique de sécurité
- Exécution de code arbitraire à distance
- Élévation de privilèges

### Systèmes Affectés
- Cisco IOS XE si l'interface Web de gestion est accessible
- Versions affectées : IOS XE versions 17.9.x antérieures à 17.9.4a, 17.6.x antérieures à 17.6.6a, et autres spécifiées

### Résumé des Mises à Jour
- **17.3.8a disponible (Mise à jour du 02 novembre 2023)**
- **Détails techniques de la CVE-2023-20198 disponibles (Mise à jour du 31 octobre 2023)**
- **Versions 17.6.6a et 16.12.10a disponibles (Mise à jour du 30 octobre 2023)**
- **Ajout de la vulnérabilité CVE-2023-20273 (Mise à jour du 23 octobre 2023)**

### Contournement Provisoire
En attendant les correctifs, Cisco recommande de désactiver l'interface webui et de s'assurer que les interfaces de gestion soient accessibles uniquement depuis un réseau d'administration sécurisé.

### Solution
Se référer au bulletin de sécurité de l'éditeur pour l'obtention des correctifs.

### Documentation
- [Bulletin de sécurité Cisco](https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-iosxe-webui-privesc-j22SaA4z)
- [Avis CERT-FR CERTFR-2023-AVI-0878](https://www.cert.ssi.gouv.fr/avis/CERTFR-2023-AVI-0878/)
- [Recommandations de l'ANSSI](https://www.ssi.gouv.fr/uploads/2018/04/anssi-guide-admin_securisee_si_v3-0.pdf)
- [Référence CVE CVE-2023-20198](https://www.cve.org/CVERecord?id=CVE-2023-20198)
- [Référence CVE CVE-2023-20273](https://www.cve.org/CVERecord?id=CVE-2023-20273)

### Gestion Détaillée du Document
- **17 octobre 2023 :** Version initiale
- **30 octobre 2023 :** Disponibilité des versions 17.6.6a et 16.12.10a
- **31 octobre 2023 :** POC disponible publiquement
- **02 novembre 2023 :** Mise à jour finale
