# Mr14KaraFR AIR

Application Android compagnon du mod de suspension pneumatique BeamNG.drive de **Mr14KaraFR**.

## Télécharger

[Installer Mr14KaraFR AIR pour Android](https://github.com/Mr14KaraFR/Mr14KaraFR-Air-Remote/releases/latest/download/Mr14KaraFR_AIR.apk)

Android 8.0 ou plus récent. Première version à tester sur téléphone : compilation et signature vérifiées, pas encore de validation sur appareil physique.

## Première connexion

1. Installer l’APK sur le téléphone.
2. Dans BeamNG, monter le kit pneumatique et activer la liaison **Téléphone Android** depuis l’ATH.
3. Connecter le téléphone et le PC au même Wi-Fi.
4. Dans l’application, toucher **Scanner le QR code de l’ATH** et autoriser la caméra.
5. Viser le QR affiché dans le jeu : avec le mod **0.11.7 ou plus récent**, l’adresse du PC et le code de connexion sont reconnus automatiquement.

Le scanner fonctionne localement, sans envoyer ni enregistrer les images. La saisie manuelle de l’adresse et du code reste disponible. Les anciens QR contenant seulement l’adresse restent lisibles, mais demandent encore les six chiffres.

L’application mémorise l’adresse du PC. Elle conserve l’interface actuelle du mod et maintient l’écran allumé tant qu’elle est affichée. Verrouiller le téléphone ne réaffiche pas l’ATH tant que la session du mod reste valide.

## Mises à jour

- **Interface et commandes** : elles sont chargées depuis le mod du PC. Mettre le mod BeamNG à jour suffit.
- **Application Android** : le bouton **Mise à jour** recherche une version publiée ici. L’application propose le téléchargement et Android demande de confirmer l’installation.
- Le pilotage fonctionne sur le réseau local sans Internet. La recherche de mise à jour de l’APK nécessite Internet.
- Les APK sont vérifiés par leur empreinte SHA-256, leur nom de paquet et leur signature. La même clé de signature doit être conservée pour publier les prochaines versions.

Ce dépôt contient seulement les fichiers publics de distribution. Aucune clé privée, aucun code de connexion et aucune adresse de PC n’y sont publiés.

## Correction 1.1.1 : retour PC et reconnexion

Avec le mod **0.16.1 ou plus récent**, le bouton **PC** rend l’ATH visible sans perdre la télécommande. **Reprendre la télécommande** ou **Recharger** depuis l’accueil restaure la connexion existante. Un rechargement ou une réouverture récupère aussi la session tant qu’elle est valide ; si elle a expiré, le code du jeu est demandé normalement. Verrouiller le téléphone garde l’ATH masqué.
