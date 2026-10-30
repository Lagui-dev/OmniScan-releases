# OmniScan — versions publiées

Scanner réseau pour Windows : découverte des équipements d'un réseau local en IPv4 et en IPv6 (ICMP, ARP, voisins IPv6), noms (DNS, NetBIOS, mDNS, LLMNR), constructeur, ports TCP et UDP, bannières, certificats TLS, découverte UPnP / WS-Discovery / ONVIF / DNS-SD, SNMP, partages SMB, inventaire WMI des postes Windows et SSH des hôtes Linux / Unix, système d'exploitation, serveurs DHCP. Terminal SSH et transfert de fichiers SFTP intégrés. Tout est déduit sur le poste : aucune donnée n'est envoyée à un service en ligne.

La liste détaillée des fonctions et des nouveautés de chaque version est dans les notes de **[Releases](../../releases)**.

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

GPL-3.0 (fichier `LICENSE`, aussi présent dans chaque paquet). Bibliothèques Qt sous LGPL-3.0, libssh sous LGPL-2.1, Mbed TLS sous Apache-2.0, libvterm sous MIT, icônes Lucide sous licence ISC (textes dans le dossier `licenses` des paquets).
