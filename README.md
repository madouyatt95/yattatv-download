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

À partir de **YattaTv 0.18.4**, les nouvelles versions sont recherchées automatiquement à l'ouverture et au retour dans l'application. Le contrôle réseau est limité à une fois par heure. Une version disponible est proposée à l'accueil ; pendant un live, un message indique de passer par Réglages.

Ouvrir **Réglages → Mises à jour** pour vérifier, télécharger et installer une version. Android demande l'autorisation d'installation depuis YattaTv la première fois, puis la confirmation de la mise à jour. Les réglages sont conservés.

Sur Shield, attendre le chargement de la liste Android des sources, puis défiler jusqu'à **YattaTv** et l'autoriser. Revenir dans l'application pour installer. Si le bouton **Télécharger et installer** réapparaît au retour, il réutilise le fichier déjà téléchargé et vérifié.

Les installations restées en **0.18.3** doivent installer cette nouvelle APK une fois avec Downloader ou le lien ci-dessus pour obtenir cette fonction. Installer par-dessus l'application existante, sans la désinstaller.

Le lien et le code Downloader restent également disponibles pour les premières installations. Chaque version conserve le nom de fichier `YattaTv.apk`.

## Connexion et DNS

La première ouverture propose d'activer **DNS YattaTv** pour les chaînes et le cinéma. Son activation est facultative et demande l'autorisation VPN d'Android. Elle utilise un service local limité à YattaTv pour transmettre les requêtes DNS par HTTPS à Cloudflare ; les vidéos restent chargées directement depuis leurs sources. Android ne permet qu'un VPN actif par profil. Si l'activation a été différée, un problème DNS détecté peut aussi déclencher une proposition.

L'option est également accessible dans **Réglages → Connexion · DNS YattaTv**. Le choix est mémorisé ; quitter complètement l'application arrête le service. Le DNS ne répare pas une source indisponible ou un blocage indépendant de la résolution de noms.

## Vérifier le téléchargement

Chaque Release inclut `SHA256SUMS.txt`, avec l'empreinte SHA-256 du fichier APK.

Les APK publiées sont des versions de test signées avec le certificat Android Debug déjà utilisé pour les installations existantes. Les versions destinées à les mettre à jour doivent conserver une signature compatible. YattaTv contrôle aussi la taille, le SHA-256, le nom du package et le numéro de version de l'APK avant l'installation d'une mise à jour.

Ce dépôt distribue le binaire et sa documentation. Les sources de l'application ne sont pas publiées ici.
