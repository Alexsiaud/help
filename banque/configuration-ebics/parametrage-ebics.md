---
hidden: true
---

# Paramétrage EBICS

### <sup>**Prérequis & Permissions**</sup>

✍️ Seul un utilisateur interne ayant le droit [**Autoriser l’accès au paramétrage de la comptabilité**](../../administration/detail-des-droits.md) peut configurer un dépôt EBICS.

***

### <sup>**Contexte & Recommandations**</sup>

Le paramétrage EBICS permet de configurer l’entreprise pour l'import de mouvements bancaires au format EBICS (cfonb ou OFX). Cette configuration lie un IBAN à l'entreprise et peut fonctionner en mode multi-entreprise.

***

### <sup>**Préparer l'environnement**</sup>

⚠️ Assurez-vous d'avoir les informations bancaires correctes avant de commencer. Une mauvaise configuration peut empêcher l'import des données.

**Critères obligatoires :**

* IBAN valide du compte bancaire
* BIC/SWIFT si disponible
* Classeur de banque créé

***

### Vidéo interactive :bulb:

{% @arcade/embed flowId="0MUKXJNUTLrF7wOJ4gvc" url="https://app.arcade.software/share/0MUKXJNUTLrF7wOJ4gvc" %}

***

### <sup>**Créer la banque**</sup>

⚠️ Le nom de la banque n'impacte pas l'import.

1. Depuis votre compte, rendez-vous dans l’édition de l’**entreprise**.
2. Cliquez sur **Banque**
3. Puis sur **+ Ajouter**
4. Saisissez le nom de la banque et cliquez sur **Enregistrer**

✍️ Le BIC/SWIFT peut être ajouté lors de cette étape si vous le possédez.

***

### <sup>**Ajouter le compte bancaire**</sup>

⚠️ L'IBAN doit être valide et correspondre exactement au compte bancaire concerné.

1. Cliquez sur **+** pour ajouter un compte à la banque créée, puis renseignez les informations suivantes :
   * Libellé du compte
   * Libellé personnalisé
   * Classeur de rattachement
   * IBAN complet
2. Cliquez sur **Enregistrer** pour finaliser la configuration

✍️ La plateforme liera automatiquement cet IBAN à l'entreprise pour permettre les dépôts EBICS multi-entreprise.

***

### <sup>**Questions fréquentes**</sup>

**Vous souhaitez modifier un IBAN déjà configuré ?**

Accédez au menu **Entreprise > Banque**, sélectionnez le compte concerné et modifiez les informations nécessaires.

**Vous rencontrez une erreur lors de la validation de l'IBAN ?**

Vérifiez que l'IBAN est complet (27 caractères pour la France) et ne contient pas d'espaces.

**Vous voulez supprimer une banque ?**

Assurez-vous qu'aucun compte n'y est rattaché avant de procéder à la suppression.
