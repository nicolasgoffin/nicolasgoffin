# Nicolas Goffin

**System & Network Administrator — Linux focus**

📍 Liège, Belgium · 🔗 [LinkedIn](https://be.linkedin.com/in/goffinnicolas) · 🐙 [GitHub](https://github.com/nicolasgoffin) · 🇫🇷 [Version française](CV.fr.md)

---

## `$ whoami`

```text
nicolas — sysadmin who builds, breaks and documents his own infrastructure.
```

I'm a system and network administrator with a strong Linux focus: I have been using Linux since 1999. I started out in networking and virtualization (Cisco, Juniper, VMware, Hyper-V, Windows Server) and today I run my own production Linux infrastructure end to end: firewall, encrypted DNS, mail, file services, monitoring and packaging.

I learn by doing, and I write down everything I learn. I also used to work as a trainer, and teaching IT is something I want to get back into: making Linux and networking accessible to people who are just starting out.

---

## `$ ls -R ~/skills`

### 🐧 Linux — since 1999

#### Distributions

`#Fedora` `#RHEL` `#Debian` `#Ubuntu` `#Kali` `#Kicksecure` `#NixOS`

#### System

`#systemd` `#SELinux` `#Bash` `#LVM` `#ext4` `#quotas` `#journald`

#### Networking

`#Netplan` `#nftables` `#firewalld` `#iptables` `#FireHOL` `#UFW` `#ipset`

#### DNS

`#Unbound` `#DNSSEC` `#dnscrypt-proxy` `#DoH` `#DoT` `#Cloudflare`

#### Mail

`#Exim` `#SMTP-relay` `#SPF` `#DKIM` `#DMARC`

#### Services

`#nginx` `#reverse-proxy` `#Samba` `#SMB3` `#vsftpd` `#FTPES` `#Cockpit` `#Webmin`

#### Packaging

`#RPM` `#mock` `#rpmlint` `#COPR` `#dnf` `#apt` `#dpkg`

### 🌐 Networking

#### Routing & switching

`#Cisco-IOS` `#Juniper-JunOS` `#CML`

#### Firewall appliances

`#Juniper-NetScreen` `#VPN` `#SSL`

### 📈 Monitoring

#### Metrics & dashboards

`#Prometheus` `#node_exporter` `#postgres_exporter` `#Grafana`

#### Infrastructure monitoring

`#Zabbix`

### 📦 Virtualization & containers

#### Hypervisors

`#VMware-ESXi` `#vCenter` `#vSphere` `#HA` `#Hyper-V` `#SCVMM`

#### Containers

`#Docker` `#Podman` `#Kubernetes`

### 🪟 Windows & cloud

#### Windows Server

`#Active-Directory` `#DFS` `#WSUS` `#Exchange`

#### Cloud

`#Azure`

### ⚙️ Automation & development

#### Scripting

`#Bash` `#Python`

#### Learning

`#Ansible`

#### Databases

`#PostgreSQL` `#MySQL`

#### Web

`#HTML` `#CSS` `#JavaScript` `#PHP`

### 🧰 Tooling

#### Daily drivers

`#Git` `#Neovim` `#Obsidian` `#Claude-Code`

---

## `$ git log --career`

```text
commit HEAD  (current)
Author: Nicolas Goffin
Branch: self-hosting / la25mheure.org

    Self-hosted Linux infrastructure — personal project
```
- Designed and run a **Fedora server** with SELinux in enforcing mode. It hosts a blog for IT beginners ("Linux for everyone") and several personal projects.
- Set up a **privacy-first DNS chain**: Unbound as a recursive resolver with DNSSEC, forwarding to dnscrypt-proxy over DoH. Ad and tracker filtering uses HaGeZi blocklists.
- Built a **FireHOL firewall** backed by automatically refreshed ipsets (FireHOL, DShield).
- Deployed a **monitoring stack**: Prometheus, Grafana and Zabbix with PostgreSQL backends.
- Configured **outbound mail** through an Exim smarthost relay with aligned SPF, DKIM and DMARC.
- Run **file services**: Samba over SMB3 only, and vsftpd over explicit TLS (FTPES) with chroot.
- **Package software as RPMs** (COPR) for Fedora using mock and rpmlint.
- Am writing a **French Linux wiki** of about 180 notes. Every command in it is tested in disposable containers. It will be published soon.

```text
commit 2025..present
Branch: learning

    Continuous self-training
```
- **DevOps**: Docker, Podman, Kubernetes (since 2026)
- **Python** programming (since 2025)
- **AI-assisted engineering** with Claude Code (since 2025)
- **CCNA 200-301** preparation through Cisco NetAcad, Jeremy's IT Lab and CML labs

```text
commit 2022..present
Branch: community

    Volunteer — "Li P'tite Buweye", day centre for homeless people (Namur)
```
- Welcomed and supported people experiencing homelessness.

```text
commit 2014..2015
Branch: inforius

    IT Support Consultant — Bruxelles-Propreté, for Inforius SPRL (Brussels)
```
- Provided user support and troubleshooting.
- Deployed workstations.
- Created security groups for DFS (Active Directory).
- Installed network printers.
- Acted as the link between users and the development team.

```text
commit 2014
Branch: internship

    Internship — Clinique et Maternité Sainte-Élisabeth (Namur)
```
- Researched, documented and implemented third-party application updates (Flash, Java…) through **WSUS** and WSUS Package Publisher.

```text
commit 2008
Branch: helpdesk

    Call-centre Technician — Win S.A. (Namur)
```
- Provided remote troubleshooting on Cisco CallManager.

```text
commit 2002..2005
Branch: technobel

    IT Support & ICT Trainer — Technobel (Lessive, Ciney)
```
- Managed the IT and network infrastructure.
- Built websites for company projects.
- **Taught ICT and web development courses.** I adapted the content to each learner's level, wrote the course material and designed skills assessments.

---

## `$ ls ~/certifications`

| Certification | Status |
|---|---|
| MCSA Windows Server 2012 — 70-410, 70-411 | ✅ Obtained |
| Hyper-V 2012 R2 & System Center VMM — 74-409 | ✅ Obtained |
| Cisco CCNA Routing & Switching — 200-120 | ⏳ Expired. Now preparing **CCNA 200-301** |
| Microsoft Azure | 🎯 Next target |

---

## `$ history | grep education`

| Year | Training |
|---|---|
| 2013–2014 | **Cloud Specialist**: Technobel, Ciney (200 days: systems and network basics, then cloud) |
| 2010 | Computer-assisted music production: Signal Flow, Liège |
| 2005–2006 | **Cisco CCNA**: Technothèque, Liège |
| 2003–2004 | Short courses at Technobel: Cisco Wi-Fi network design, Samba file servers, web design |
| 2001–2002 | Web Developer: STE-Formation |
| 2000–2003 | Bachelor in Computer Science (graduat): ECI, Liège (left during the 3rd year) |
| 1999 | Upper secondary education diploma (CESS), audio-visual section: IATA, Namur |

---

## `$ locale -a`

| Language | Level |
|---|---|
| French | Native |
| English | Technical reading and writing: good. Speaking: basic, actively improving |

---

## `$ cat /etc/motd`

```text
🎵 Music    🚵 Mountain biking    🏃 Running
🎓 Long-term goal: create a training centre for geeks, the tech school I wish I had.
```
