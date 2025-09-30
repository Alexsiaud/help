# Gestion des mots-clés

#### <sup>**Prérequis & Permissions**</sup>

{% hint style="warning" %}
Seul un utilisateur ayant le droit **Autoriser l'accès à la gestion des mots-clés sur les tiers** peut configurer cette fonctionnalité.
{% endhint %}

***

#### <sup>**Contexte & Recommandations**</sup>

La gestion des mots-clés permet à INGENEO de reconnaître automatiquement un tiers à partir de mots-clés présents dans vos documents.

#### **Critères obligatoires :**

* Profil de site configuré avec autorisation de gestion des mots-clés
* Minimum de 3 saisies effectuées sur le fournisseur concerné

***

### <sup>Vidéo interactive 💡</sup>

{% @arcade/embed flowId="c2Y4jRzqCUnZ93bhcbz4" url="https://app.arcade.software/share/c2Y4jRzqCUnZ93bhcbz4" %}

{% @arcade/embed flowId="Sp4yH8dk7z9lBJBaGVBx" url="https://app.arcade.software/share/Sp4yH8dk7z9lBJBaGVBx" %}

***

#### <sup>**Configurer les droits d'accès**</sup>

1. Depuis votre compte INGENEO, rendez-vous dans **Paramètres**.
2. Cliquez sur **Profils de droits**
3. Sélectionnez **Profils de site**
4. Ajoutez un nouveau profil de site
5. Cochez **Autoriser l'accès à la gestion des mots-clés sur les tiers**
6. Cliquez sur **Enregistrer**

{% hint style="success" %}
Vous pouvez également paramétrer ces droits depuis le menu **Entreprises**.
{% endhint %}

***

#### <sup>**Gérer les mots-clés d'un tiers**</sup>

{% hint style="warning" %}
Le bouton **Gérer les mots-clés du compte tiers** n'apparaît qu'après minimum 3 saisies sur le fournisseur
{% endhint %}

1. Depuis **Bannettes**, accédez au menu de saisie.
2. Lors de la saisie d'un document, indiquez votre compte tiers
3. Cliquez sur **Imputations**
4. Cliquez sur **Gérer les mots-clés du compte tiers**
5. Saisissez vos mots-clés manuellement ou cliquez directement sur les mots du document
6. Cliquez sur **Enregistrer**

{% hint style="success" %}
Une fois configurés, la plateforme proposera automatiquement le compte tiers lors des prochaines saisies.
{% endhint %}

{% hint style="warning" %}
#### <sup>**Voici les limitations imposées par la plateforme :**</sup>

* Les mots-clés de moins de 3 caractères ne seront pas pris en compte
* La condition OU est appliquée pour chaque mot-clé que vous avez renseigné
* Les mots-clés ne doivent pas être des identifiants reconnus automatiquement par OCRLAD, tels que le SIRET, le SIREN, la TVA intracom, le téléphone, le fax, le site web, ou l'IBAN
* Évitez les mots-clés génériques qui peuvent apparaître sur des factures d'autres tiers (ex. : facture, total, carburant, loterie, restaurant...)
{% endhint %}

***

#### <sup>**Questions fréquentes**</sup>

**Vous souhaitez gérer les mots-clés par compte de charge ?**&#x20;

Cette option est disponible directement dans l'interface de gestion des mots-clés après configuration du compte tiers.

**Vos mots-clés ne fonctionnent pas ?**&#x20;

Vérifiez qu'ils respectent les critères : plus de 3 caractères, non génériques, et qu'ils ne correspondent pas à des identifiants automatiquement reconnus.

**Vous voulez optimiser la reconnaissance automatique ?**&#x20;

Évitez les mots génériques (facture, total, carburant) et privilégiez des termes spécifiques au fournisseur.
