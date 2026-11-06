> 🇫🇷 [Version française](README.fr.md)

# Tycho Knowledge

`@tycho/knowledge` is the Tycho module behind `tycho knowledge`. Its purpose is to curate knowledge bases in the Open Knowledge Format (OKF v0.1): install OKF packages, compose their hierarchy and `index.md` files, validate the frontmatter contract and synchronise a base to a target. For the overall picture, see the [Tycho core README](https://git.qtrn.io/tycho/tycho).

## Install

```bash
tycho module add knowledge
```

## Usage

```bash
tycho knowledge install <package>   # install an OKF package
tycho knowledge compose             # compose the hierarchy and generate index.md files
tycho knowledge validate            # check the flat YAML frontmatter (OKF v0.1)
tycho knowledge sync [target]       # synchronise the knowledge base to a target
tycho knowledge list                # list installed OKF packages
```

Without a command, or with an unknown one, the module prints its usage.

## Status

Early skeleton. All five commands (`install`, `compose`, `validate`, `sync`, `list`) are placeholders that only print a message; none of them reads or writes files yet.

## Licence

AGPL-3.0-only, © Quatrain Technologies. Source: https://git.qtrn.io/tycho/tycho-knowledge
