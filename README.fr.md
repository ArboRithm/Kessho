<div align="center">

<img src="https://arborithm.github.io/Kessho/logo.svg" alt="Kessho" width="160" />

# Kessho

**Une mémoire structurée pour vos agents IA — sur votre poste.**

Un vault de fichiers Markdown qui vous appartient, rangé pour que sa croissance reste maîtrisée, que vos agents lisent et complètent par MCP d'une session à l'autre.

[![Dernière version](https://img.shields.io/github/v/release/ArboRithm/Kessho?label=version&color=4C40D4)](https://github.com/ArboRithm/Kessho/releases/latest) [![Plateformes](https://img.shields.io/badge/macOS%20%C2%B7%20Windows-4C40D4?label=plateformes)](#télécharger) [![Documentation](https://img.shields.io/badge/doc-arborithm.github.io-AD8B4A)](https://arborithm.github.io/Kessho/)

[**Télécharger**](https://github.com/ArboRithm/Kessho/releases/latest) · [**Documentation**](https://arborithm.github.io/Kessho/) · [**Référence MCP**](https://arborithm.github.io/Kessho/reference/mcp/) · [English](README.md)

<br />

<img src="https://arborithm.github.io/Kessho/captures/fr/accueil.png" alt="Le tableau de bord de Kessho : la mémoire en relations, les dépôts récents et les zones de la mémoire" width="900" />

</div>

## Pourquoi Kessho

Un agent IA oublie tout à la fin de la session. Le remède habituel est une mémoire simple et plate — un fichier, ou un tas de notes — que personne ne range et dont la croissance n'est pas contrôlée : tôt ou tard, l'agent s'y noie. Kessho vous donne, à vous et à votre agent, une mémoire **structurée** : de simples fichiers Markdown dans un dossier qui vous appartient, rangés par zones (sessions, connaissances, procédures, principes, objectifs, personnes), projets et domaines, avec des résumés, des archives et des contrôles de santé. L'agent la lit pour reprendre là où vous en étiez et la complète au fil du travail, et elle reste lisible en grossissant.

Vous gardez les fichiers. Votre agent garde le fil. Kessho garde tout en ordre.

## Points forts

- **Une mémoire qui est juste un dossier** — des fichiers Markdown que vous pouvez copier, sauvegarder et ouvrir avec d'autres outils. Compatible avec Obsidian, sans en dépendre.
- **Un serveur MCP embarqué** — `kessho-mcp` expose 62 outils à vos agents : rappel, recherche, archivage, écriture de notes, entretien du vault. Chaque outil est dans la [référence MCP](https://arborithm.github.io/Kessho/reference/mcp/).
- **Voir sa mémoire** — un tableau de bord, des clés de contexte à donner à un agent pour qu'il retrouve où vous en étiez, et un graphe des relations entre vos notes.
- **Un vrai éditeur** — lire et écrire des notes avec des blocs, des tableaux, des encadrés, des liens entre notes, rechercher et remplacer, exporter.
- **Synchronisation git** — sauvegarder et partager la mémoire par un dépôt git de votre choix, à la main ou automatiquement.
- **Vos agents, connectés** — Kessho déclare son serveur MCP dans les outils IA installés sur votre poste.

## Fonctionne avec vos agents

Kessho parle le [Model Context Protocol](https://modelcontextprotocol.io). Connectez-le depuis l'application (**Réglages › Connecteurs MCP**), puis parlez simplement à votre agent :

> _« On reprend là où on en était sur le projet de facturation. »_

Le [guide « Avec un agent »](https://arborithm.github.io/Kessho/agent/) déroule des cas d'usage réels : reprendre, chercher, écrire, archiver, synchroniser, entretenir.

## Télécharger

| Plateforme  | Prérequis                              | Fichier                          |
| ----------- | -------------------------------------- | -------------------------------- |
| **macOS**   | Apple Silicon, macOS 11 ou plus récent | `Kessho_<version>_aarch64.dmg`   |
| **Windows** | x64                                    | `Kessho_<version>_x64-setup.exe` |

La première version publique, la **0.3.0**, arrive : elle apparaîtra sur la [page des versions](https://github.com/ArboRithm/Kessho/releases). Kessho propose ensuite ses propres mises à jour — rien ne s'installe sans votre accord.

La version macOS est signée et notarisée par Apple. L'installeur Windows n'est pas encore signé : si SmartScreen vous avertit, choisissez **Informations complémentaires**, puis **Exécuter quand même**.

## Premiers pas

1. **Installez** Kessho et parcourez le premier lancement en cinq étapes.
2. **Choisissez votre mémoire** — adoptez un dossier existant ou créez-en un.
3. **Connectez votre agent** depuis **Réglages › Connecteurs MCP**.
4. **Parlez à votre agent** — et regardez la mémoire se remplir dans l'application.

Le [guide](https://arborithm.github.io/Kessho/guide/) détaille chaque écran.

## Vie privée

Kessho tourne sur votre poste. Votre mémoire reste dans vos dossiers et vous appartient. Il n'y a ni télémétrie ni collecte de données.

## Support

- **Documentation** — [arborithm.github.io/Kessho](https://arborithm.github.io/Kessho/)
- **Bugs et suggestions** — [ouvrir un ticket](https://github.com/ArboRithm/Kessho/issues)
- **Contact** — app@arborithm.fr

---

<sub>Kessho est publié par ArboRithm et gratuit selon son [contrat de licence](LICENSE.md). Composants tiers : [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).</sub>
