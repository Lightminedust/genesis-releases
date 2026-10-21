<p align="center">
  <img src="images/logo.png" alt="Logo de Genesis" width="96" height="96">
</p>

<h1 align="center">Genesis</h1>

<p align="center">
  <b>La matière, calculée sous vos yeux.</b><br>
  Un simulateur physique gratuit pour Windows, Linux et macOS : construisez un atome, faites fusionner deux noyaux, descendez jusqu'aux quarks.
</p>

<p align="center">
  <a href="https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0.exe"><b>Télécharger pour Windows</b></a>
  ·
  <a href="https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-linux-x64.deb"><b>Télécharger pour Linux</b></a>
  ·
  <a href="https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-macos-arm64.dmg"><b>Télécharger pour macOS</b></a>
  ·
  <a href="https://genesis.gemmi-e.com">Site web</a>
  ·
  <a href="README.md">Read in English</a>
</p>

<p align="center">
  <img src="images/atom.jpg" alt="L'écran de l'atome : un atome d'uranium qui se désintègre en thorium, avec son nuage d'électrons, son noyau et la chaîne de désintégration jusqu'au plomb">
</p>

Dans Genesis, rien n'est scénarisé. Un moteur physique écrit en Python fait avancer le temps et applique les lois de la physique ; chaque événement arrive au moment où la loi le décide, avec le calcul qui le justifie. Les chiffres viennent de données de référence : NIST, NUBASE2020, AME2020, PDG, CODATA, REACLIB.

## Trois laboratoires

### L'atome

Choisissez l'un des 118 éléments, puis ajoutez ou retirez protons, neutrons et électrons. L'atome réagit : un électron excité redescend en émettant un photon, un noyau instable se désintègre au moment tiré par sa demi-vie.

- Le nuage électronique en 3D, couche par couche
- Un laser réglable : le photon est absorbé, traverse ou arrache un électron
- La chaîne de désintégration, de l'uranium au plomb, avec le temps qui accélère
- Le noyau vu comme une goutte qui vibre

### La fusion nucléaire

<img src="images/fusion.jpg" alt="La chambre de collision : un carbone 12 et un oxygène 16 qui se soudent, avec la force forte et la chaleur de la soudure affichées en direct">

Choisissez n'importe quels deux noyaux et l'énergie du choc. Le moteur calcule l'approche, la répulsion électrique, l'effet tunnel, puis ce qui reste : une fusion, un rebond ou une fission.

- La collision à son échelle réelle, puis au plus près du contact
- Les champs et les forces qui agissent à chaque instant
- Un bilan détaillé : produits, énergie libérée, probabilités
- Le plasma d'un réacteur et le cœur d'une étoile

### Le monde subatomique

<img src="images/subatomic.jpg" alt="Un électron lancé sur un proton à 2 GeV, raconté étape par étape en 3D avec la probabilité de chaque issue">

Envoyez un électron sur un nucléon et regardez ce qui arrive, assemblez vos propres hadrons à partir de quarks, explorez l'intérieur du proton à différentes résolutions.

- Des collisions racontées étape par étape
- Un atelier pour assembler des hadrons et voir s'ils tiennent
- Le tableau du Modèle Standard, chaque ligne calculée ou mesurée
- La mer de partons qui apparaît quand on regarde de plus près

## Télécharger — version 0.3.0

| Fichier | Usage |
| --- | --- |
| [**Genesis-0.3.0.exe**](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0.exe) | Installateur Windows : ajoute Genesis au menu Démarrer et au bureau |
| [Genesis-0.3.0-portable.zip](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-portable.zip) | Windows portable : extraire toute l'archive, puis lancer `Genesis/Genesis.exe` |
| [**Genesis-0.3.0-linux-x64.deb**](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-linux-x64.deb) | Installateur Debian/Ubuntu x86-64 : ajoute Genesis au menu des applications |
| [Genesis-0.3.0-linux-x64.tar.gz](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-linux-x64.tar.gz) | Linux portable : extraire, puis lancer `Genesis/bin/Genesis` |
| [**Genesis-0.3.0-macos-arm64.dmg**](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-macos-arm64.dmg) | Image disque macOS Apple Silicon : ouvrir, puis glisser Genesis vers Applications |
| [Genesis-0.3.0-macos-arm64.zip](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-macos-arm64.zip) | macOS Apple Silicon portable : extraire, puis ouvrir `Genesis.app` |

