# Cas de test – Application de réservation

| ID | Fonctionnalité | Description | Étapes | Résultat attendu |
| --- | --- | --- | --- | --- |
| TC-001 | Création de réservation | Vérifier qu'un utilisateur peut créer une réservation valide | 1. Se connecter avec un compte valide ; 2. Sélectionner des dates disponibles ; 3. Confirmer la réservation. | La réservation est créée et apparaît dans le tableau de bord. |
| TC-002 | Dates invalides | Tenter de réserver avec une date de fin avant la date de début | 1. Se connecter ; 2. Sélectionner une date de fin antérieure ; 3. Soumettre la demande. | Un message d'erreur indique que la date est invalide. |
| TC-003 | Modification de réservation | Modifier une réservation existante et vérifier la mise à jour | 1. Se connecter ; 2. Ouvrir une réservation existante ; 3. Modifier les dates ; 4. Sauvegarder. | Les nouvelles dates sont enregistrées et affichées correctement. |
| TC-004 | Annulation | Annuler une réservation et vérifier sa suppression | 1. Se connecter ; 2. Ouvrir une réservation ; 3. Cliquer sur "Annuler" ; 4. Confirmer. | La réservation disparaît de la liste et un email de confirmation est envoyé. |

Ces cas de test peuvent être étendus pour couvrir des scénarios négatifs et des tests exploratoires.
