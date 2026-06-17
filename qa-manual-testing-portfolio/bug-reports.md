# Rapports d'anomalies – Application de réservation

## BUG-001 – Impossible de créer une réservation au 29 février sur année bissextile

**Contexte** : Lors de la création d'une réservation pour le 29 février 2024, le système retourne une erreur de date invalide.

**Étapes de reproduction** :
1. Se connecter à l'application avec un compte valide.
2. Choisir la date de début au 28 février 2024 et la date de fin au 29 février 2024.
3. Soumettre la réservation.

**Résultat attendu** : La réservation est créée avec succès.

**Résultat obtenu** : Message d'erreur « Date invalide ».

**Sévérité** : Majeure  
**Priorité** : Élevée  

## BUG-002 – Les réservations annulées restent affichées dans le tableau de bord

**Contexte** : Après avoir annulé une réservation, l'entrée reste visible dans le tableau de bord jusqu'à la prochaine actualisation manuelle.

**Étapes de reproduction** :
1. Se connecter.
2. Sélectionner une réservation existante.
3. Cliquer sur « Annuler » et confirmer.
4. Observer le tableau de bord.

**Résultat attendu** : La réservation disparaît immédiatement de la liste sans rafraîchir la page.

**Résultat obtenu** : La réservation annulée reste affichée jusqu'à un rafraîchissement manuel.

**Sévérité** : Mineure  
**Priorité** : Moyenne  
