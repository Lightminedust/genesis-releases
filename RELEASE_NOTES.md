# Genesis 0.4.0 — Le laboratoire moléculaire

Genesis 0.4.0 ajoute un laboratoire moléculaire interactif aux écrans de l'atome, de la fusion et du monde subatomique. Les paquets incluent Java 21 et le moteur Python local : aucune installation séparée de Java, Python, Docker ou MongoDB n'est nécessaire.

## Nouveautés

- **Construire des molécules.** Poser des atomes sur l'établi, partir d'une molécule proposée, déplacer un atome et observer la relaxation de la structure avec le modèle semi-empirique GFN1-xTB.
- **Voir les électrons.** Halo de polarisation, densité de déformation et orbitales moléculaires en 3D ; liaisons covalentes, polaires et multicentres, avec leurs paires d'électrons localisées.
- **Explorer la dynamique.** Température, dynamique libre ou avec thermostat, traction, apport d'énergie et mélanges moléculaires.
- **Comprendre les vibrations.** Modes normaux, excitation d'un mode et choix des isotopes pour observer l'effet des masses atomiques.
- **Lire les calculs.** Bilan d'énergie détaillé, charges, dipôles, forces et comparaison de résultats calculés à des valeurs de référence.
- **Français et anglais.** Les nouveaux écrans et leurs explications sont intégrés au sélecteur de langue.

Le laboratoire moléculaire utilise des approximations de modèle ; ses résultats ne remplacent pas une étude de chimie de précision.

## Téléchargements

| Système | Installateur | Portable |
| --- | --- | --- |
| Windows | [Genesis-0.4.0.exe](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.0/Genesis-0.4.0.exe) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.0/Genesis-0.4.0-portable.zip) |
| Debian/Ubuntu x86-64 | [.deb](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.0/Genesis-0.4.0-linux-x64.deb) | [tar.gz](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.0/Genesis-0.4.0-linux-x64.tar.gz) |
| macOS Apple Silicon | [.dmg](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.0/Genesis-0.4.0-macos-arm64.dmg) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.0/Genesis-0.4.0-macos-arm64.zip) |

Les utilisateurs de Genesis 0.3.0 reçoivent la proposition de mise à jour au démarrage. Sous Windows, le bouton d'installation télécharge l'installateur et vérifie son SHA-256 avant de le lancer. Sous Linux et macOS, il ouvre la page de téléchargement.

Sous Linux, installer le `.deb` avec `sudo apt install ./Genesis-0.4.0-linux-x64.deb`, ou extraire l'archive et lancer `./Genesis/bin/Genesis`. Un bureau avec GTK 3 est requis.

Sous macOS, ouvrir le `.dmg` et glisser Genesis vers Applications, ou extraire le ZIP et ouvrir `Genesis.app`. Le paquet est signé localement, sans notarisation Apple.

Empreintes : [CHECKSUMS-SHA256.txt](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.0/CHECKSUMS-SHA256.txt). Licence : [EULA.txt](https://github.com/Lightminedust/genesis-releases/blob/main/EULA.txt). Les paquets Windows ne disposent pas de signature de code publique.

Sources de cette version : [Lightminedust/genesis, commit 3eb6f44](https://github.com/Lightminedust/genesis/commit/3eb6f44).

## English

Genesis 0.4.0 introduces an interactive molecular laboratory: build and relax molecules using GFN1-xTB, inspect polarization and deformation density, view molecular orbitals and localized electron pairs, explore dynamics, and compare vibrations across isotopes. Detailed energy terms and reference comparisons accompany the simulation. The new screens support both English and French.

Windows, Linux x86-64 and macOS Apple Silicon packages bundle Java 21 and the local Python engine. Download links and SHA-256 checksums are above. Genesis 0.3.0 users are offered the update at startup; Windows supports installer download with checksum verification.
