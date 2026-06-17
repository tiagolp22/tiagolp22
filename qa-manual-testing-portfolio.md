# Portfolio de tests manuels

Ce dépôt contient un exemple de documentation QA manuelle, démontrant ma capacité à planifier et exécuter des tests sans automatisation.

## Structure

- **Plan de tests** : objectifs, scope, critères d’acceptation, jeux de données, risques.
- **Matrice de traçabilité** : correspondance entre exigences et cas de test.
- **Cas de test** : description, étapes de reproduction, données d’entrée, résultat attendu.
- **Rapports d’anomalies** : identification de bugs, reproduction, résultat attendu vs résultat observé, capture d’écran.

## Exemples

### Plan de tests

```
Objectif : Valider le flux de création de compte pour un site e‑commerce.
Scope : Formulaire d’inscription, validation des champs, message de confirmation.
Critères d’acceptation :
- Tous les champs obligatoires sont validés.
- L’utilisateur reçoit un message de confirmation après inscription.
Jeux de données : utilisateurs valides, adresses e‑mail existantes, mots de passe invalides.
Risques : blocage dû à des validations côté client, incohérences de messages d’erreur.
```

### Matrice de traçabilité (extrait)

| Exigence | Cas de test |
| --- | --- |
| REQ-001 : L’utilisateur doit saisir un e‑mail unique. | TC-001 : Inscription avec e‑mail déjà utilisé → message d’erreur affiché. |
| REQ-002 : Le mot de passe doit comporter au moins 8 caractères. | TC-002 : Inscription avec mot de passe trop court → message d’erreur affiché. |

...
