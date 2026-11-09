# YattaTv pour Android TV

Télécharger et installer YattaTv sur une NVIDIA Shield ou une box Android TV compatible.

**[Télécharger YattaTv.apk](https://github.com/madouyatt95/yattatv-download/releases/latest/download/YattaTv.apk)** · [Toutes les versions](https://github.com/madouyatt95/yattatv-download/releases)

**Code Downloader : `2828478`** · [Lien court à partager](https://aftv.news/2828478) · [Vérifier la destination du code](https://aftv.news/2828478+)

## Installer

1. Sur la box, ouvrir **Downloader**, saisir **2828478** et valider. On peut également télécharger `YattaTv.apk` directement depuis le lien ci-dessus.
2. Si Android le demande, autoriser Downloader à installer des applications.
3. Confirmer l'installation, puis ouvrir **YattaTv** depuis la liste des applications.

Configuration minimale : Android TV 8.0 (Android 8.0 / API 26). La version 0.18.3 a été vérifiée sur NVIDIA Shield sous Android 11 ; les autres box restent à valider.

## Mettre à jour

Réutiliser le lien de téléchargement pour obtenir la dernière version. Installer la nouvelle APK par-dessus l'application existante afin de conserver les réglages. Ne pas désinstaller l'application avant la mise à jour.

Une nouvelle publication sur GitHub ne déclenche pas à elle seule l'installation automatique sur la box. Chaque version conserve le nom de fichier `YattaTv.apk` pour que le lien et le code Downloader ci-dessus restent valables.

## Connexion et DNS

Si un problème DNS est détecté, YattaTv peut proposer son option **DNS YattaTv**. Son activation est facultative et demande l'autorisation VPN d'Android. Elle utilise un service local limité à YattaTv pour transmettre les requêtes DNS par HTTPS à Cloudflare ; les vidéos restent chargées directement depuis leurs sources. Android ne permet qu'un VPN actif par profil.

L'option est également accessible dans **Réglages → Connexion · DNS YattaTv**. Le choix est mémorisé ; quitter complètement l'application arrête le service. Le DNS ne répare pas une source indisponible ou un blocage indépendant de la résolution de noms.

## Vérifier le téléchargement

Chaque Release inclut `SHA256SUMS.txt`, avec l'empreinte SHA-256 du fichier APK.

La version 0.18.3 est une version de test signée avec le certificat Android Debug déjà utilisé pour les installations existantes. Les versions destinées à les mettre à jour doivent conserver une signature compatible.

Ce dépôt distribue le binaire et sa documentation. Les sources de l'application ne sont pas publiées ici.
