---
description: "Directives de navigation, maquettage des transitions et respect du User Flow MIRE."
globs: "src/navigation/**/*", "*.figma", "docs/flow/**/*"
alwaysApply: true
---

# 🗺️ Prototypage & Architecture User Flow (MIRE)

## 1. Respect de l'Arborescence
Le prototypage doit refléter le diagramme du User Flow défini. Les écrans clés à maquetter en priorité sont :
- **Onboarding** : Accueil, sélection du poste (ex: Passeur), niveau, et matériel disponible (ex: Mur + ballon).
- **Dashboard / Programme du jour** : Affichage hiérarchisé du programme généré sur-mesure avec un CTA évident ("DÉBUTER MA SÉANCE").
- **Fiche d'Exercice** : Vidéo démonstrative en haut, série/répétitions, chronomètre de repos, et conseils textuels en typographie Inter.
- **Écran d'Analyse (Zero-Touch)** : Interface épurée avec retour visuel ultra-contrasté.

## 2. Minimalisme & Éco-conception UI
- **Animations** : Dans les prototypes Figma et le code, bannir les animations superflues (Smart Animate complexe) qui ne servent qu'à décorer. N'animer que les transitions d'état ayant une fonction ergonomique pour guider l'œil (ex: apparition d'un feedback de correction).
- **Data-Ink Ratio** : Supprimer tous les éléments visuels non essentiels (ombres portées inutiles, dégradés superflus, fioritures). L'écran d'entraînement doit tendre vers le noir absolu pour économiser l'énergie de l'appareil (écrans OLED).
