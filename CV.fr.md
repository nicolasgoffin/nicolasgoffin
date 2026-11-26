# Nicolas Goffin

**Administrateur système & réseau — orienté Linux**

📍 Liège, Belgique · 🔗 [LinkedIn](https://be.linkedin.com/in/goffinnicolas) · 🐙 [GitHub](https://github.com/nicolasgoffin) · 🇬🇧 [English version](CV.en.md)

---

## `$ whoami`

```text
nicolas — sysadmin qui construit, casse et documente sa propre infrastructure.
```

Je suis administrateur système et réseau, avec une forte orientation Linux. J'ai commencé par le réseau et la virtualisation (Cisco, Juniper, VMware, Hyper-V, Windows Server). Aujourd'hui, je gère seul ma propre infrastructure Linux en production : pare-feu, DNS chiffré, messagerie, services de fichiers, supervision et packaging.

J'apprends en pratiquant et je documente tout ce que j'apprends. J'ai aussi été formateur, et c'est une activité que je veux reprendre : rendre Linux et le réseau accessibles à celles et ceux qui débutent.

---

## `$ ls -R ~/competences`

### 🐧 Linux

#### Distributions

`#Fedora` `#RHEL` `#Debian` `#Ubuntu` `#Kali` `#Kicksecure` `#NixOS`

#### Système

`#systemd` `#SELinux` `#Bash` `#LVM` `#ext4` `#quotas` `#journald`

#### Réseau

`#Netplan` `#nftables` `#firewalld` `#iptables` `#FireHOL` `#UFW` `#ipset`

#### DNS

`#Unbound` `#DNSSEC` `#dnscrypt-proxy` `#DoH` `#DoT` `#Cloudflare`

#### Messagerie

`#Exim` `#relais-SMTP` `#SPF` `#DKIM` `#DMARC`

#### Services

`#nginx` `#reverse-proxy` `#Samba` `#SMB3` `#vsftpd` `#FTPES` `#Cockpit` `#Webmin`

#### Packaging

`#RPM` `#mock` `#rpmlint` `#COPR` `#dnf` `#apt` `#dpkg`

### 🌐 Réseau

#### Routage & commutation

`#Cisco-IOS` `#Juniper-JunOS` `#CML`

#### Pare-feu matériels

`#Juniper-NetScreen` `#VPN` `#SSL`

### 📈 Supervision

#### Métriques & tableaux de bord

`#Prometheus` `#node_exporter` `#postgres_exporter` `#Grafana`

#### Supervision d'infrastructure

`#Zabbix`

### 📦 Virtualisation & conteneurs

#### Hyperviseurs

`#VMware-ESXi` `#vCenter` `#vSphere` `#HA` `#Hyper-V` `#SCVMM`

#### Conteneurs

`#Docker` `#Podman` `#Kubernetes`

### 🪟 Windows & cloud

#### Windows Server

`#Active-Directory` `#DFS` `#WSUS` `#Exchange`

#### Cloud

`#Azure`

### ⚙️ Automatisation & développement

#### Scripting

`#Bash` `#Python`

#### En cours d'apprentissage

`#Ansible`

#### Bases de données

`#PostgreSQL` `#MySQL`

#### Web

`#HTML` `#CSS` `#JavaScript` `#PHP`

### 🧰 Outils

#### Au quotidien

`#Git` `#Neovim` `#Obsidian` `#Claude-Code`

---

## `$ git log --carriere`

```text
commit HEAD  (actuel)
Author: Nicolas Goffin
Branch: auto-hebergement / la25mheure.org

    Infrastructure Linux auto-hébergée — projet personnel
```
- J'ai conçu et j'exploite un **serveur Fedora** avec SELinux en mode enforcing. Il héberge un blog IT pour débutants (« Linux pour tous ») et plusieurs projets personnels.
- J'ai mis en place une **chaîne DNS respectueuse de la vie privée** : Unbound en résolveur récursif avec DNSSEC, relayé vers dnscrypt-proxy en DoH. Le filtrage des publicités et des traqueurs utilise les listes HaGeZi.
- J'ai construit un **pare-feu FireHOL** adossé à des ipsets mis à jour automatiquement (FireHOL, DShield).
- J'ai déployé une **pile de supervision** : Prometheus, Grafana et Zabbix sur PostgreSQL.
- J'ai configuré la **messagerie sortante** avec un relais Exim (smarthost) et l'alignement SPF, DKIM et DMARC.
- J'exploite des **services de fichiers** : Samba en SMB3 uniquement, et vsftpd en TLS explicite (FTPES) avec chroot.
- Je **package des logiciels en RPM** (COPR) pour Fedora avec mock et rpmlint.
- Je rédige un **wiki Linux en français** d'environ 180 notes. Chaque commande y est testée dans des conteneurs jetables. Sa publication est prévue prochainement.

```text
commit benevolat
Branch: communaute

    Bénévole — « Li P'tite Buweye », centre d'accueil de jour pour personnes sans abri (Liège)
```
- Accueil et accompagnement de personnes sans abri.

```text
commit autoformation
Branch: apprentissage

    Formation continue en autodidacte
```
- **Linux et DevOps** : Docker, Podman, Kubernetes
- Programmation **Python**
- **Ingénierie assistée par IA** avec Claude Code
- Préparation du **CCNA 200-301** avec Cisco NetAcad, Jeremy's IT Lab et des labs CML

```text
commit 2014..2015
Branch: inforius

    IT Support Consultant — Bruxelles-Propreté, pour Inforius SPRL (Bruxelles)
```
- Assistance et dépannage des utilisateurs.
- Déploiement de postes de travail.
- Création de groupes de sécurité pour le DFS (Active Directory).
- Installation d'imprimantes réseau.
- Interface entre les utilisateurs et l'équipe de développement.

```text
commit 2014
Branch: stage

    Stage d'insertion — Clinique et Maternité Sainte-Élisabeth (Namur)
```
- Recherche, documentation et mise en place de la mise à jour d'applications tierces (Flash, Java…) via **WSUS** et WSUS Package Publisher.

```text
commit 2008
Branch: helpdesk

    Agent technique en call center — Win S.A. (Namur)
```
- Dépannage à distance sur Cisco CallManager.

```text
commit 2002..2005
Branch: technobel

    Support informatique et formateur TIC — Technobel (Lessive, Ciney)
```
- Gestion du parc informatique et du réseau.
- Création de sites web pour les projets de l'entreprise.
- **Formateur en TIC et en création de sites web.** J'adaptais le contenu au niveau de chaque apprenant, je rédigeais les supports de cours et je concevais les exercices d'évaluation des compétences.

---

## `$ ls ~/certifications`

| Certification | Statut |
|---|---|
| MCSA Windows Server 2012 — 70-410, 70-411 | ✅ Obtenue |
| Hyper-V 2012 R2 & System Center VMM — 74-409 | ✅ Obtenue |
| Cisco CCNA Routing & Switching — 200-120 | ⏳ Expirée. Préparation du **CCNA 200-301** en cours |
| Microsoft Azure | 🎯 Prochain objectif |

---

## `$ history | grep formation`

| Année | Formation |
|---|---|
| 2013–2014 | **Cloud Specialist** : Technobel, Ciney (200 jours : bases systèmes et réseaux, puis cloud) |
| 2010 | Musique assistée par ordinateur (MAO) : Signal Flow, Liège |
| 2005–2006 | **Cisco CCNA** : Technothèque, Liège |
| 2003–2004 | Formations courtes à Technobel : conception de réseaux Wi-Fi Cisco, serveur de fichiers Samba, création de sites web |
| 2001–2002 | Développeur Internet : STE-Formation |
| 2000–2003 | Graduat en informatique : ECI, Liège (interrompu en 3e année) |
| 1999 | CESS, section audiovisuel : IATA, Namur |

---

## `$ locale -a`

| Langue | Niveau |
|---|---|
| Français | Langue maternelle |
| Anglais | Lecture et écriture techniques : bon niveau. Oral : limité, en progression active |

---

## `$ cat /etc/motd`

```text
🎵 Musique    🚵 VTT    🏃 Course à pied
🎓 Objectif à long terme : créer un centre de formation pour geeks, l'école tech que j'aurais aimé avoir.
```
