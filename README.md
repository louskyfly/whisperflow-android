# WhisperFlow Android

APK Android de WhisperFlow, pour piloter le PC et envoyer des fichiers depuis le téléphone.

## Installer l'application

**Lien durable :** https://github.com/louskyfly/whisperflow-android/releases/latest/download/WhisperFlow.apk

1. Ouvre ce lien depuis le téléphone.
2. Télécharge `WhisperFlow.apk`.
3. Autorise l'installation depuis cette source si Android le demande.
4. Installe par-dessus l'ancienne version.

## Nouveautés de la version 1.6

- **Enregistrement écran verrouillé** : le micro continue même quand l'écran est éteint (service de premier plan + verrou processeur).
- **Tuile « WhisperFlow »** dans les réglages rapides : démarre ou arrête la dictée depuis l'écran verrouillé.
- Le texte transcrit arrive sur le téléphone (notification + dernière dictée) avec un bouton **Réécrire sur le PC**.
- Contrôle de l'ordinateur : aperçu des deux écrans, souris au doigt, clavier, alimentation.
- Envoi de fichiers du téléphone vers le PC, sélecteur de fichiers natif.
- Sonnerie « Retrouver mon téléphone » : volume alarme au maximum et vibreur au maximum.

### Nouveautés de la version 1.5

- Envoi de fichiers du téléphone vers le PC, même les fichiers lourds (transfert par morceaux).
- Sélecteur de fichiers Android natif (choix multiple).
- Sonnerie « Retrouver mon téléphone » : volume alarme au maximum et vibreur au maximum.
- Les fichiers envoyés arrivent dans `Téléchargements\WhisperFlow` sur le PC.

## Connexion au PC

L'application a besoin que le PC soit allumé et que le pont WhisperFlow Mobile soit lancé.

- Page d'installation locale : `http://<IP-DU-PC>:8766/`
- Application locale : `https://<IP-DU-PC>:8765/`

Le téléphone doit être sur le même Wi-Fi que le PC. Si le réseau isole les appareils, utilise l'accès distant WhisperFlow.

## Signature

APK de développement, signé avec la clé debug locale. Android peut afficher un avertissement lors de l'installation.
