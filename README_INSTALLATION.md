# Nous Deux V5 — PWA gratuite

Cette version ne nécessite ni App Store, ni Play Store, ni compte Apple Developer.

## Mise en ligne gratuite
Les fichiers sont statiques. Publiez le dossier sur un hébergement HTTPS gratuit (par exemple GitHub Pages).
Aucune base de données distante n'est nécessaire : l'hébergement ne sert que le code de l'application.

## iPhone
1. Ouvrir l'adresse HTTPS de Nous Deux dans Safari.
2. Bouton Partager.
3. Ajouter à l'écran d'accueil.
4. Ouvrir ensuite l'icône Nous Deux.

## Android
1. Ouvrir l'adresse dans Chrome.
2. Menu ⋮ > Installer l'application / Ajouter à l'écran d'accueil.
3. Ouvrir l'icône Nous Deux.

## Appairage et sync
Le premier téléphone crée une clé aléatoire 256 bits. La transmettre UNE FOIS au second téléphone par un canal de confiance et comparer l'empreinte.
Les paquets ND5 utilisent AES-256-GCM via Web Crypto avant partage par WhatsApp.

## Vie privée
Les contenus sont dans le stockage local du navigateur. Le site hébergé ne contient pas vos messages.
Attention : dans une PWA, la clé ne bénéficie pas du Keychain/Keystore natif comme dans V4.1. Toute personne ayant accès au téléphone déverrouillé et aux données du navigateur pourrait potentiellement accéder au stockage de l'application. Ne partagez jamais la clé du couple publiquement.

## Sauvegarde
La synchronisation ND5 constitue aussi une copie transportable des données chiffrées, mais ne remplace pas encore une vraie fonction d'export/backup avec historique.
