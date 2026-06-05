# Spécifications DNS25-Bot - Système de Design Global

## 1. Palette de Couleurs
- **Fond principal** : #050510 (noir navy profond)
- **Couleur primaire/brand** : #f59e0b (ambre/or)
- **Couleur secondaire** : #00bcd4 (turquoise/cyan)
- **Texte principal** : #f0f0f0 (blanc crème)
- **Texte secondaire** : #a0a0b0 (gris bleu)
- **Bordures cartes** : #ffffff alpha 0.06-0.08
- **Fond cartes** : #ffffff alpha 0.03-0.06 + backdrop-blur

## 2. Style Visuel
- **Style** : Premium 3D, dégradés néon, effets holographiques, glassmorphism.
- **Rendu** : Ombres portées, reflets, profondeur lumineuse (pas de flat 2D).
- **Effets** : Glow/neon avec drop-shadow, glassmorphism (fond semi-transparent avec blur).
- **Animations** : Pulse/glow subtil en CSS pour les badges.

## 3. Typographie
- **Titres** : JetBrains Mono (monospace) ou équivalent géométrique.
- **Corps** : System sans-serif.
- **Numéros/Stats** : Monospace bold, aligné à droite.

## 4. Assets à Générer (Total ~75 éléments)

### A. Badges de Profil (12 badges NFT - 400x400px)
1. **Premier Dépôt** : Wallet/Portefeuille (#FFD700 / #FFA500)
2. **Gros Déposant** : Building/Immeuble (#00F2FF / #007BFF)
3. **Baleine** : Whale/Baleine (#7B61FF / #4B0082)
4. **Premier Parrainage** : Handshake (#00F0FF / #00FFA3)
5. **Recruteur** : Users/Groupe (#00A3FF / #7B61FF)
6. **Bâtisseur de Réseau** : Globe (#FF00C7 / #00F0FF)
7. **Inscrit** : Check-circle (#00FFA3 / #00A3FF)
8. **Utilisateur Fidèle** : Star/Étoile (#FF8A00 / #FF0000)
9. **Chasseur de Prédictions** : Target/Cible (#00D1FF / #0057FF)
10. **Observateur de Cotes** : Slot Machine (#AD00FF / #3300FF)
11. **Semaine Active** : Flame/Flamme (#FF5C00 / #FFB800)
12. **Mois Actif** : Sparkle/Étincelle (#FF00C7 / #7B61FF)

### B. Badges de Niveau XP (5 niveaux - 56x56px)
- Novice (Shield), Analyste (Bar chart), Expert (Star), Pro (Trophy), Légende (Crown).

### C. Icônes de Rang MLM (6 rangs - 48x48px)
- Non classé, Bronze, Silver, Gold, Diamond, VIP.

### D. Icônes UI (Diverses tailles)
- Cartes Stats (6 icônes), Navigation (12 icônes), Défis (3 icônes), Notifications (6 icônes), Hero Profil, Parrainage, Menu Partage.

### E. Illustrations Onboarding (3 étapes - 120x120px)
- AlgorithmIllustration, ColorGuideIllustration, StartIllustration.

### F. Assets Crypto & Brand
- USDT, TRX, BNB, BTC, TON.
- Logo DNS25 (PNG & SVG).

## 5. Instructions d'Exécution
- Générer les SVG vectoriels propres.
- Créer les exports PNG 400x400px pour les badges.
- Intégrer les icônes UI en tant que composants React (Inline SVG).
- Corriger les problèmes identifiés (tailles d'images de jeux, logo TON, fichiers inutiles).
