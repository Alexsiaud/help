---
hidden: true
---

# Gestion des BNC - Comptabilité de trésorerie

## 1 – Paramétrage du type de comptabilité

INGENEO vous permet de définir le type de comptabilité de votre entreprise : comptabilité d'engagement ou de trésorerie.

Dans le paramétrage de l'entreprise concernée se rendre dans comptabilité, paramétrage général puis choisir le type de comptabilité.

{% @arcade/embed flowId="e79LbAz94dvvxNKfGypP" url="https://app.arcade.software/share/e79LbAz94dvvxNKfGypP" %}

{% hint style="info" %}
Lorsque le type « Comptabilité de trésorerie » est sélectionné, la saisie n'est alors plus disponible dans votre classeur d'achat.
{% endhint %}

La collecte de la banque peut se réaliser par plusieurs canaux de collecte :

* Redirection des mouvements bancaires issues de votre compte jedéclare.com ;
* Connexionvia Powens ;&#x20;
* Dépôt de fichier bancaire au format CFONB, OFX, QIF ;

Une documentation dédiée à chaque canal est disponible dans le centre d'aide.&#x20;

***

## 2 – Rapprochement documentaire

Pour une comptabilité de trésorerie, l'enregistrement de la saisie passera par le classeur de banque, il faut donc un rapprochement documentaire en amont de la comptabilisation.

{% hint style="warning" %}
**Attention** : une fois le document rapproché au mouvement, ce dernier, même si pas encore exporté, est retiré du classeur d'achat.
{% endhint %}

### 1.1 Suggestion automatique

La suggestion automatique peut s'effectuer jusqu'à la somme de 3 montants de mouvements correspondant à un montant total d'une facture, et inversement.

Dans votre classeur de banque, appuyez sur le bouton de rapprochement de facture.

Le bouton de rapprochement vous propose le code couleur et repère visuel suivant :

* **Jaune** : indique le nombre de factures suggérées par la plateforme.
* **Orange** : indique le nombre de factures rapprochées mais le montant total n'est pas égal à celui du mouvement.
* **Vert** : indique le nombre de factures rapprochées, le montant total est égal à celui du mouvement.

Pour ce mouvement, la plateforme vous propose une suggestion de facture à rapprocher **11**, vous avez la possibilité de la visualiser **12** et de la rapprocher au mouvement **13**.

Le compteur va se mettre à jour en fonction du montant de la ou des factures rapprochées **14**.

### 1.2 Rapprochement manuel

Vous avez la possibilité de visualiser toutes les factures **15**.

{% hint style="warning" %}
⚠️ **Attention** : pour être visible, la date de la facture doit toujours être inférieure à celle du mouvement. Si votre compte fournisseur est reconnu par la plateforme vous avez la possibilité de l'utiliser comme filtre de recherche.
{% endhint %}

Sélectionnez le ou les documents à rapprocher comme vu précédemment.

L'ensemble des mouvements après validation manuelle, semi-automatique ou automatique seront transférés en comptabilité avec le ou les justificatifs associés.

Vous pourrez également retrouver le mouvement et sa facture dans votre menu **Rechercher**.
