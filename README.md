# PresenceKF — kfokam48-epreuve-171

Application de gestion de présence, dépôt d'exercices et relecture par les pairs pour la formation KFOKAM48. Voir `docs/CAHIER_DES_CHARGES.md` pour le besoin complet.

**Frontend :** Next.js, choisi car il apporte nativement le routage par fichiers (les trois écrans — formateur, étudiant, relecteur — deviennent trois dossiers dans `app/`) et une structure de projet déjà cadrée, évitant de perdre du temps en configuration pendant l'épreuve (F1).

**Backend :** Java 17+ / Spring Boot, Maven (wrapper `mvnw` commité).

## Démarrage

À compléter à l'étape 4 (version finale) : commande(s) testée(s) depuis un clone vierge.

## Documentation

- `docs/CAHIER_DES_CHARGES.md` — besoin, exigences, règles de gestion
- `docs/diagrammes/` — cas d'utilisation, classes, séquence, états (Mermaid)
- `docs/JOURNAL.md` — journal de bord par étape
- `api/contrat.yaml` — contrat d'API
