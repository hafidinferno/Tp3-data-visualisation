# TP Data Visualisation : Évolution des Déchets (DEEE) en France

Ce projet propose une visualisation interactive de l'évolution des tonnages de **Déchets d'Équipements Électriques et Électroniques (DEEE)** par département en France, entre 2009 et 2021.

Il a été réalisé avec **D3.js (v7)**.

## ⚠️ Important : Comment lancer le projet

Pour des raisons de sécurité liées aux navigateurs (politique **CORS**), ce projet ne peut pas fonctionner en ouvrant simplement le fichier `index.html` (protocole `file://`). Les données externes (CSV et GeoJSON) seraient bloquées.

**Vous devez utiliser un serveur local.**

### Option 1 : Avec Visual Studio Code (Recommandé)
1. Installez l'extension **Live Server**.
2. Faites un clic droit sur `index.html`.
3. Choisissez **"Open with Live Server"**.

### Option 2 : Avec Python
Ouvrez un terminal dans le dossier du projet et lancez :
```bash
# Pour Python 3
python -m http.server 8000
