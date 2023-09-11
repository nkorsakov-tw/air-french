# unTill Payments

--------

<table data-card-size="large" data-view="cards" data-full-width="false"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Qui peut utiliser cette fonctionnalité ?</strong></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2714">✔</span><mark style="color:green;">Propriétaire de l'Emplacement</mark> dans le Back Office</td><td></td></tr></tbody></table>

## Qu'est-ce que d'unTill Payments?

unTill Payments est une intégration des produits unTill Air avec la plateforme Adyen, conçue pour améliorer le processus de paiement en ajoutant plus de commodité.

L'avantage principal de l'utilisation d'unTill Payments réside dans son approche du partage des finances de chaque transaction de paiement.

En combinant les produits unTill Air avec les fonctionnalités de la plateforme Adyen, l'unTill Payments optimise le processus de paiement en général.

## Prérequis pour utiliser l'unTill Payments

Pour travailler avec unTill Payments, vous devez accepter le système de monétisation, qui est décrit ci-dessous, et accepter d'utiliser des terminaux de paiement spécifiques pour effectuer les transactions. Les paiements unTill supportent une large gamme de méthodes de paiement différentes, y compris :

- Maestro
- Mastercard
- VPay
- Visa
- Banonact
- Girocard
- Et plus...

### Deux types de taux

Dans l'unTill Payments, deux types de taux existent :

- Taux de traitement (en €)
- Taux d'acquéreur (en %)

Lorsqu'un client au restaurant paie sa facture, le processus de transfert des finances commence. Le montant du compte du client est dirigé vers la plateforme Adyen, où il est sécurisé jusqu'à ce que le processus de division ait lieu et que les paiements soient exécutés. Durant la division, les taux correspondants sont déduits du montant total et ensuite alloués aux 'Comptes de solde' des parties concernées au sein de la plateforme Adyen.

### Types d'abonnements

Dans l'unTill Payments, la division des montants est déterminée soit par les valeurs des taux spécifiées par votre Revendeur dans le Portail du Revendeur, soit par les taux par défaut.

Les abonnements dans unTill Air sont divisés en :

- Abonnement hébergé
  - Le Propriétaire de l'Emplacement a été invité à unTill Air par le Revendeur d'Air et travaille avec le Revendeur de Paiements au sein de l'Emplacement de Paiement
- Abonnement direct
  - Le Propriétaire de l'Emplacement a organisé un abonnement sans l'aide du Revendeur d'Air et travaille au sein de l'Emplacement de Paiement avec l'aide du représentant unTill

### Diviser le montant

{% tabs %}
{% tab title="Abonnement hébergé" %}
Parties de la division :

- unTill
- Revendeur
- Propriétaire de l'Emplacement

Les valeurs des taux sont déterminées par le Revendeur de Paiements sur la base des accords avec le Propriétaire de l'Emplacement.
{% endtab %}

{% tab title="Abonnement direct" %}
Parties de la division :

- unTill
- Propriétaire de l'Emplacement

Les taux ont les valeurs par défaut.
{% endtab %}
{% endtabs %}

En fonction des taux convenus pour les taux de traitement et les taux d'acquéreur, la division distribue des portions spécifiques du montant à chaque participant et les crédite sur leurs 'Comptes de solde' correspondant.

Selon la méthode de paiement choisie par votre client, la plateforme Adyen calcule les taux de paiement après un retard. Ces taux seront ensuite déduits de votre 'Compte de solde' avant le traitement du paiement.

Après le processus de division, en tant que Propriétaire de l'Emplacement, vous recevrez des paiements quotidiens basés sur les transactions du jour. Des factures quotidiennes correspondantes seront fournies pour chaque paiement effectué.

## Propriétaire de l'Emplacement et portail de paiements

Pour utiliser l'unTill Payments, le Propriétaire de l'Emplacement doit d'abord s'inscrire en tant qu'utilisateur d'unTill Payments. Cette inscription peut être réalisée à travers les paramètres du Back Office d'unTill Air.

{% hint style="info" %}
Pour plus de détails sur comment demander l'accès au unTill Payments, [référez-vous à cette page](request-untill-payments.md).
{% endhint %}

Quand le Propriétaire de l'Emplacement a complété le processus pour devenir une partie d'unTill Payments, un système de paiement pratique s'ouvre. Le Portail de Paiements devient leur point crucial pour gérer efficacement tous les aspects liés aux paiements.

De plus, le Portail de Paiements offre des rapports détaillés sur la division des revenus pour vous aider à avoir un meilleur contrôle sur l'état financier de votre entreprise.
