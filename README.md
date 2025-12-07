# Générateur de QR Code

Application web simple pour créer des QR codes à partir de texte ou d'URL.

## Hébergement sur GitHub Pages

### Étapes

1. **Créer un repository GitHub**
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/votre-username/qrcode-generator.git
   git push -u origin main
   ```

2. **Activer GitHub Pages**
   - Aller dans les paramètres du repository
   - Section "Pages" dans le menu latéral
   - Source : Sélectionner "main" branch
   - Cliquer sur "Save"

3. **Accéder à l'application**
   - URL : `https://votre-username.github.io/qrcode-generator/`
   - Disponible en quelques minutes

## Fonctionnalités

- ✅ Génération de QR code instantanée
- ✅ Support texte et URL
- ✅ Téléchargement en PNG
- ✅ Design responsive
- ✅ Aucune dépendance externe (hors CDN)

## Technologies

- HTML5
- CSS3
- JavaScript (Vanilla)
- QRCode.js (via CDN)

## Licence

MIT