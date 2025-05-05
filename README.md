# 🛡️ **Découverte d'Active Directory Windows Server 2008 R2**

![Banner](image/background.png)

## 📄 **Description**
Ce dépôt contient les ressources pour la découverte et la mise en pratique d'Active Directory sur Windows Server 2008 R2. Vous y trouverez :

Un guide détaillé au format PDF pour l'installation et la configuration d'AD, DNS, DHCP, serveur de fichiers et permissions NTFS.

Ce TP vous permettra de maîtriser la gestion centralisée des comptes, la délégation DNS, l’attribution d’adresses IP via DHCP, la structuration des OU, la gestion des groupes et la sécurisation des partages de fichiers.

---
## 📚 **Fonctionnalités Principales**

- **Déploiement d’une nouvelle forêt et d’un domaine AD via PowerShell ou l’Assistant.**
- **Configuration du rôle DNS pour la résolution interne et la délégation.**
-**Installation et autorisation du service DHCP avec création d’étendues.**
-**Création et organisation d’Unités d’Organisation (OU) pour structurer les objets.**
-**Gestion des groupes de sécurité et des comptes utilisateurs (professeurs, étudiants, administrateurs).**
-**Mise en place d’un serveur de fichiers : DFS, quotas, indexation, partages avancés.**
-**Configuration des autorisations NTFS et partage réseau pour garantir la sécurité.**

## 📂 **Structure du Dépôt**

```
📂 decouverte-packet-tracer/
|
├── 📂 Documents/
│   └── activedirectory.pdf
│
├── 📂 image/
│   └── background.png
|
└── README.md
```
---

## ⚙️ **Prérequis**

- **Windows Server 2008 R2** avec droits administrateur.
  
- Connaissances de base sur les protocoles réseau : 
  - **ICMP**, **TCP**, **DNS**, **DHCP**, **Permissions Windows**.

---

## 🚀 **Mise en Œuvre**

### 1. **Cloner le Dépôt**

```bash
git clone https://github.com/votre_nom_utilisateur/activedirectory.git
cd activedirectory
```

### 2. **Parcourir la Documentation**

Consultez le dossier `documentation/` pour des guides d'analyse détaillés.

---

## 💡 **Bonnes Pratiques**

- **Sauvegardez régulièrement vos configurations** pour éviter toute perte de données.
- **Utilisez des annotations** pour documenter vos topologies réseau.
- **Testez des stratégies de groupes** dans un environnement isolé.
- **Vérifiez les journaux d’événements** pour anticiper les anomalies.

---

## 🌍 **Licence**

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus d'informations.

---

### 🗓 **Date de Création**

Janvier 2025
