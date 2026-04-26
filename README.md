# APK Analysis Lab

Analyse statique de l'application **OWASP UnCrackable Level 1** réalisée dans le cadre d’un lab de sécurité mobile.

## Objectif
Analyser la structure d’un APK, étudier le code décompilé et identifier les vulnérabilités.

## Contenu
- rapport.pdf : rapport détaillé de l’analyse

## Résultats
- Validation du secret côté client
- Clé AES exposée dans le code
- Données récupérables (Base64)
- `android:allowBackup="true"` activé

## Recommandations
- Ne pas stocker de secrets côté client
- Utiliser une validation côté serveur
- Protéger les clés cryptographiques
- Désactiver allowBackup