Java et le moteur Python sont inclus : aucune installation séparée de Java ou Python n'est requise. Genesis tourne entièrement sur votre ordinateur, sans compte ni serveur. L'anglais est la langue initiale ; le français se choisit dans le menu des langues. Toutes les versions sont sur la [page des Releases](https://github.com/Lightminedust/genesis-releases/releases).

**Premier lancement.** Le moteur charge ses données, ce qui peut prendre plusieurs dizaines de secondes. Un écran de chargement reste affiché jusqu'à ce qu'il soit prêt.

**Avertissement de Windows.** Cette version n'est pas encore signée numériquement. Si Windows SmartScreen affiche un avertissement, cliquez sur **Informations complémentaires**, puis **Exécuter quand même**. Vous pouvez vérifier que votre téléchargement est intact avec les empreintes SHA-256 de [CHECKSUMS-SHA256.txt](CHECKSUMS-SHA256.txt) :

```powershell
Get-FileHash .\Genesis-0.3.0.exe -Algorithm SHA256
```

**Linux.** Sous Debian/Ubuntu, installer le fichier téléchargé avec `sudo apt install ./Genesis-0.3.0-linux-x64.deb`. Pour l'archive portable : `tar -xzf Genesis-0.3.0-linux-x64.tar.gz`, puis `./Genesis/bin/Genesis`. Un bureau avec GTK 3 est nécessaire. Le journal du moteur Linux est dans `${XDG_STATE_HOME:-~/.local/state}/genesis/logs/engine.log`.

**macOS.** Apple Silicon (arm64) uniquement. Ouvrir le `.dmg` et glisser Genesis vers Applications, ou extraire le `.zip` et ouvrir `Genesis.app`. Le paquet n'est pas notarié : si macOS bloque le premier lancement, clic droit sur l'application, **Ouvrir**, puis confirmer. Vous pouvez aussi lever la quarantaine avec `xattr -dr com.apple.quarantine /Applications/Genesis.app`. Le journal du moteur est dans `~/Library/Logs/Genesis/engine.log`.

**Si le moteur ne démarre pas**, son journal se trouve dans `%LOCALAPPDATA%\Genesis\logs\engine.log` sous Windows, `${XDG_STATE_HOME:-~/.local/state}/genesis/logs/engine.log` sous Linux, ou `~/Library/Logs/Genesis/engine.log` sous macOS. Envoyez-le via la [page de contact](https://gemmi-e.com/contact), avec votre version du système.

## Soutenir le projet

Genesis est conçu et développé en indépendant. S'il vous plaît :

- ⭐ **Mettez une étoile à ce dépôt.** C'est le geste le plus simple, et il me montre que Genesis est utilisé.
- 👀 **Watch → Custom → Releases** pour être prévenu des nouvelles versions.
- Parlez-en autour de vous, et envoyez vos idées ou vos bugs via la [page de contact](https://gemmi-e.com/contact).

## Licence

Genesis est gratuit à installer et à utiliser, pour un usage personnel ou professionnel, sur tous les ordinateurs que vous possédez. C'est un logiciel propriétaire : il est interdit de le vendre, de le redistribuer ou de le modifier. Voir la [licence d'utilisation](EULA.txt) complète. Ce dépôt contient les téléchargements officiels ; le [dépôt du code source](https://github.com/Lightminedust/genesis) est maintenu séparément.

---

<p align="center">
  © 2026 Gemmie · <a href="https://genesis.gemmi-e.com">genesis.gemmi-e.com</a> · <a href="https://gemmi-e.com/contact">Portfolio et contact</a> · <a href="https://github.com/Lightminedust">GitHub</a>
</p>
