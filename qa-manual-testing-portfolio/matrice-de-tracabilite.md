# Matrice de traçabilité – Application de réservation

Cette matrice relie les exigences aux cas de test et aux anomalies, afin d'assurer une couverture complète et la traçabilité des tests.

| Exigence | Description | Cas de test | Anomalie liée | Statut |
| --- | --- | --- | --- | --- |
| REQ-01 | Créer une réservation valide | TC-001 | — | Couvert |
| REQ-02 | Refuser une date de fin antérieure à la date de début | TC-002 | — | Couvert |
| REQ-03 | Modifier une réservation existante | TC-003 | — | Couvert |
| REQ-04 | Annuler une réservation et la retirer du tableau de bord | TC-004 | BUG-002 | Anomalie ouverte |
| REQ-05 | Gérer les dates limites (ex. 29 février, année bissextile) | TC-002 | BUG-001 | Anomalie ouverte |

Légende : Couvert = conforme · Anomalie ouverte = couvert mais défaut en cours · Non couvert = à tester.
