# Jeu 95 Online — version prête à héberger

Cette version est prête pour Render.

## Chemin le plus simple

### 1. Créer un compte GitHub
Va sur github.com et crée un compte.

### 2. Créer un nouveau dépôt
Clique sur :
New repository

Nom conseillé :
jeu-95-online

Laisse en Public ou Private, peu importe.

### 3. Envoyer les fichiers
Dans ton dépôt GitHub :
- clique sur "uploading an existing file"
- glisse-dépose TOUT le contenu de ce dossier
- clique sur "Commit changes"

Important : il faut envoyer les fichiers, pas le ZIP.

Tu dois voir à la racine :
- server.js
- package.json
- render.yaml
- README.md
- dossier public

### 4. Créer le site sur Render
Va sur render.com et crée un compte.

Puis :
- New +
- Web Service
- Connect GitHub
- choisis ton dépôt `jeu-95-online`
- Render devrait détecter le projet

Paramètres :
- Build Command : npm install
- Start Command : npm start
- Health Check Path : /health

Clique sur Deploy.

### 5. Récupérer le lien
Quand le déploiement est fini, Render donne un lien du style :

https://jeu-95-online.onrender.com

C’est ce lien que tu partages aux joueurs.

## Important
Sur le plan gratuit Render, le site peut se mettre en veille après un moment sans utilisation. Au premier chargement, il peut prendre un peu de temps à se réveiller.
