<p align="center"><img src="assets/banner.png" alt="Batflix pour Android TV"></p>

<p align="center">
  <b>Le lecteur IPTV pensé pour la télécommande.</b><br>
  Direct, films et séries de votre abonnement, rapides et lisibles depuis le canapé.
</p>

<p align="center">
  <a href="https://github.com/loudovic12/Batflix-TV/releases/latest/download/Batflix.apk"><b>Télécharger Batflix.apk</b></a>
  · Android TV et Google TV, Android 6 ou plus
  · <a href="README.md">English</a>
</p>

<p align="center">
  <img alt="Code Downloader 9415870" src="https://img.shields.io/badge/Downloader-9415870-FFC93C">
  <img alt="Android TV 6 ou plus" src="https://img.shields.io/badge/Android%20TV-6%2B-3DDC84">
  <img alt="Fait avec l'aide de l'IA" src="https://img.shields.io/badge/fait%20avec-l'aide%20de%20l'IA-8A2BE2">
</p>

## Ce que fait Batflix

| | |
|---|---|
| **Le direct qui tient.** Quand un serveur coupe ou ralentit, Batflix reprend tout seul, sur la même chaîne ou sur un autre serveur de votre abonnement. Le zapping démarre en moins d'une seconde et demie. | **Tout à la télécommande.** Catégories à gauche, chaînes au centre, aperçu en direct à droite. Recherche à la voix, filtre par pays, favoris en maintenant OK. |
| **Films et séries.** Reprise là où vous vous êtes arrêté, « À voir plus tard », favoris, « Vu », tri par nouveautés ou de A à Z, épisode suivant enchaîné. | **Ajout du compte depuis le téléphone.** Scannez le QR code affiché sur la TV et remplissez le formulaire sur le téléphone : il va directement à la TV par votre Wi-Fi, jamais par Internet. |
| **Plusieurs comptes.** Xtream ou playlist M3U, plusieurs serveurs par compte. Si l'un tombe, les autres continuent. | **Mises à jour intégrées.** Batflix vous prévient quand une nouvelle version sort, montre ce qui change et l'installe en un clic. |

## Captures

| Direct | Plein écran |
|---|---|
| ![Direct : catégories, chaînes, aperçu](assets/screens/live.png) | ![Menu du lecteur](assets/screens/player.png) |
| **Accueil** | **Ajout depuis le téléphone** |
| ![Accueil](assets/screens/home.png) | ![QR code pour ajouter un compte](assets/screens/add.png) |

## Installer sur la TV

**Le plus simple : l'appli Downloader** (Android TV, Google TV et anciennes Fire TV)

1. Sur la TV, installez **Downloader** d'AFTVnews (logo orange) depuis le Play Store, ou l'Appstore d'Amazon sur Fire TV.
2. Ouvrez Downloader et tapez le code **9415870** ([aftv.news/9415870](https://aftv.news/9415870)), ou l'adresse
   `https://github.com/loudovic12/Batflix-TV/releases/latest/download/Batflix.apk`.
   Les deux mènent toujours à la dernière version signée.
3. Quand Android le demande, autorisez Downloader à installer des applis, revenez en arrière, puis **Installer** et **Ouvrir**.
4. Downloader peut ensuite supprimer l'APK pour libérer de la place : Batflix reste installé.

**Autres façons**

- **Depuis le téléphone ou l'ordinateur** : téléchargez `Batflix.apk` dans les [Releases](https://github.com/loudovic12/Batflix-TV/releases)
  et envoyez-le à la TV avec une appli de transfert comme *Send Files to TV*.
- **Clé USB** : copiez `Batflix.apk` sur une clé USB et ouvrez-le avec un gestionnaire de fichiers sur la TV (par exemple *X-plore*).
- **adb** (avancé) : `adb install Batflix.apk`.

**Selon l'appareil**

- **Google TV (Chromecast avec Google TV, TV récentes)** : l'installation d'applis est bloquée tant qu'on ne l'active pas.
  *Paramètres › Système › À propos*, appuyez 7 fois sur *Build du système d'exploitation Android TV* pour activer le
  mode développeur, puis *Paramètres › Applis › Sécurité et restrictions › Sources inconnues* et activez **Downloader**.
- **Fire TV** : activez *Paramètres › Ma Fire TV › Options pour les développeurs › Installer des applis inconnues ›
  Downloader*. Les Fire TV sorties depuis fin 2025 tournent sous Vega OS, pas Android, et ne peuvent pas lancer
  Batflix. Fire TV n'est pas encore testée.
- Batflix demande **Android 6 ou plus récent**. L'appareil de référence est une Xiaomi Mi Box S (Android TV 14).

**Ajouter votre abonnement**

Au premier lancement, suivez l'accueil jusqu'à **Nouveau compte**. Le plus rapide : **scannez le QR code avec
votre téléphone** (même Wi-Fi que la TV), entrez le code PIN affiché sur la TV, puis remplissez vos infos ou collez
votre lien d'abonnement complet. Sur la TV, choisissez **Enregistrer et charger**. Les chaînes sont prêtes en quelques
secondes, les films et séries en une minute environ.

**Mises à jour**

Rien à faire : Batflix affiche une fenêtre quand une nouvelle version sort (ou vérifiez dans *Réglages › À propos ›
Rechercher une mise à jour*) et l'installe en un clic. La première fois, Android peut demander d'autoriser Batflix à
installer des applis.

**Dépannage**

- *« Application non installée »* : libérez de la place et téléchargez à nouveau. Si un ancien Batflix venu
  d'ailleurs est installé, désinstallez-le d'abord (une autre signature ne peut pas être mise à jour).
- *Downloader n'ouvre pas le code* : tapez plutôt l'adresse complète ci-dessus.
- *Aucune chaîne* : vérifiez les infos de votre abonnement, puis *Réglages › Synchroniser*.

## Bon à savoir

- **Batflix ne fournit aucune chaîne ni aucun contenu.** C'est un lecteur : il faut votre propre abonnement IPTV.
- **Vos identifiants restent sur la TV**, chiffrés. Pas de compte Batflix, pas de publicité, pas de statistiques.
- **Ne téléchargez Batflix que depuis cette page.** Chaque version est signée : une copie modifiée ne pourrait pas remplacer la vôtre.
- **Fait avec l'aide de l'IA.** Batflix est conçu, testé sur de vraies box Android TV et maintenu par son auteur,
  avec Claude (Anthropic) comme assistant de programmation.

Les captures montrent des chaînes gratuites et publiques.
