# 🖧 TSSR Labs — Karim.A

> Technicien Supérieur Systèmes et Réseaux 

[![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?style=flat&logo=cisco&logoColor=white)](https://www.netacad.com/)
[![Windows Server](https://img.shields.io/badge/Windows%20Server-2025-0078D6?style=flat&logo=windows&logoColor=white)](https://www.microsoft.com/)
[![VMware](https://img.shields.io/badge/VMware-Workstation-607078?style=flat&logo=vmware&logoColor=white)](https://www.vmware.com/)
[![Docker](https://img.shields.io/badge/Docker-labs-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)

---

## 👨‍💻 À propos

Développeur fullstack junior (JavaScript · TypeScript · Symfony · Node.js · Docker) en reconversion vers l'administration systèmes et réseaux.

Ce repo regroupe tous mes **travaux pratiques** réalisés pendant ma formation TSSR : labs réseau sous Packet Tracer, configs Active Directory, Veeam, GLPI, VoIP... chaque dossier = un TP documenté avec schéma et explications.

---

## 🗂️ Structure du repo

```
tssr-labs/
│
├── 📡 packet-tracer/
│   ├── tp-01-metropole-reseau/       ← Schéma réseau entreprise
│   ├── tp-02-vlan/                   ← Segmentation VLAN par service
│   ├── tp-03-ospf/                   ← Routage dynamique OSPF
│   ├── tp-04-acl/                    ← Listes de contrôle d'accès
│   └── tp-05-vpn-ipsec/              ← Tunnel VPN site-à-site
│
├── 🪟 active-directory/
│   ├── tp-01-ad-ds-dhcp-dns/         ← Installation AD DS, DHCP, DNS
│   ├── tp-02-gpo/                    ← Stratégies de groupe (GPO)
│   ├── tp-03-ntfs-partage/           ← Permissions NTFS et partages
│   └── tp-04-profils-itinerants/     ← Profils itinérants
│
├── 💾 veeam/
│   ├── tp-01-backup-windows/         ← Sauvegarde Windows Server
│   └── tp-02-backup-linux/           ← Sauvegarde Debian/Ubuntu
│
├── 🎫 glpi/
│   ├── tp-01-installation/           ← Déploiement GLPI (Docker/LAMP)
│   ├── tp-02-ldap-ad/                ← Intégration LDAP ↔ Active Directory
│   └── tp-03-ticketing/              ← Gestion des incidents
│
└── 📞 voip/
    ├── tp-01-xivo/                   ← IPBX XiVO via Docker
    └── tp-02-freepbx/                ← FreePBX configuration
```

---

## 🧪 Labs réalisés

### 📡 Réseau — Cisco Packet Tracer

| TP | Description | Concepts |
|---|---|---|
| [TP 01](./packet-tracer/tp-01-metropole-reseau/) | Schéma réseau métropole Chantilly | Topologie, câblage, switch/routeur |
| TP 02 | VLANs par département | 802.1Q, trunk, access port |
| TP 03 | Routage OSPF | Protocoles dynamiques, aire 0 |
| TP 04 | ACL | Filtrage, sécurité périmétrique |
| TP 05 | VPN IPSec site-à-site | Chiffrement, tunnel GRE |

### 🪟 Active Directory — Windows Server 2025

| TP | Description | Concepts |
|---|---|---|
| [TP 01](./active-directory/tp-01-ad-ds-dhcp-dns/) | AD DS + DHCP + DNS | Domaine `infotech.lan`, OU, groupes |
| TP 02 | GPO | Stratégies utilisateurs et machines |
| TP 03 | NTFS & Partages | Droits d'accès, héritage |
| TP 04 | Profils itinérants | Redirection de dossiers |

### 💾 Veeam Backup & Replication

| TP | Description |
|---|---|
| [TP 01](./veeam/tp-01-backup-windows/) | Sauvegarde et restauration Windows Server |
| [TP 02](./veeam/tp-02-backup-linux/) | Sauvegarde agent Linux (Debian) |

---

## 🛠️ Stack technique

| Catégorie | Outils |
|---|---|
| **Virtualisation** | VMware Workstation · ESXi (nested) |
| **Réseau** | Cisco Packet Tracer · Switch 2960 · Routeur 1941 |
| **Systèmes** | Windows Server 2025 · Debian · Ubuntu Server |
| **Sauvegarde** | Veeam B&R · Veeam ONE · Clonezilla |
| **ITSM** | GLPI · FusionInventory |
| **VoIP** | XiVO · FreePBX · Cisco CME |
| **Conteneurisation** | Docker · Docker Compose |
| **SSH** | MobaXterm |

---

## 🏗️ Environnement lab

```
Hôte Windows (Ryzen 9 3900X · 32 GB DDR4 · NVMe)
│
├── SRV-DC01  → Windows Server 2025 · AD DS · DHCP · DNS · 192.168.1.10
├── SRV-GLPI  → Debian · GLPI Docker · 192.168.1.20
├── SRV-VEEAM → Windows Server · Veeam B&R + ONE
├── CLT-WIN10 → Windows 10 · joint au domaine infotech.lan
└── CLT-LINUX → Ubuntu Server · cible de sauvegarde
```

Réseau interne : `VMnet1` (Host-Only) `192.168.1.0/24` · Internet : `VMnet8` (NAT)

---

## 📈 Progression

- [x] Schéma réseau entreprise (Packet Tracer)
- [ ] VLANs
- [ ] OSPF
- [ ] ACL
- [ ] VPN IPSec
- [x] Active Directory + DHCP + DNS
- [x] GPO
- [x] Veeam B&R
- [x] GLPI + LDAP
- [ ] VoIP XiVO

---

## 📬 Contact

**Karim Rimk** ·  Administrateur Systèmes & Réseaux · Paris . https://nekodigital.fr/

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Karim%20Rimk-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/karim-a-a23816176/)
[![GitHub](https://img.shields.io/badge/https://github.com/kadev-oclock?style=flat&logo=github)](https://github.com)

> 💡 *Disponible fin juin 2026 — Île-de-France*
