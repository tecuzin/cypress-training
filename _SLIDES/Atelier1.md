---
marp: true
---

# Communauté testeurs - Atelier Cypress #1

Mise en pace de l'environnement et premiers tests

---

## Agenda

- Pourquoi cet atelier ?
- Installation et présentation des logiciels utilisés
- Premiers pas
- Un premier exemple

---

## Pourquoi cet atelier

- La stratégie de tests web comprend des tests :
  - De composants
  - D’intégration
  - De « mini-services »
  - D'API
- De nouveaux outils sont donc en cours d’évaluation pour prendre en charge ces tests

---

## Prérequis

- NodeJS : le framework sur lequel est construit Cypress
- Visual Studio code, un éditeur de code bien pratique avec des plugins Cypress pour vous aider dans la rédaction des tests
- Les sources de cet atelier : https://github.com/izadro/cypress-training

---

## Initialisation du projet et premier lancement

- Créer un dosier pour votre projet
- Ouvrir le dossier dans Vscode
- `npm install cypress –save-dev`
- `npx cypress open`
Cette dernière commande créé les dossiers de base dans l'arborescence du projet et ouvre la fenêtre de lancement des tests,il est possible de demander la création d'un projet d'example
---

## Lecture de quelques scénarios

- Structure d'une spécification de test
- Les commandes Cypress
- Les différents types de tests

---

## Atelier

- Choisir un site à tester
- Créer une première spec permettant de vérifier :
- La présence des éléments du *DOM* dans la page
- Le bon chargement de la page
- Le remplissage de quelque champs

DOM : La hiérarchie des objet composants une page

---

## Prochain atelier

- On continue les tests
- Organiser les tests
- Créer ses propres commandes Cypress

---


## Merci :)