> 🇬🇧 [English version](README.md)

# Tycho Knowledge

`@tycho/knowledge` est le module Tycho derrière `tycho knowledge`. Il a pour but de gérer des bases de connaissances au format Open Knowledge Format (OKF v0.1) : installer des paquets OKF, composer leur arborescence et leurs fichiers `index.md`, valider le contrat de frontmatter et synchroniser une base vers une cible. Pour la vue d'ensemble, voir le [README du cœur Tycho](https://git.qtrn.io/tycho/tycho).

## Installation

```bash
tycho module add knowledge
```

## Utilisation

```bash
tycho knowledge install <package>   # installer un paquet OKF
tycho knowledge compose             # composer l'arborescence et générer les index.md
tycho knowledge validate            # vérifier le frontmatter YAML plat (OKF v0.1)
tycho knowledge sync [target]       # synchroniser la base de connaissances vers une cible
tycho knowledge list                # lister les paquets OKF installés
```

Sans commande, ou avec une commande inconnue, le module affiche son aide.

## Statut

Squelette précoce. Les cinq commandes (`install`, `compose`, `validate`, `sync`, `list`) sont des emplacements réservés qui affichent seulement un message ; aucune ne lit ni n'écrit encore de fichier.

## Licence

AGPL-3.0-only, © Quatrain Technologies. Source : https://git.qtrn.io/tycho/tycho-knowledge
