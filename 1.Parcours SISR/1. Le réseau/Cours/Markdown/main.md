# 1. Les bases du réseau

## 1.1 Qu'est-ce qu'un réseau ? 

---

## 1.2 Globalité et bases

### 1.2.1 Client serveur



### 1.2.2 DHCP

### 1.2.3 DNS 

### 1.2.4 HTTP et HTTPS
---

## 1.3 Classification des réseaux

### 1.3.1 PAN, LAN, MAN, WAN

### 1.3.2 Réseau d'entreprise vs domestique vs internet

### 1.3.3 DMZ

---

## 1.3 Les Topologies

bus, étoiles, maillé, hybride etc..

### 1.3.1 Topologie physique vs logique

### 1.3.2 Modèle actuelle 

---


## 1.4 Notions de transmission

### 1.4.1 Signal analogique / numérique, bande passante, débit, latence, gigue, perte

### 1.4.2 Bits, octets, et le piège Mb/s vs Mo/s

### 1.4.3 Simplex, half-duplex, full-duplex

### 1.4.4 Unicast, multicast, broadcast, anycast

### 1.4.5 Domaine de collision vs domaine de diffusion


---

## 1.5 Les modèles en couches

### 1.5.1 Pourquoi découper en couches ? 

### 1.5.2 Le modèle OSI

### 1.5.3 Le modèle TCP/IP

### 1.5.4 Encapsulation / désencapsulation
Segment → paquet → trame → bits
En-têtes : qui ajoute quoi
MTU, fragmentation, MSS, jumbo frames
Exemple complet : que se passe-t-il quand j'ouvre un site web (à revoir en fin de doc)

---


## 1.6 VLAN

### 1.6.1 Pourquoi utiliser les VLAN ? 

### 1.6.2 Acces, Trunk, Hybride

### 1.6.3 Les normes 802.1Q

### Gestion logiques des VLAN et utilisations pratique

### Routage inter-VLAN

## Les protocoles et leurs fonctionnements

---

## 1.7 Redondances de niveau 2

### 1.7.1 Tempête de broadcast

### 1.7.2 STP/RESTP/MSTP

### 1.7.3 Agrégations de liens


---


## 1.8 IPV4

### 1.8.1 Format et binaire

### 1.8.2 Masque de sous-réseau avec notation CIDR

### 1.8.3 Adresses réseau, diffusion et plage utilisable

### 1.8.4 Les classes 

### 1.8.5 Les adresses privées

APIPA, loopback, réservés etc..


---

## 1.9 Subnetting (Découpages)

### 1.9.1 Méthodes

### 1.9.2 VLSM et FLSM

### 1.9.3 Les Super-réseaux

---


## 1.10 IPV6
### 1.10.1 Pourquoi (épuisement IPv4)

### 1.10.2 Notation, abréviation, préfixes

### 1.10.3 Types d'adresses : GUA, ULA, link-local, multicast

### 1.10.4 SLAAC, DHCPv6, NDP (le remplaçant d'ARP)

### 1.10.5 Cohabitation IPv4/IPv6 (double pile, tunnels)


--- 

## 1.11 Routage

### 1.11.1 Rôle du routeur, table de routage, passerelle par défaut

### 1.11.2 Lecture d'une table de routage, règle du préfixe le plus long

### 1.11.3 Routage statique vs dynamique

### 1.11.4 Protocoles à vecteur de distance vs à état de liens

### 1.11.5 RIP, OSPF, EIGRP, BGP (ce que fait chacun, quand on le rencontre)

### 1.11.6 Métriques, distance administrative, convergence

### 1.11.7 Redondance de passerelle : VRRP / HSRP


---

## 1.12 Translation NAT et PAT

### 1.12.1 Qu'est-ce que le NAT ?

### 1.12.2 NAT statique

### 1.12.3 Redirection de port 

### 1.12.4 Limites


---

## 1.13 TCP

### 1.12.1 En-tête TCP et flag 

### 1.12.2 Handcheck

### 1.12.3 Fiabilité du protocole

### 1.12.4 Controle de flux

### 1.12.5 Les états de la connexion

---

## 1.14 UDP

### 1.14.1 Quand et pourquoi ? 

### 1.14.2 TCP vs UDP

---

## 1.15 Messagerie et connexino à distances

### 1.15.1 Messagerie — SMTP, IMAP, POP3, SPF / DKIM / DMARC

### 1.15.2 Autres services — SSH, Telnet (et pourquoi ne pas l'utiliser), FTP/SFTP/FTPS, SMB, NFS, NTP, SNMP, Syslog, LDAP / Kerberos, RDP

---

## 1.16 Les équipements

### 1.16.1 Quels sont leurs utilités

### 1.16.2 Architecture d'un réseau d'entreprise


---


## 1.17 Le sans-fil (Wifi)

### 1.17.1 Les fréquences radios

### 1.17.2 Les normes

### 1.17.3 Les concepts principaux 

SSID BSSID, ESSID, WIFI 6 et 7

### 1.17.4 La sécurité du wifi 

WEP, WPA? WPA2, WPA3

### 1.17.5 les bonnes pratiques


---

## 1.18 VPN

### 1.18.1 Fonctionnment du VPN

### 1.18.2 Le site-à-site

### 1.18.3 IPsec 

### 1.18.4 SSL/TLS 


---

## 1.19 Virtualisation 

### 1.19.1 vSwitch

### 1.19.2 Conteneur (Docker, Podman)

### 1.19.3 Cloud 

### 1.19.4 SDN

---


## 20. Boite à outils et scénarios

50.1 ipconfig / ifconfig / ip a
50.2 ping, traceroute / tracert, pathping
50.3 nslookup, dig
50.4 netstat / ss, arp, route
50.5 telnet / nc pour tester un port
50.6 Wireshark / tcpdump : lire une capture sans paniquer
50.7 iperf, speedtest


## 21. Des certifications pour aller plus loin



## 22. Autres




<!-- Commande de création : `pandoc Page\ de\ garde.md Sommaire.md av_propos.md main.md -o Cours_Réseau_2026.pdf --pdf-engine=xelatex -V lang=fr` -->

