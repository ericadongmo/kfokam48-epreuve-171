# Journal de bord — <matricule>

> Une entrée **par étape**, écrite **au moment où tu la termines**, pas à la fin de la journée.
> Trois lignes suffisent. Un journal rédigé d'un bloc juste avant de soumettre se repère
> immédiatement dans l'historique Git et ne compte pas.

Chaque entrée répond aux trois mêmes questions :

- **Fait** — ce que tu viens de terminer
- **Bloqué** — ce qui t'a coûté du temps, et combien
- **IA** — ce que tu lui as demandé, et **comment tu as vérifié sa réponse**

---

## Étape 1 — Analyse et conception

**Fait :** cahier des charges (17 exigences fonctionnelles, 16 règles de gestion), les trois diagrammes en Mermaid + un quatrième bonus (états-transitions), 11 issues créées, contrat d'API complété, commit `[JALON] analyse` poussé.

**Bloqué :** 12 min sur la contradiction entre Q10 et Q15. Tranchée en faveur de Q10 : Q11 décrit un usage réel et concret du formateur, Q15 n'est qu'une intention générale. Noté en section 7. Par ailleurs, j'ai édité le dépôt à la fois en local et sur l'interface GitHub sans `git pull` entre les deux : le contenu de l'analyse s'est retrouvé committé deux fois sur deux branches divergentes, fusionnées ensuite. Conséquence : `README.md` a été supprimé par erreur dans la fusion (recréé), et le commit `[JALON] analyse` a fini par contenir les fichiers au lieu d'être vide comme demandé par le sujet — je ne réécris pas l'historique déjà poussé pour ne pas risquer le malus `push --force` sur `main`, mais je m'assure que `[JALON] v0.1` et `[JALON] v1.0` seront de vrais commits vides. Leçon retenue : toujours `git pull` avant de committer, ne pas éditer en parallèle sur le web et en local.

**IA :** m'a proposé un découpage en 18 tickets, j'en ai retenu 11. Les autres étaient des tâches techniques (« créer l'entité », « configurer Flyway »), pas des résultats utilisateur. Vérifié en relisant chaque titre : est-ce que le client le comprendrait ?

---

## Étape 2 — Première version

**Fait :**

**Bloqué :**

**IA :**

---

## Étape 3 — Enveloppe

**Fait :**

**Bloqué :**

**IA :**

**Ce que j'ai sorti du périmètre pour absorber le changement, et pourquoi :**

---

## Étape 4 — Version finale

**Fait :**

**Bloqué :**

**IA :**

---

## Étape 5 — Épreuve Git

**Fait :**

**Bloqué :**

**IA :**

---

## Étape 6 — Soumission

**Fait :**

**Ce que je referais autrement avec une journée de plus :**
