---
description: "Standards UX, interactions des écrans et respect des contraintes terrains (Zero-Touch, Pédagogie, Adaptabilité)."
globs: "docs/ux/**/*", "src/screens/**/*", "prototypes/**/*"
alwaysApply: true
---

# 🧠 Principes UX & Ergonomie (MIRE)

## 1. Principe du "Zero-Touch" (Joueur Régulier)
- **Objectif** : Empêcher le joueur de devoir interagir tactilement avec l'écran pendant l'effort.
- **Prototypage Figma / UI** : Les écrans d'analyse vidéo ne doivent contenir aucun bouton d'action requérant une manipulation tactile. Le retour (feedback) doit apparaître sous forme de signalétique vectorielle massive au centre de l'écran (ex: "BRAS TROP RIGIDE"). L'information doit être saisie en un coup d'œil ("glanceability") à plusieurs mètres de distance.

## 2. Cadre Pédagogique Restrictif (Grand Débutant)
- **Objectif** : Canaliser l'impatience du joueur et éviter la surcharge cognitive liée au mimétisme des professionnels.
- **Prototypage Figma / UI** : Les wireframes de la bibliothèque d'exercices doivent visuellement griser ou verrouiller avec un cadenas les exercices complexes tant que les fondamentaux ne sont pas validés. La progression doit être gamifiée.

## 3. Hyper-Adaptabilité Logistique (Pratiquant de l'Extrême)
- **Objectif** : Adapter instantanément l'application au matériel très précaire du joueur extérieur (ex: juste un ballon et un mur).
- **Prototypage Figma / UI** : L'Onboarding (premier lancement) doit imposer un écran de filtrage matériel (Setup: Mur + ballon, Filet, etc.). Le User Flow ne doit générer qu'un programme 100% viable selon ce choix, sous peine de provoquer l'abandon immédiat de l'utilisateur.

