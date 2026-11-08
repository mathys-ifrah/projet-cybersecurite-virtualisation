# Projet cybersécurité : Configuration matérielle & virtualisation

**Groupe : MNC-CYBER** : Mathys, Nasri, Clement
Formation : La Plateforme

## Présentation
- 📄 [Version PDF](presentation/Configurations_Materielles_Virtualisation.pdf)
- 🔗 [Lien Google Slides](COLLE_ICI_TON_LIEN)

## Contenu

| Job | Sujet |
|-----|-------|
| 1 à 4 | Configurations matérielles (PC à budget) |
| 5 | Téléchargement de VMware Workstation Pro |
| 6 à 9 | Installation et configuration de Windows 10 en VM |
| 10 | Commandes CMD (fichiers et dossiers) |
| 11 à 15 | Debian 13 : installation, commandes, utilisateurs, Chrome |
| 16 | Réseau NAT / ping entre VMs |
| 17 | Réseau de test : Debian (NAT + host-only) et Windows 11 |
| 18 | SSH / SCP (à venir) |

## Topologie du Job 17

| Machine | Interface | Type | IP |
|---|---|---|---|
| Debian | ens160 | NAT | 192.168.146.130/24 |
| Debian | ens256 | Host-only | 192.168.56.10/24 |
| Windows 11 | Ethernet0 | NAT | 192.168.146.129/24 |
