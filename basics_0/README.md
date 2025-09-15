# Networking basics #0

Projet Holberton sur les bases du réseau informatique.
Objectif : comprendre les notions fondamentales du networking et savoir les appliquer via des scripts Bash simples.

## 📚 Notions couvertes

- Modèle OSI (7 couches)
- Différents types de réseau (LAN, WAN, Internet)
- Adresses MAC et IP (IPv4 & IPv6)
- Localhost et subnets
- Protocoles TCP et UDP
- Numéros de ports (22, 80, 443)
- Commandes réseau de base (`ping`, `netstat`)

## 🗂️ Structure

- `0-OSI_model` → Questions sur le modèle OSI
- `1-types_of_network` → Questions sur LAN, WAN et Internet
- `2-MAC_and_IP_address` → Questions sur MAC et IP
- `3-UDP_and_TCP` → Questions sur les protocoles de transport
- `4-TCP_and_UDP_ports` → Script affichant les ports TCP/UDP en écoute
- `5-is_the_host_on_the_network` → Script pour tester si une IP est joignable

## ⚙️ Exécution

Tous les fichiers sont des scripts Bash exécutables sur Ubuntu 22.04.

Exemple :

```bash
./5-is_the_host_on_the_network 8.8.8.8
```
