# 🗡️ Chroniques des Royaumes — JDR Fiches de Personnage

Gestionnaire de fiches de personnage pour JDR (Donjons & Dragons / Fantasy), hébergeable sur GitHub Pages.

## 🚀 Déploiement sur GitHub Pages

1. Crée un nouveau dépôt GitHub (public ou privé avec Pages activé)
2. Upload les deux fichiers : `index.html` et `fiche.html`
3. Va dans **Settings → Pages → Source → Deploy from branch → main**
4. Ton site sera disponible sur `https://TON-PSEUDO.github.io/NOM-DEPOT/`

## 📱 Utilisation

### Pour le MJ (Maître du Jeu)
1. Ouvrir `index.html`
2. **Créer une aventure** avec un nom et un mot de passe MJ
3. Cliquer sur l'aventure → **Panneau MJ** → entrer le mdp MJ
4. **Ajouter des personnages** (prénom, nom, race, classe, mdp joueur)
5. **Exporter l'aventure** → copier le code → l'envoyer aux joueurs

### Pour les joueurs
1. Ouvrir le lien du site
2. Si première fois : **Importer une aventure** → coller le code du MJ
3. Sélectionner l'aventure → cliquer sur son personnage → entrer son mdp
4. Modifier sa fiche → sauvegarde automatique ✓

### Synchronisation
- Chaque modification est sauvegardée **localement** sur l'appareil
- Pour partager les mises à jour : le MJ réexporte et renvoie le code
- ⚠️ Le localStorage est propre à chaque appareil/navigateur

## 🔐 Sécurité
- Les mots de passe sont **hashés** (non stockés en clair)
- Le MJ accède à toutes les fiches avec son mdp global
- Chaque joueur accède uniquement à sa fiche avec son mdp personnel

## 📂 Fichiers
- `index.html` — Liste des aventures, création, gestion
- `fiche.html` — Fiche de personnage complète (onglets Identité / Psycho / Vitales / Stats)

## 💡 Pas de serveur nécessaire
Tout fonctionne en **localStorage** dans le navigateur. Aucune base de données, aucun backend.
