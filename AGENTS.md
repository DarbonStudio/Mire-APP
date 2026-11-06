# Règles de l'Agent — MIRE

## 1. Langue et Communication
- **Communication** : Toujours communiquer avec l'utilisateur en **français**.
- **Documentation** : Rédiger toute la documentation, les commentaires de code, les messages de commit et les explications techniques en **français**.

## 2. Principes UX & Ergonomie (Zero-Touch & Pédagogie)
- **Zero-Touch (Joueur Régulier)** : Aucun bouton tactile requis pendant l'effort ou l'analyse vidéo. Feedback massif au centre de l'écran (ex: "BRAS TROP RIGIDE") visible à plusieurs mètres ("Glanceability").
- **Cadre Pédagogique Restrictif (Grand Débutant)** : Cadenasser ou griser les exercices complexes tant que les fondamentaux ne sont pas validés. Progression gamifiée.
- **Hyper-Adaptabilité Logistique (Pratiquant Extérieur)** : L'Onboarding doit intégrer un filtrage matériel strict (Mur + ballon, Filet, etc.) et générer un programme 100% réalisable avec ce setup.

## 3. Architecture & User Flow
- **Écrans Clés Prioritaires** :
  1. *Onboarding* : Accueil, poste (ex: Passeur), niveau, setup matériel.
  2. *Dashboard / Programme du jour* : Programme généré sur-mesure + CTA saillant ("DÉBUTER MA SÉANCE").
  3. *Fiche Exercice* : Démonstration vidéo, séries/répétitions, chrono repos, consignes en `Inter`.
  4. *Écran d'Analyse (Zero-Touch)* : Interface épurée, contraste maximal.
- **Éco-conception & Data-Ink Ratio** : Supprimer le superflu décoratif (ombres lourdes, dégradés superflus). Aucune animation purement décorative. Fonds sombres tendant vers le noir absolu (OLED) pour préserver la batterie.

## 4. Identité Visuelle & Design System
- **Palette Chromatique Stricte (WCAG AAA)** :
  - `Fond Principal` : Bleu Nuit `#01043A` (éco-conception OLED)
  - `Actions & Effort` : Vert Néon `#ADFF02` (CTA principal, validation cinétique)
  - `Technologie & IA` : Cyan Électrique `#66FCF1` (télémétrie, analyse)
  - `Progression & Gamification` : Rose Vibrant `#FECDFE` (niveaux, signalétique d'évolution)
  - `Textes` : Blanc `#FFFFFF` (contraste AAA obligatoire, 7,81:1 sur Bleu Nuit)
- **Typographie Stricte** :
  - `Titres, Impact, Métriques` : exclusivement **Mona Sans** (graisses fortes, italique dynamique).
  - `Corps de texte, Instructions` : exclusivement **Inter** (lisibilité neutre et irréprochable).
- **Assets & Visuels** :
  - Signalétique 100% vectorielle en `.SVG` (formes géométriques pures pour Attaque, Bloc, Défense, Service, Passe).
  - Habillage abstrait basé sur les courbes dynamiques du "M" du logo, sans photographies lourdes.

---
*Détails des règles modulaires disponibles dans [.agents/rules/](file:///Users/florian/Desktop/Mire%20App/.agents/rules/)*.
