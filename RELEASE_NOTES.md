# Genesis 0.5.0 — Assembleur moléculaire, réacteur à piston et navigation 3D

Cette version fait du laboratoire moléculaire un atelier complet : on dessine une molécule, on la vérifie, on la simule, on la comprime.

## Nouveautés

- **Assembleur moléculaire 2D.** Dessinez une molécule atome par atome : les valences sont vérifiées pendant le dessin, GFN1-xTB dit si elle tient, se réarrange ou se défait, puis elle passe en 3D dans le simulateur. Sélection multiple, charges, menu contextuel et raccourcis clavier.
- **Un dictionnaire de 151 espèces.** Les molécules de la scène sont reconnues et nommées ; un cercle signale celle qui vient de se former.
- **Une scène 3D plus lisible.** Liaisons simples, doubles et triples dessinées en brins, à plat ou torsadés selon la liaison π calculée ; atomes teintés selon leur charge ; carte détaillée au survol d'un atome et fiche de la molécule au clic droit (moment dipolaire, charges, liaisons).
- **Nouvelle navigation 3D.** Rotation libre autour des axes de l'écran, zoom vers le curseur, déplacement de la vue au clic droit, double-clic pour centrer et suivre un atome, bouton « Tout voir ».
- **Réacteur à piston.** La pression est mesurée sur la paroi et peut être imposée, de 100 à 20 000 atm ; l'enceinte affiche aussi le gaz parfait et l'écart Z = PV/NkT. L'agitation thermique est désormais bien répartie entre les molécules.
- **Nouvel écran de démarrage.** Une orbitale de l'hydrogène, calculée point par point, tourne pendant que le moteur se prépare.

## Statistiques d'utilisation

À partir de cette version, Genesis envoie des statistiques d'utilisation au serveur de Gemmie pour guider son évolution : ouverture et fermeture, durée d'utilisation, laboratoires utilisés, version, système, langue et écran, liés à un identifiant aléatoire créé à l'installation, sans nom ni e-mail. L'adresse IP sert à estimer le pays et la ville et n'est pas conservée. Rien de ce que vous construisez ou calculez n'est envoyé.

Une carte le signale au premier lancement et permet de refuser ; l'envoi se coupe aussi à tout moment dans **⚙ → Envoyer les statistiques d'utilisation**, et Genesis fonctionne exactement de la même façon. Détails : [notice de confidentialité](https://github.com/Lightminedust/genesis-releases/blob/main/docs/PRIVACY.md). La [licence](https://github.com/Lightminedust/genesis-releases/blob/main/EULA.txt) est mise à jour en conséquence.

## Téléchargements

| Système | Installateur | Portable |
| --- | --- | --- |
| Windows | [Genesis-0.5.0.exe](https://github.com/Lightminedust/genesis-releases/releases/download/v0.5.0/Genesis-0.5.0.exe) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.5.0/Genesis-0.5.0-portable.zip) |
| Debian/Ubuntu x86-64 | [.deb](https://github.com/Lightminedust/genesis-releases/releases/download/v0.5.0/Genesis-0.5.0-linux-x64.deb) | [tar.gz](https://github.com/Lightminedust/genesis-releases/releases/download/v0.5.0/Genesis-0.5.0-linux-x64.tar.gz) |
| macOS Apple Silicon | [.dmg](https://github.com/Lightminedust/genesis-releases/releases/download/v0.5.0/Genesis-0.5.0-macos-arm64.dmg) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.5.0/Genesis-0.5.0-macos-arm64.zip) |

Java 21 et le moteur Python local sont inclus. Les utilisateurs des versions 0.3.0 à 0.4.1 reçoivent la proposition de mise à jour au démarrage. Sous Windows, le téléchargement de l'installateur est vérifié par SHA-256 avant son lancement ; sous Linux et macOS, le bouton ouvre la page de téléchargement.

Empreintes : [CHECKSUMS-SHA256.txt](https://github.com/Lightminedust/genesis-releases/releases/download/v0.5.0/CHECKSUMS-SHA256.txt). Licence : [EULA.txt](https://github.com/Lightminedust/genesis-releases/blob/main/EULA.txt).

Sources : [Lightminedust/genesis, commit 434b0df](https://github.com/Lightminedust/genesis/commit/434b0df).

## English

Genesis 0.5.0 turns the molecular laboratory into a full workshop: a 2D molecular assembler checked by valence rules and GFN1-xTB before the molecule moves to 3D, a 151-species dictionary that names the molecules in the scene, bonds drawn as one, two or three strands (flat or twisted from the computed π bond), charge-tinted atoms, a drawn hover card and a right-click molecule card, a new 3D navigation (screen-axis rotation, zoom toward the cursor, right-drag panning, double-click to centre and follow an atom, "Show all"), a reactor piston with measured and imposed pressure (100 to 20,000 atm), and a computed hydrogen-orbital start-up screen.

**Usage statistics.** From this version, Genesis sends usage statistics to Gemmie's server to guide its development: start and close, time used, laboratories used, version, system, language and screen, linked to a random identifier created at installation, with no name or e-mail. The IP address is used to estimate the country and city and is not kept. Nothing you build or compute is sent. The first launch shows a card that lets you decline, and **⚙ → Send usage statistics** turns it off at any time; Genesis works the same. Details are in the [privacy notice](https://github.com/Lightminedust/genesis-releases/blob/main/docs/PRIVACY.md); the [EULA](https://github.com/Lightminedust/genesis-releases/blob/main/EULA.txt) is updated accordingly.

Windows, Linux x86-64 and macOS Apple Silicon packages bundle Java 21 and the local Python engine. Download links and SHA-256 checksums are above. Existing 0.3.0 to 0.4.1 installations are offered the update at startup.
