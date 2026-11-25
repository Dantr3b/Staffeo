# Plateforme SIRH — Ydays 2026-2027

![Statut](https://img.shields.io/badge/Statut-En%20conception-blue)
![Projet](https://img.shields.io/badge/Projet-Ydays%202026--2027-6366f1)
![Version](https://img.shields.io/badge/Version-MVP-orange)

## Présentation

Ce projet consiste à concevoir et développer une plateforme de gestion des ressources humaines (SIRH) destinée aux TPE et PME françaises.

L'objectif est de centraliser les opérations quotidiennes liées à la gestion du personnel, de simplifier l'organisation des équipes et de faciliter les échanges entre salariés et responsables.

Développé dans le cadre des Ydays 2026-2027, le projet repose sur une collaboration entre plusieurs filières : développement, création et design, marketing et communication, audiovisuel et gestion de projet.

## Objectifs

- Simplifier la création et la consultation des plannings.
- Faciliter la gestion des demandes de congés.
- Centraliser les informations relatives aux équipes.
- Proposer une interface intuitive et adaptée aux petites entreprises.
- Garantir la confidentialité des données et la gestion des droits d'accès.
- Réaliser un démonstrateur fonctionnel répondant aux besoins identifiés lors des recherches utilisateurs.

## Fonctionnalités

### MVP — Fonctionnalités prioritaires

- [ ] Création de comptes et authentification.
- [ ] Gestion des rôles et des autorisations.
- [ ] Création et modification des plannings individuels et collectifs.
- [ ] Consultation des plannings.
- [ ] Dépôt des demandes de congés.
- [ ] Acceptation ou refus des demandes par les responsables.
- [ ] Suivi du statut des demandes.
- [ ] Notifications simples.

### Fonctionnalités secondaires

- [ ] Consultation des informations des équipes.
- [ ] Pointage et enregistrement des horaires.
- [ ] Suivi du temps de travail.
- [ ] Suivi des heures supplémentaires, sous réserve de faisabilité.

### Évolutions futures

- Gestion des disponibilités, des échanges de postes et des remplacements.
- Gestion des absences et des justificatifs.
- Espace documentaire sécurisé.
- Dépôt et consultation des bulletins de paie.
- Intégration avec des logiciels de paie externes.

> Le calcul des salaires ne fait pas partie du périmètre du projet. La priorisation des fonctionnalités reste susceptible d'évoluer selon les recherches utilisateurs et les contraintes techniques.

## Profils utilisateurs

| Profil | Responsabilités principales |
| --- | --- |
| Salarié | Consulter son planning, déposer des demandes et accéder à ses informations autorisées. |
| Manager | Organiser les plannings, traiter les demandes et suivre son équipe. |
| Directeur / dirigeant | Disposer d'une vision globale de l'organisation et de la gestion du personnel. |
| Comptable / service de paie | Accéder aux fonctionnalités administratives et documentaires autorisées, à terme. |

Les permissions détaillées seront définies pendant la conception fonctionnelle.

## Architecture technique

Les choix techniques seront validés par l'équipe de développement à l'issue de l'étude de faisabilité.

| Composant | Technologie |
| --- | --- |
| Frontend | À définir |
| Backend / API | À définir |
| Base de données | À définir |
| Authentification | À définir |
| Tests | À définir |
| Hébergement et déploiement | À définir |

## Installation

Les instructions d'installation, les prérequis, les variables d'environnement et les commandes de démarrage seront documentés après l'initialisation de l'environnement technique.

## Roadmap

| Période | Objectif |
| --- | --- |
| Novembre 2026 | Lancement et cadrage du projet |
| Décembre 2026 | Étude de faisabilité et définition initiale du MVP |
| Janvier 2027 | Architecture, conception et premiers développements |
| Mars 2027 | Développement, intégration et premiers tests |
| Avril 2027 | Corrections, améliorations et stabilisation |
| Mai 2027 | Consolidation, documentation et bilan |

Ce calendrier est prévisionnel et pourra être ajusté au cours du projet.

## Organisation du développement

Les conventions suivantes sont proposées et restent à valider par l'équipe.

### Branches Git

| Branche | Utilisation |
| --- | --- |
| `main` | Version stable du projet |
| `develop` | Intégration des développements |
| `feature/*` | Développement de fonctionnalités |
| `fix/*` | Correction d'anomalies |
| `docs/*` | Mise à jour de la documentation |

### Conventions de commits

Utilisation recommandée de [Conventional Commits](https://www.conventionalcommits.org/).

```text
feat: add leave request management
fix: correct planning display
refactor: improve authentication service
test: add leave request tests
docs: update installation guide
chore: update dependencies
```

### Contribution

1. Créer ou sélectionner une issue correspondant à la tâche.
2. Créer une branche dédiée depuis `develop`.
3. Développer et tester les modifications.
4. Réaliser des commits explicites.
5. Ouvrir une Pull Request vers `develop`.
6. Faire relire et valider les modifications avant fusion.

## Sécurité et protection des données

La plateforme étant destinée à traiter des données RH, une attention particulière sera portée aux points suivants :

- Authentification sécurisée et contrôle des accès.
- Confidentialité des données personnelles.
- Validation des données et des autorisations côté serveur.
- Protection des secrets et des variables d'environnement.
- Utilisation de données fictives pour les tests et démonstrations.
- Prise en compte des exigences du RGPD dès la conception.

Aucune donnée personnelle réelle ni aucun secret ne doit être ajouté au dépôt Git.

Le projet constitue un démonstrateur pédagogique et ne doit pas être considéré comme prêt pour une utilisation en production sans vérifications techniques, juridiques et de sécurité complémentaires.

## Équipe projet

| Pôle | Missions |
| --- | --- |
| Gestion de projet | Coordination, priorisation et suivi des livrables |
| Développement | Architecture, implémentation, intégration et tests |
| Création & Design | Recherche UX/UI, maquettes et design system |
| Marketing & Communication | Étude de marché, benchmark et positionnement |
| Audiovisuel | Documentation et valorisation du projet |

## Licence

Licence et conditions de diffusion à définir avec l'équipe projet.

---

Projet pédagogique — Ydays 2026-2027.
