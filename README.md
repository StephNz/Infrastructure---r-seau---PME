# Projet d’infrastructure réseau PME

## Objectif du projet

Ce projet consiste à concevoir une infrastructure réseau sécurisée et évolutive pour une PME.

L’objectif est de segmenter le réseau par services, configurer le DHCP, mettre en place un firewall et assurer la communication contrôlée entre les VLANs.

## Technologies utilisées

- Cisco Packet Tracer
- VLAN
- DHCP
- Routage inter-VLAN
- Firewall
- Switch Cisco 2960
- Tests de connectivité

## Travail réalisé

- Création des VLANs par département
- Configuration des ports access
- Configuration du trunk 802.1Q
- Mise en place du DHCP
- Configuration des passerelles
- Ajout d’un firewall
- Tests de ping entre les machines
- Vérification de la connectivité réseau

## VLANs configurés

| VLAN | Département | Réseau |
|---|---|---|
| 10 | Vente | 192.168.10.0/24 |
| 20 | Colometrie | 192.168.20.0/24 |
| 30 | Commercial | 192.168.30.0/24 |
| 40 | compta | 192.168.40.0/24 |
| 50 | RH | 192.168.50.0/24 |
| 60 | IT | 192.168.60.0/24 |
| 70 | serveur | 192.168.70.0/24 |

## Résultat attendu

Chaque service dispose de son propre réseau, les adresses IP sont distribuées automatiquement par DHCP, et le firewall permet de renforcer la sécurité.


## Topologie réseau

![Topologie](images/topologie-reseau.png)
