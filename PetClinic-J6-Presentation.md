# 🐾 PetClinic — Jour 6 : Présentation finale

Dernier jour du projet. Matinée : derniers ajustements et vérification finale. Après-midi : soutenances devant l'encadrant.

---

## 0. Vérification finale (matin, tous les groupes — 30-45 min)

- [ ] `git pull` sur `main`, démarrage complet de l'application (back + front) sans erreur.
- [ ] Relecture rapide du `README.md` et de `DOCUMENTATION.md` : tout est bien à jour, aucun lien mort, procédure d'installation testée par quelqu'un qui n'a pas écrit la doc.
- [ ] Vérifier que le jeu de données de démo est toujours cohérent (RDV du jour visibles, dashboard correct, pas de données de test parasites).
- [ ] Dernière relecture croisée : chaque binôme jette un œil rapide à un module qui n'est pas le sien pour repérer un dernier bug visible à l'écran.

## 1. Dernière répétition (matin, tous les groupes — 30 min)

- [ ] Répétition finale de l'enchaînement de démo dans l'ordre : Clinique → Médecin → Client → Animal → Rendez-vous → Recherche/Dashboard.
- [ ] Vérifier le chronométrage (viser large : présentation + questions).
- [ ] Désigner qui parle sur quelle partie si plusieurs binômes présentent à la suite.

---

## 2. Déroulé de la soutenance (par groupe)

Chaque binôme dispose d'un créneau (à ajuster selon le nombre de groupes et le temps disponible, par exemple 15-20 min chacun) structuré ainsi :

1. **Démo du module** (5 min) — scénario concret, pas une liste de fonctionnalités.
2. **Choix techniques et règles métier** (3-4 min) — ce qui a été fait, pourquoi.
3. **Difficultés rencontrées** (3-4 min) — notamment sur la coordination Git/JDL avec les autres groupes, et comment elles ont été résolues.
4. **Questions** (5 min).

Le binôme ayant tenu le rôle "Intégration" au moment de la démo présente en plus, en 5 minutes supplémentaires :
- l'état du `petclinic.jdl` final et son évolution au fil du projet,
- la gestion des conflits rencontrés (Liquibase, i18n, fichiers Angular générés),
- le fonctionnement de la CI mise en place.

---

## 3. Grille d'évaluation

### Volet technique (par module, /10)
- Fonctionnalités CRUD complètes et conformes au périmètre du groupe — 3 pts
- Personnalisation front (lisibilité, traduction, recherche) — 3 pts
- Logique métier et validations correctement implémentées — 2 pts
- Qualité du code et tests écrits — 2 pts

### Volet collaboratif (commun à tout le projet, /10)
- Qualité et régularité des Pull Requests (taille raisonnable, description claire) — 3 pts
- Participation aux revues de code d'autres groupes — 2 pts
- Contribution constructive aux évolutions du `petclinic.jdl` commun — 2 pts
- Tenue du rôle Intégration (pour les groupes qui l'ont assumé) — 2 pts
- Qualité de la documentation rédigée — 1 pt

### Volet présentation (/10)
- Clarté et fluidité de la démo — 4 pts
- Pertinence des explications techniques — 3 pts
- Qualité des réponses aux questions — 3 pts

---

## ✅ Fin du projet

À l'issue de la journée, l'encadrant dispose :
- d'une application PetClinic complète et fonctionnelle sur `main`,
- d'un historique Git reflétant un vrai travail collaboratif (branches, PR, reviews, résolutions de conflits),
- d'une documentation technique complète,
- d'une note par groupe sur les trois volets ci-dessus.
