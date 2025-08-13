---
description: Paramétrage note de frais
priority: 5
chatbot_keywords: 
  - paramétrage
  - note de frais
  - natures
---

# Paramétrage note de frais

### <sup>**Prérequis et Permissions**</sup>

{% hint style="success" %}
Seuls les utilisateurs ayant le droit [**Autoriser l’accès au paramétrage des processus métier**](../../administration/detail-des-droits.md) pourront paramétrer les notes de frais.
{% endhint %}

***

### <sup>Vidéo interactive 💡</sup>

{% hint style="warning" %}
Le paramétrage des notes de frais nécessite obligatoirement un [**classeur comptable**](../../gestion-des-entreprises/classeurs-comptables.md) de type **Notes de frais**.
{% endhint %}

{% @arcade/embed url="https://app.arcade.software/share/kzNUw3zexuqY7BWa0lZ2" flowId="kzNUw3zexuqY7BWa0lZ2" %}

{% hint style="warning" %}
La création de notes de frais nécessite obligatoirement un [**circuit de validation**](../workflow/circuit-de-validation.md) de type **formulaire**.
{% endhint %}

{% @arcade/embed url="https://app.arcade.software/share/xDllqwOIyhIc5AwHRUBb" flowId="xDllqwOIyhIc5AwHRUBb" %}

***

**Quand l'utiliser :**

* Pour la gestion des remboursements de frais professionnels de collaborateurs
* Lors d’un besoin de validation de dépenses
* Pour automatiser la saisie de notes de frais

**Quand NE PAS l'utiliser :**

* Pour des frais exceptionnels ou ponctuels sans besoin de validation
* Si vous préférez une saisie comptable directe

***

### <sup>**Préparer l'environnement**</sup>

{% hint style="info" %}
Une mauvaise configuration initiale entraînera des erreurs de saisie et des dysfonctionnements dans les circuits de validation.
{% endhint %}

**Critères obligatoires :**

* Définir les comptes comptables HT et TVA pour chaque nature de frais
* Créer au moins un circuit de validation avec des utilisateurs actifs
* Paramétrer le journal comptable par défaut pour le classeur
* Créer et paramétrer les natures de frais

***

### <sup>**Configurer les notes de frais**</sup>

1. Accédez au menu **Entreprise > Plan de classement > Processus métier >** **Circuits de validation**.
2. Cliquez sur **Ajouter** pour créer un nouveau circuit de validation.
3. Choisissez dans le menu déroulant le type **Formulaire** et enregistrez.
4. Indiquez le nom du circuit de validation et le formulaire dédié **Note de frais**.
5. Cochez l'option **Transférer en comptabilité lors de la validation finale** pour envoyer la note de frais dans le classeur comptable.
6. Cliquez sur **Enregistrer**.
7. Indiquez le nom de l'utilisateur, avec la possibilité d'ajouter plusieurs utilisateurs avec le **+**.

{% hint style="success" %}
Si un utilisateur est seul dans son circuit, les notes sont validées automatiquement.
{% endhint %}

***

### <sup>**Questions fréquentes**</sup>

**Vous souhaitez modifier une nature de frais après création ?**

Retournez dans **Entreprise** > **Plan de classement** > **Processus métier** > **Formulaire** et éditez le formulaire concerné.

**Vous ne voyez pas l'onglet Mes notes de frais ?**

Vérifiez que vous êtes bien initiateur d'un circuit de validation de type **Formulaire** et que celui-ci est actif.

**Vous voulez ajouter des validateurs au circuit ?**

Dans **Circuits de validation**, éditez le circuit concerné et utilisez le **+** pour ajouter des utilisateurs supplémentaires.

***

### <sup>**Avertissement**</sup>

{% hint style="warning" %}
Une fois une note de frais validée et transférée, elle ne peut plus être modifiée directement. Toute correction nécessitera une écriture comptable d'ajustement.
{% endhint %}
