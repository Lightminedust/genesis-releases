# Genesis 0.4.1 — Correctifs du laboratoire moléculaire

Cette mise à jour améliore la stabilité du laboratoire moléculaire et précise la lecture de ses résultats.

## Correctifs

- **Calculs plus réactifs.** Le solveur électronique gère mieux les ensembles d'atomes séparés, conserve le palier de convergence utile et limite l'effort de calcul pour éviter les blocages prolongés.
- **Dynamique plus robuste.** Lorsqu'un pas ne converge pas ou produit un état invalide, la simulation s'arrête sur le dernier état valide.
- **Historique cohérent.** L'ajout d'un atome remet la courbe d'énergie à zéro pour ne pas mélanger des systèmes de compositions différentes.
- **Bilan énergétique plus clair.** Les valeurs de référence et les explications sur les limites des énergies calculées et du nanoréacteur sont complétées.
- **Textes et traductions.** Plusieurs libellés du laboratoire moléculaire sont corrigés en français et en anglais.

## Téléchargements

| Système | Installateur | Portable |
| --- | --- | --- |
| Windows | [Genesis-0.4.1.exe](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.1/Genesis-0.4.1.exe) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.1/Genesis-0.4.1-portable.zip) |
| Debian/Ubuntu x86-64 | [.deb](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.1/Genesis-0.4.1-linux-x64.deb) | [tar.gz](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.1/Genesis-0.4.1-linux-x64.tar.gz) |
| macOS Apple Silicon | [.dmg](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.1/Genesis-0.4.1-macos-arm64.dmg) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.1/Genesis-0.4.1-macos-arm64.zip) |

Java 21 et le moteur Python local sont inclus. Les utilisateurs des versions 0.3.0 et 0.4.0 reçoivent la proposition de mise à jour au démarrage. Sous Windows, le téléchargement de l'installateur est vérifié par SHA-256 avant son lancement ; sous Linux et macOS, le bouton ouvre la page de téléchargement.

Empreintes : [CHECKSUMS-SHA256.txt](https://github.com/Lightminedust/genesis-releases/releases/download/v0.4.1/CHECKSUMS-SHA256.txt). Licence : [EULA.txt](https://github.com/Lightminedust/genesis-releases/blob/main/EULA.txt).

Sources : [Lightminedust/genesis, commit 3662ad0](https://github.com/Lightminedust/genesis/commit/3662ad0).

## English

Genesis 0.4.1 improves molecular solver convergence and responsiveness for separated atoms, stops dynamics on the last valid state when a calculation fails to converge, resets energy history when an atom is added, and clarifies energy references, model limitations and translations.

Windows, Linux x86-64 and macOS Apple Silicon packages bundle Java 21 and the local Python engine. Download links and SHA-256 checksums are above. Existing 0.3.0 and 0.4.0 installations are offered the update at startup.
