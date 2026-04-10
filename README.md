# Système Automatisé de Traitement de Factures

## Description
Application web permettant l'automatisation complète du traitement 
des factures PDF grâce à n8n, l'IA Gemini et les services Google.

## Technologies utilisées
- **Frontend** : React.js
- **Automatisation** : n8n (local)
- **IA** : Google Gemini 2.5 Flash-Lite
- **Stockage** : Google Drive
- **Base de données** : Google Sheets
- **Email** : Gmail API
- **Extraction PDF** : pdf.co

## Fonctionnalités
- Dépôt de factures PDF via formulaire web
- Sauvegarde automatique sur Google Drive
- Extraction du texte PDF automatique
- Analyse IA et extraction des données (fournisseur, montant, date)
- Enregistrement automatique dans Google Sheets
- Email de confirmation automatique

## Workflow n8n
![Workflow](workflow/screenshot.png)

## Structure du projet
