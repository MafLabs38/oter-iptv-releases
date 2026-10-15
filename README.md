# oter IPTV — téléchargement (bêta)

Lecteur IPTV pour Windows 10 (1903+) et Windows 11 : TV en direct, films et séries (Xtream Codes et M3U).
Ce dépôt ne contient que les versions installables ; le code source est privé.

## Installer

1. Ouvrir la **[dernière version](../../releases/latest)** et télécharger **`OterIPTVApp-win-Setup.exe`**.
2. Le lancer. L'installeur n'est pas signé : Windows affiche « Windows a protégé votre ordinateur ».
   Cliquer **Informations complémentaires**, puis **Exécuter quand même**.
3. oter IPTV s'installe pour l'utilisateur courant (pas besoin des droits administrateur) et démarre.

Pas envie d'installer ? `OterIPTVApp-win-Portable.zip` se décompresse et se lance tel quel
(mais ne se met pas à jour tout seul).

## Mises à jour

Automatiques : l'appli vérifie au démarrage puis toutes les 4 heures, télécharge la nouvelle
version en arrière-plan (seulement les différences quand c'est possible) et propose de redémarrer.
Sans action de votre part, la mise à jour s'installe à la prochaine fermeture de l'appli —
jamais au milieu d'une vidéo. **Paramètres › Mises à jour** permet aussi de vérifier à la main.

## Désinstaller

Paramètres Windows › Applications › oter IPTV › Désinstaller. Vos comptes, favoris et historique
(dans `%LocalAppData%\OterIPTV`) sont conservés.

---

*English:* download `OterIPTVApp-win-Setup.exe` from the [latest release](../../releases/latest).
It is not code-signed: on the SmartScreen warning click **More info › Run anyway**. Updates are
automatic. Video decoding uses [FFmpeg](https://ffmpeg.org) (LGPL build).
