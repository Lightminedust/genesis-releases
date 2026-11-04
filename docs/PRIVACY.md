# Genesis — statistiques d'utilisation et vie privée

*English below.*

Genesis calcule tout sur ton ordinateur. Pour savoir comment le logiciel est utilisé et le faire évoluer, il envoie
des **statistiques d'utilisation** au serveur de Gemmie (`https://gemmi-e.com/genesis/stats`). Cette page dit
lesquelles, pourquoi, et comment les refuser ou les faire effacer.

## Ce qui est envoyé

| Quand | Quoi |
|---|---|
| à l'ouverture | l'heure locale et son fuseau, la version de Genesis, le système (nom, version, architecture), la version de Java, la langue du système et celle de l'interface, la taille de l'écran, le nombre de cœurs et la mémoire, s'il s'agit du premier lancement |
| à la fermeture | la durée de la session, dont le temps au premier plan ; chaque laboratoire ouvert (atome, molécule, fusion, réacteur…), combien de fois et combien de temps ; si la fermeture a été normale |
| toujours | un **identifiant aléatoire** créé à l'installation (il reste le même après une mise à jour ou une réinstallation sur le même compte), et l'identifiant de la session |

Le serveur reçoit aussi **ton adresse IP**, comme tout site web. Cloudflare, par où passe gemmi-e.com, en déduit un
pays, une région et une ville approximatifs ; le serveur garde ces trois lieux et **une empreinte salée de l'adresse**
(pour reconnaître les envois répétés), jamais l'adresse elle-même.

**Jamais envoyé :** ton nom, ton e-mail, ce que tu construis ou calcules dans Genesis, tes exports, tes fichiers.

Si une session s'arrête brutalement, sa fin est envoyée au lancement suivant. Hors ligne, les envois attendent
(quelques kilo-octets au plus) et partent quand le réseau revient.

## Pourquoi

Uniquement pour améliorer Genesis : savoir quels laboratoires servent, combien de temps, sur quels systèmes et
quelles tailles d'écran, dans quelles langues et quels pays, et si le logiciel plante. Ces données ne sont ni
vendues ni partagées, et ne servent à aucune publicité.

## Refuser

L'envoi est actif par défaut. Au premier lancement, une carte le dit et propose **Refuser l'envoi** ; tant qu'elle
n'a pas de réponse, rien ne part. Ensuite, à tout moment : **⚙ (en haut à droite) → Envoyer les statistiques
d'utilisation**. Coupé, plus rien n'est envoyé (ce qui attendait est effacé) et Genesis fonctionne exactement de la
même façon.

## Tes droits

Tu peux demander à voir tes données ou à les faire effacer : écris à **nellawassi@gmail.com** en donnant
l'identifiant de ton installation (⚙ → Quelles données sont envoyées ?).

Responsable : Gemmie — nellawassi@gmail.com. Conservation : 24 mois après la dernière utilisation.

---

# Genesis — usage statistics and privacy

Genesis computes everything on your computer. To learn how it is used and improve it, it sends **usage
statistics** to Gemmie's server (`https://gemmi-e.com/genesis/stats`).

**Sent at start:** local time and time zone, Genesis version, operating system (name, version, architecture), Java
version, system and interface language, screen size, processor cores and memory, whether it is the first launch.
**Sent at close:** session length (and time in the foreground), each laboratory opened, how many times and for how
long, whether the close was normal. **Always:** a **random identifier** created at installation (kept across updates
and reinstalls on the same account) and the session identifier. The server also receives **your IP address**;
Cloudflare, in front of gemmi-e.com, derives an approximate country, region and city from it. The server keeps those
and **a salted fingerprint of the address**, never the address itself.

**Never sent:** your name, your e-mail, what you build or compute, your exports, your files.

**Why:** solely to improve Genesis. Not sold, not shared, not used for advertising.

**Opting out:** sending is on by default; the first launch shows a card with **Decline**, and nothing leaves until
it is answered. At any time: **⚙ (top right) → Send usage statistics**. Once off, nothing is sent and Genesis works
the same.

**Your rights:** to see or delete your data, write to **nellawassi@gmail.com** with your installation identifier
(⚙ → What data is sent?). Controller: Gemmie. Retention: 24 months after last use.
