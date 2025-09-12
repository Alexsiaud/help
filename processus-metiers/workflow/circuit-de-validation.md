---
priority: 6
chatbot_keywords:
  - circuit
  - validation
  - workflow
---

# Circuit de validation

### <sup>**Prérequis et Permissions**</sup>

{% hint style="success" %}
Un utilisateur ayant le droit [**Autoriser l’accès au paramétrage des processus métier**](../../administration/detail-des-droits.md) peut configurer les circuits de validation. L'utilisation nécessite des rôles spécifiques selon le niveau de validation.
{% endhint %}

***

### <sup>**Contexte et Recommandations**</sup>

Le circuit de validation permet d'automatiser les demandes de validation pour des documents déposés dans des classeurs comptables ou de plan de classement.

### <sup>**Types de circuits de validation**</sup>

* **Prédéfini** : s'appliquent aux classeurs comptables ou de plan de classement
* **Formulaire** : spécifiques aux processus métier [note de frais](../notes-de-frais/) ou [engagement de dépense](../engagement-de-depense/), retrouvez les paramétrages dans les pages dédiées

Il est possible d’appliquer automatiquement des [statuts](configurer-les-statuts-de-documents.md) pendant les circuits de validation. Retrouvez les paramétrages dans la page dédiée.

***

**Quand l'utiliser :**

* Pour digitaliser la validation de documents
* Quand plusieurs niveaux d'approbation sont nécessaires
* Pour tracer le parcours de validation des documents

**Fonctionnalités disponibles :**

* Création de plusieurs niveaux avec différents rôles
* Circuit obligatoire par classeur ou plan de classement

***

### Vidéo interactive 💡

{% @arcade/embed url="https://app.arcade.software/share/ROLF2KrulWbatkcmMctl" flowId="ROLF2KrulWbatkcmMctl" %}

***

### <sup>**Créer un circuit de validation**</sup>

1. Sélectionnez **Circuit de validation** depuis le menu **Processus métier**.
2. Cliquez sur **+ Ajouter** pour créer un nouveau circuit.
3. Nommez le circuit et définissez les niveaux de validation souhaités.
4. Pour chaque niveau, ajoutez les utilisateurs concernés et attribuez-leur un rôle (Initiateur, Valideur, Aiguilleur, Observateur, Gestionnaire).
5. Définissez les conditions et options spécifiques si besoin.
6. Cliquez sur **Enregistrer** pour valider la création du circuit.

***

{% hint style="warning" %}
## Rôles disponibles

* **Initiateur** : Toujours au niveau 1, il initie le circuit de validation mais n’est pas obligé de faire de la saisie comptable pour initier le circuit de validation. Possibilité de définir plusieurs initiateurs au niveau 1.
* **Valideur** : Il valide avec ou sans condition. Si plusieurs valideurs sont au même niveau, le premier qui valide permettra au document de passer à l’étape suivante. Dans le cas de plusieurs valideurs dont un ou plusieurs sont obligés de valider, le document ne passera à l’étape suivante que lorsque tous les valideurs avec obligation auront effectué leur action.
* **Aiguilleur** : Il détermine qui au prochain niveau validera le document. Il faut au moins un niveau supérieur dans ce cas avec au moins deux valideurs.
* **Observateur** : Il peut suivre l'avancement du document à tous les niveaux, mais ne peut agir sur celui-ci.
* **Gestionnaire** : Il peut suivre l'avancement du document à tous les niveaux et il peut agir sur celui-ci de toutes les actions souhaitées et à tous les niveaux.
{% endhint %}

***

### <sup>**Options supplémentaires par utilisateur disponible**</sup>

* Changer le circuit de validation
* Changer le classeur
* Activer la validation par mail (impossibilité de renseigner un commentaire)
* Obliger la saisie analytique
* Obliger la saisie d’une note
* Obliger l’ajout d’une pièce jointe
* Appliquer la signature
* Appliquer le tampon

{% hint style="danger" %}
La suppression d'un circuit en cours d'utilisation peut entraîner la perte de documents en attente de validation
{% endhint %}
