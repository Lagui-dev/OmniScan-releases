# OmniScan — versions publiées

Scanner réseau pour Windows : découverte des équipements d'un réseau local (ICMP, ARP), noms (DNS, NetBIOS, mDNS, LLMNR), constructeur, ports TCP et UDP, bannières, certificats TLS, découverte UPnP / WS-Discovery / ONVIF / DNS-SD, SNMP, partages SMB, système d'exploitation, serveurs DHCP. Tout est déduit sur le poste : aucune donnée n'est envoyée à un service en ligne.

Ce dépôt ne contient que les versions publiées. Téléchargements : **[Releases](../../releases)**.

## Quelle version choisir ?

| Fichier | Usage |
| :--- | :--- |
| `OmniScan-<version>-Windows-AMD64-setup.exe` | **Installable** : menu Démarrer, désinstallation ; dans *Program Files* ou pour l'utilisateur seul, sans droits administrateur. |
| `OmniScan-<version>-Windows-AMD64.zip` | **Portable** : décompresser où l'on veut, lancer `bin\omniscan.exe`. Rien n'est installé. |

## Configuration requise

- Windows 10 ou 11, 64 bits.
- Aucun droit administrateur pour le scan standard.

## Bon usage

Ne scannez que des réseaux qui vous appartiennent ou pour lesquels vous avez une autorisation.

## Licence

GPL-3.0 (fichier `LICENSE`, aussi présent dans chaque paquet). Bibliothèques Qt sous LGPL-3.0, icônes Lucide sous licence ISC.
