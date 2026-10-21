# Genesis 0.3.0 — Windows et Linux

Genesis 0.3.0 est disponible pour Windows et Linux x86-64. Les paquets
embarquent le client JavaFX, Java 21 et le moteur Python local ; aucun serveur,
Docker ou environnement Python séparé n'est nécessaire. La version macOS reste
la 0.2.0 pour l'instant.

## Nouveautés

- **Anglais complet.** Toute l'interface et tous les messages du moteur sont
  traduits (explications, journal, laboratoires). Le menu **FR/EN** bascule à
  tout moment.
- **Tirer sur le noyau.** Un neutron lent : son issue (diffusion, capture,
  fission de l'uranium 235, réactions (n,α) et (n,p)) est tirée selon les
  sections efficaces mesurées, et l'énergie libérée vient des masses mesurées.
  Ou une particule α de 5 MeV, calculée dans la chambre de collision.
- **Les particules changent l'atome à l'impact**, plus au clic : un proton
  ajouté vole d'abord vers le noyau, et l'élément change quand il le touche.
- **Isotope naturel.** Un clic dans la table périodique charge l'isotope le
  plus abondant sur Terre (Fe-56, U-238…).
- **Valence et phase.** Un bouton montre en 3D la seule sous-couche de valence
  (la forme du 4d¹ de l'yttrium apparaît) ; le panneau Orbitale colore la phase
  de ψ (bleu ψ > 0, orange ψ < 0).
- **Plus clair.** Diagramme des couches avec 1s en bas, explications Aufbau et
  Klechkowski au survol, limites du modèle affichées, scène moins chargée,
  « transmutation » plutôt que « fusion » au-delà du fer.
- **Plus solide.** Le moteur ne plante plus lors de clics rapides ou d'ajouts
  massifs de neutrons, et l'application démarre bien sur l'uranium 238.
- **Mises à jour.** Au démarrage, Genesis vérifie s'il existe une version plus
  récente et propose de l'installer (sous Windows, l'installateur est vérifié
  par son empreinte SHA-256 avant d'être lancé). Les versions 0.2.0 et
  antérieures ne le font pas : installez la 0.3.0 à la main une fois.

## Téléchargements

| Système | Installateur | Portable |
| --- | --- | --- |
| Windows | [Genesis-0.3.0.exe](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0.exe) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-portable.zip) |
| Debian/Ubuntu x86-64 | [.deb](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-linux-x64.deb) | [tar.gz](https://github.com/Lightminedust/genesis-releases/releases/download/v0.3.0/Genesis-0.3.0-linux-x64.tar.gz) |
| macOS Apple Silicon (0.2.0) | [.dmg](https://github.com/Lightminedust/genesis-releases/releases/download/v0.2.0/Genesis-0.2.0-macos-arm64.dmg) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.2.0/Genesis-0.2.0-macos-arm64.zip) |

Sous Linux, installez le `.deb` avec `sudo apt install ./Genesis-0.3.0-linux-x64.deb`,
ou extrayez l'archive et lancez `./Genesis/bin/Genesis`. Un environnement de bureau
GTK 3 est requis. Le moteur écrit ses erreurs dans
`${XDG_STATE_HOME:-~/.local/state}/genesis/logs/engine.log`.

Consultez la [licence](https://github.com/Lightminedust/genesis-releases/blob/main/EULA.txt)
et vérifiez les fichiers avec les [empreintes SHA-256](https://github.com/Lightminedust/genesis-releases/blob/main/CHECKSUMS-SHA256.txt).
Les paquets ne sont pas signés numériquement.
