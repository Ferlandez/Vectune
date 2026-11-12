# Journal des changements

Suivi de l'avancement de **Vectune**, version par version.

---

## [En cours]

### Novembre 2026 — Ouverture de vrais fichiers ROM
- Ouverture et modification de vrais fichiers de calibration (ROM)
- Tables de carburant, d'allumage et limites du moteur, classées par catégorie
- Indicateur de confiance par table (confirmée / probable / inconnue)
- Modifications appliquées en temps réel, avec annuler / rétablir
- Zones sensibles protégées en lecture seule
- Sauvegarde sécurisée : nouveau fichier à la première sauvegarde, l'original n'est jamais écrasé
- Avertissement clair quand un fichier modifié n'est pas prêt à être programmé dans un ECU

### Base

### Ajouté
- Éditeur de tables de calibration (grille, graphique 2D, surface 3D)
- Annuler / rétablir, copier / coller, interpolation
- Ouverture et enregistrement des calibrations
- Diagnostic de base : lecture des codes défaut
- Thème sombre / clair

### Prévu
- Version gratuite : diagnostic (codes défaut) et données en temps réel par la prise OBD2, avec une interface Tactrix OpenPort 2.0
- Datalog
- Lecture de l'ECU
- Reprogrammation de l'ECU
