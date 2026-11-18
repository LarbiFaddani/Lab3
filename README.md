# Lab 3 — Stratégie de recherche bibliographique

## Sujet de recherche

**Blockchain-Enabled Trustworthy Federated Learning for Secure and Privacy-Preserving Collaborative AI**

## Objectif du travail

Ce lab vise à préparer une stratégie de recherche bibliographique pour une revue systématique de la littérature (SLR). Le travail consiste à définir les concepts du sujet, identifier leurs mots-clés et synonymes, puis construire une requête utilisant les opérateurs booléens **AND** et **OR**.

## 1. Définition des concepts

| Concept | Définition dans le cadre du sujet |
|---|---|
| **C1 — Blockchain** | Technologie de registre distribué étudiée pour renforcer la traçabilité, l'intégrité et la confiance. |
| **C2 — Federated Learning** | Approche d'apprentissage collaboratif où les données brutes restent distribuées chez les participants. |
| **C3 — Security, Privacy & Trust** | Propriétés à examiner : sécurité, confidentialité, confiance et fiabilité du système. |

## 2. Mots-clés, synonymes et variantes

| Concept | Mot-clé principal | Synonymes et termes associés | Acronymes / variantes |
|---|---|---|---|
| **Blockchain** | Blockchain | Distributed Ledger, Distributed Ledger Technology, Blockchain Technology | DLT, Block-chain |
| **Federated Learning** | Federated Learning | Federated Machine Learning, Collaborative Learning, Decentralized Federated Learning | FL, FML, DFL |
| **Sécurité, confidentialité et confiance** | Security, Privacy, Trust | Data Privacy, Data Protection, Trustworthiness, Robustness, Data Integrity, Secure Aggregation | DP (Differential Privacy), PPFL (Privacy-Preserving Federated Learning) |

Les termes associés ne sont pas tous des synonymes stricts. Ils servent à explorer le vocabulaire scientifique du domaine et doivent être évalués avant leur inclusion dans une requête définitive.

## 3. Requête de recherche proposée

```text
("blockchain" OR "distributed ledger")
AND ("federated learning" OR "federated machine learning")
AND ("security" OR "privacy" OR "trust" OR "data integrity" OR "poisoning attack")
```

**Logique booléenne :** `OR` rassemble des mots-clés alternatifs au sein de chaque concept ; `AND` exige la présence de chacun des trois groupes de concepts.

Cette requête est une **proposition initiale**, non une recherche dont les résultats auraient déjà été validés. Elle doit être adaptée à la syntaxe des bases consultées (notamment IEEE Xplore, Scopus et Web of Science).

## 4. Démarche de validation

1. Exécuter la requête dans une base scientifique et noter **la date, la base, les champs interrogés, les filtres et le nombre de résultats**.
2. Examiner un échantillon de titres et résumés pour mesurer leur pertinence vis-à-vis du sujet.
3. Comparer avec une requête à deux concepts (`Blockchain AND Federated Learning`) afin de vérifier si le troisième groupe exclut des études pertinentes.
4. Ajuster les termes et documenter toute modification de la requête.

**État actuel :** définition des concepts, tableau terminologique et requête proposée. Aucun nombre de résultats ni test de validation n'est affirmé dans ce README.

## 5. Résultat attendu

Une stratégie de recherche **claire, justifiée et reproductible**, utilisable comme point de départ pour l'identification des publications dans la SLR et pour une future analyse bibliométrique.

## Contenu du dépôt

- `README.md` : présentation du sujet, des concepts, des mots-clés, de la requête et de la démarche de validation.
- Le document de lab associé : développement détaillé des concepts et du tableau des mots-clés.
