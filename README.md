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
- Analyse et extraction des données par IA
- Enregistrement automatique dans Google Sheets
- Email de confirmation à l'utilisateur
- Notification email à l'admin
- Changement de statut (Approuvée / Rejetée)
- Notification automatique à l'utilisateur selon le statut

## Workflows
- **Workflow 1** : Traitement automatique des factures
- **Workflow 2** : Notification changement de statut

## Structure du projet
projet-factures/
├── frontend/        # Application React
├── workflow/        # Workflows n8n (JSON)
└── README.md


