# ShyzosChestFN

Le compteur de coffres Fortnite : il compte les coffres que tu ouvres (et ceux que tu casses)
et affiche le total dans un petit overlay par-dessus le jeu.

## Télécharger

Prends l'installateur `ShyzosChestFN_x.y.z_x64-setup.exe` dans la
[dernière release](https://github.com/ShyzosCorp/ShyzosChestFN/releases/latest), puis lance-le.
Windows 10 ou 11, 64 bits.

Une fois installée, l'appli te propose elle-même les nouvelles versions : un bandeau
« Version x.y.z disponible » apparaît sur l'overlay, avec **Installer** et **Plus tard**. Rien
n'est installé sans ton accord, et la proposition attend la fin de ta partie.

## Avant de jouer

- Dans Fortnite, active l'enregistrement des replays : **Paramètres > Jeu > Replays**. Le
  réglage compte à partir de la partie suivante.
- Joue en **plein écran fenêtré** : en plein écran exclusif, Windows ne laisse aucune fenêtre
  s'afficher par-dessus le jeu.

## Ce qu'elle fait

- Total de coffres, gain de la dernière partie et détail par type de coffre.
- Prochaine Treasure Hour (heure de Paris), avec compte à rebours.
- Overlay déplaçable à la souris, 6 positions, 4 tailles, opacité réglable, clics traversants.
- Lancement avec Windows, fermeture automatique quand tu quittes Fortnite (désactivable).

## Comment ça marche

L'appli ne touche pas au jeu : pas d'injection, pas de lecture de sa mémoire, pas de capture
d'écran. Elle lit les fichiers replay que Fortnite enregistre lui-même dans
`%LOCALAPPDATA%\FortniteGame\Saved\Demos\`, à la fin de chaque partie. Tout est calculé sur ton
PC et rien n'est envoyé sur Internet. Le seul accès réseau est la vérification des mises à jour
sur ce dépôt.

Chaque installateur est signé, et l'appli refuse une mise à jour dont la signature ne
correspond pas.

## Ce dépôt

Il ne contient que les versions publiées. Le code source n'est pas public.

---

Projet indépendant, sans lien avec Epic Games. Fortnite est une marque d'Epic Games, Inc.
