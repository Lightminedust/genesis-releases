# Genesis — téléchargements Windows

Genesis est un simulateur atomique et subatomique pour Windows. Ce dépôt contient uniquement les téléchargements officiels, les empreintes de vérification et la [licence utilisateur](EULA.txt). Le code source n'est pas publié ici.

## Version 0.1.1

| Fichier | Usage |
| --- | --- |
| [Genesis-0.1.1.exe](https://github.com/Lightminedust/genesis-releases/releases/download/v0.1.1/Genesis-0.1.1.exe) | Installation avec raccourcis Windows |
| [Genesis-0.1.1-portable.zip](https://github.com/Lightminedust/genesis-releases/releases/download/v0.1.1/Genesis-0.1.1-portable.zip) | Extraire entièrement, puis lancer `Genesis/Genesis.exe` |

Les fichiers sont aussi accessibles depuis la [dernière release](https://github.com/Lightminedust/genesis-releases/releases/latest). L'application embarque Java et son moteur Python ; il n'est pas nécessaire d'installer Gradle, Python ou Docker pour l'utiliser.

Au premier lancement, le chargement des données du moteur peut prendre plusieurs dizaines de secondes. Un écran de chargement reste affiché jusqu'à la connexion. Si le moteur échoue, consulter `%LOCALAPPDATA%\Genesis\logs\engine.log`.

Les empreintes SHA-256 sont dans [CHECKSUMS-SHA256.txt](CHECKSUMS-SHA256.txt). Cette version n'est pas signée numériquement.
