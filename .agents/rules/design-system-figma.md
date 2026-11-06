---
description: "Règles strictes du Design System MIRE, intégration des variables Figma et assets vectoriels."
globs: "design-system/**/*.{ts,json,figma,css}", "docs/ui/**/*", "src/styles/**/*"
alwaysApply: true
---

# 🎨 Design System & Figma Standards (MIRE)

## 1. Palette Chromatique & Contraste (WCAG AAA)
La Direction Artistique repose sur une éco-conception visuelle et une lisibilité extrême ("Glanceability") pour l'extérieur. Les variables de couleur doivent se limiter à ces hexadécimaux stricts :
- **Fond Principal (Éco-conception OLED)** : Bleu Nuit `#01043A`. Les fonds doivent être majoritairement de cette couleur pour éteindre un maximum de pixels.
- **Actions & Effort** : Vert Néon `#ADFF02`. Réservé aux boutons d'action (ex: "DÉBUTER MA SÉANCE") et à la validation cinétique.
- **Technologie & IA** : Cyan Électrique `#66FCF1`. Réservé à la télémétrie et aux retours d'analyse technique.
- **Progression & Gamification** : Rose Vibrant `#FECDFE`. Réservé aux niveaux, aux cadres pédagogiques et à la signalétique d'évolution.
- **Textes** : Blanc `#FFFFFF` pour assurer un contraste AAA obligatoire (rapport 7,81:1 sur le Bleu Nuit).

## 2. Hiérarchie Typographique
Dans Figma et dans le code, les styles de textes doivent être nommés et structurés selon ces règles :
- **Titres & Impact (`Mona Sans`)** : Utiliser exclusivement `Mona Sans` (néo-grotesque variable) pour les en-têtes et les métriques clés. Privilégier les graisses fortes et l'italique pour traduire le dynamisme, le saut et l'élan athlétique.
- **Corps de texte & Consignes (`Inter`)** : Utiliser exclusivement `Inter` pour toutes les descriptions, instructions techniques et textes secondaires. Lisibilité neutre et parfaite, même en petite taille.

## 3. Gestion des Assets & Pictogrammes
- **Vectoriel Uniquement (`.SVG`)** : Toute la signalétique d'effort (Attaque, Bloc, Défense, Service, Passe) doit être conçue en formes géométriques pures et exportée/maquettée en format `.SVG`.
- **Fonds Dynamiques** : Utiliser les courbes abstraites inspirées du "M" du logotype pour habiller l'interface sans alourdir le design avec des photos complexes.

