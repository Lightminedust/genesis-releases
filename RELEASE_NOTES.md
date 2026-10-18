# Genesis 0.2.0 — Windows et Linux

Genesis est désormais distribué pour Windows et Linux x86-64. Les deux paquets
embarquent le client JavaFX, Java 21 et le moteur Python local ; aucun serveur,
Docker ou environnement Python séparé n'est nécessaire.

L'interface démarre en anglais. Le menu **FR/EN** permet de passer au français,
et mémorise ce choix. Les simulations et les calculs physiques ne changent pas.

## Téléchargements

| Système | Installateur | Portable |
| --- | --- | --- |
| Windows | [Genesis-0.2.0.exe](https://github.com/Lightminedust/genesis-releases/releases/download/v0.2.0/Genesis-0.2.0.exe) | [ZIP](https://github.com/Lightminedust/genesis-releases/releases/download/v0.2.0/Genesis-0.2.0-portable.zip) |
| Debian/Ubuntu x86-64 | [.deb](https://github.com/Lightminedust/genesis-releases/releases/download/v0.2.0/Genesis-0.2.0-linux-x64.deb) | [tar.gz](https://github.com/Lightminedust/genesis-releases/releases/download/v0.2.0/Genesis-0.2.0-linux-x64.tar.gz) |

Sous Linux, installez le `.deb` avec `sudo apt install ./Genesis-0.2.0-linux-x64.deb`,
ou extrayez l'archive et lancez `./Genesis/bin/Genesis`. Un environnement de bureau
GTK 3 est requis. Le moteur écrit ses erreurs dans
`${XDG_STATE_HOME:-~/.local/state}/genesis/logs/engine.log`.

Consultez la [licence](https://github.com/Lightminedust/genesis-releases/blob/main/EULA.txt)
et vérifiez les fichiers avec les [empreintes SHA-256](https://github.com/Lightminedust/genesis-releases/blob/main/CHECKSUMS-SHA256.txt).
Les paquets ne sont pas signés numériquement.
