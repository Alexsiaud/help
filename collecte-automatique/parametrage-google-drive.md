---
description: 
priority: 
chatbot_keywords: 
---

# Paramétrage Google Drive

### <sup>**Prérequis et Permissions**</sup>

{% hint style="success" %}
Seul un utilisateur ayant le droit [**Autoriser l’accès au paramétrage de la collecte**](../administration/detail-des-droits.md) peut créer un canal de collecte Google Drive
{% endhint %}

***

### <sup>**Contexte et Recommandations**</sup>

Google Drive permet de réceptionner automatiquement des documents déposés dans le cloud par vos clients. Cette solution est adaptée pour :

***

**Quand l'utiliser :**

* Collecte automatisée de documents clients récurrents

**Quand NE PAS l'utiliser :**

* Pour des envois ponctuels ou urgents (collecte une fois par jour uniquement)

{% hint style="warning" %}
Important : Un document collecté ne sera pas récupéré une seconde fois, même s'il reste dans l'espace de dépôt.
{% endhint %}

***

### <sup>Vidéo interactive 💡</sup>

{% @arcade/embed url="https://app.arcade.software/share/7zXHcTuYxlw1H4A2fhum" flowId="7zXHcTuYxlw1H4A2fhum" %}

***

### <sup>**Préparer la connexion**</sup>

{% hint style="info" %}
Vous devrez disposer des identifiants du compte Google du client ou faire une demande au propriétaire du compte.
{% endhint %}

**Critères obligatoires :**

* Disposer des identifiants de connexion Google du client
* Le client doit être créé comme utilisateur dans la plateforme (utilisateur EXTERNE si nécessaire)
* Définir le classeur de destination pour le dépôt des documents

***

### <sup>**Créer le canal de collecte Google Drive**</sup>

{% hint style="info" %}
L'enregistrement ouvrira automatiquement un navigateur pour la connexion Google.
{% endhint %}

1. Depuis votre compte INGENEO, rendez-vous dans le menu Entreprise.
2. Accédez à la section Collecte puis cliquez sur Nouveau canal.
3. Sélectionnez Google Drive comme type de canal.
4. Saisissez les identifiants Google requis.
5. Choisissez le dossier de dépôt de documents dans l'encart "Configuration des répertoires récupérés".

{% hint style="info" %}
Le dossier réservé au dépôt devient automatiquement visible dans le Google Drive du client.
{% endhint %}

***

### <sup>**Exécuter la collecte**</sup>

#### **Collecte automatique**

La collecte s'effectue **automatiquement une fois par jour**.

#### **Collecte manuelle**

Possibilité d'exécuter manuellement depuis :

* La liste des canaux de collecte : bouton **Exécuter manuellement le processus de collecte**
* L'édition du canal, page **Exécution**

{% hint style="info" %}
Une confirmation sera demandée avant l'exécution manuelle.
{% endhint %}

***

### <sup>**Questions fréquentes**</sup>

**Vous souhaitez consulter l'historique des collectes ?**

Depuis le menu **Collecte**, cliquez sur **Historique** pour voir toutes les collectes effectuées.

**Vos documents ne sont pas collectés ?**

Vérifiez que le client a bien accepté la connexion et que les documents sont dans le bon dossier de dépôt.

**Vous voulez modifier les paramètres de collecte ?**

Éditez le canal existant depuis la liste des canaux de collecte pour ajuster les options.

***

### <sup>**Avertissement**</sup>

{% hint style="warning" %}
Les documents collectés passent automatiquement par l'OCR et sont disponibles dans la bannette de l'entreprise, prêts pour la saisie.
{% endhint %}

{% hint style="warning" %}
Un document collecté ne sera jamais récupéré une seconde fois, même s'il reste dans l'espace de collecte.
{% endhint %}
