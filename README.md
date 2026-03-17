# Exercice sur les tests unitaires en programmation orientée objet

## Consignes

Créez une classe `CompteBancaire` et sa classe de test.

1. Créez une classe `CompteBancaire` avec un `solde` initialisé dans le constructeur
2. Créez les méthodes `deposer(montant)` et `retirer(montant)`
3. Créez une exception `SoldeInsuffisantError(Exception)`
4. La méthode `retirer` doit lever la nouvelle exception si le retrait est impossible parce que le solde est insuffisant.
5. Écrivez la classe `TestCompteBancaire` en utilisant `setUp` pour créer un compte bancaire `self._compte = CompteBancaire(100)`

## Cas à tester

- Un dépôt augmente le solde
- Un retrait diminue le solde
- Un retrait impossible lève une exception
- Calcul du solde après un dépôt et un retrait
