---
description: Paramétrage OneDrive
priority: 6
chatbot_keywords: 
  - paramétrage
  - onedrive
  - récupération
  - documents
  - cloud
---

# Paramétrage OneDrive

### <sup>**Prérequis & Permissions**</sup>

{% hint style="success" %}
Seul un utilisateur ayant le droit [**Autoriser l’accès au paramétrage de la collecte**](../administration/detail-des-droits.md) peut créer un canal de collecte One Drive.
{% endhint %}

***

### <sup>**Contexte et Recommandations**</sup>

OneDrive est adapté pour la collecte automatisée de documents déposés dans le cloud. Les collectes s'effectuent une fois par jour automatiquement.

***

**Quand l'utiliser :**

* Import régulier de documents clients
* Dépôt sécurisé de pièces comptables
* Automatisation de la collecte documentaire

***

### <sup>**Informations importantes**</sup>

* Un document collecté ne sera jamais collecté une seconde fois, même s'il reste dans l'espace
* Collecte automatique limitée à une fois par jour
* Nécessite un compte OneDrive valide

***

### <sup>Vidéo interactive 💡</sup>

{% @arcade/embed url="https://app.arcade.software/share/7zXHcTuYxlw1H4A2fhum" flowId="7zXHcTuYxlw1H4A2fhum" %}

### <sup>**Préparer l'environnement**</sup>

{% hint style="info" %}
Assurez-vous d'avoir les identifiants du compte One Drive avant de commencer la configuration. Sans ces informations, vous devrez faire une demande au propriétaire du compte.
{% endhint %}

**Critères obligatoires :**

* Utilisateur destinataire créé dans la plateforme
* Classeur de destination défini

***

### <sup>**Créer le canal de collecte One Drive**</sup>

**La sauvegarde ouvrira automatiquement un navigateur pour la connexion Google. Préparez vos identifiants.**

1. Depuis la plateforme, accédez à la gestion des canaux de collecte.
2. Cliquez sur **Créer un canal** et sélectionnez **OneDrive** comme type de canal.
3. Saisissez les identifiants OneDrive requis.
4. Définissez le classeur de destination pour le dépôt des documents.
5. Validez la création du canal.
6. Le client reçoit une notification pour connecter OneDrive.

***

### <sup>**Gestion des collectes**</sup>

La collecte automatique s'effectue **une fois par jour**.

**Pour une collecte manuelle :**

1. Depuis la liste des canaux de collecte, cliquez sur "**Exécuter manuellement le processus de collecte**"
2. Confirmez l'exécution en cliquant sur "**Confirmer l'exécution du process**"
3. Un message de confirmation indiquera la bonne réception

**Consulter l'historique :**

Menu **Collecte** > **Historique** pour visualiser toutes les collectes effectuées

***

### <sup>**Questions fréquentes**</sup>

**Vous souhaitez vérifier l'état des collectes ?**

Rendez-vous dans **Collecte** > **Historique** pour consulter l'historique complet des réceptions.

**Vous ne trouvez pas l'utilisateur dans la liste ?**

Créez d'abord cet utilisateur dans **Administration** > **Utilisateur**.

**Vous voulez modifier la fréquence de collecte ?**

La collecte automatique est fixée à une fois par jour. Utilisez la collecte manuelle pour des besoins ponctuels.

**Vous ne recevez plus de documents ?**

Vérifiez que la connexion OneDrive est toujours active en éditant le canal de collecte. Un document déjà collecté ne sera jamais collecté une seconde fois.

***

### <sup>**Avertissement**</sup>

{% hint style="warning" %}
**Les documents réceptionnés sont automatiquement traités par l'OCR et disponibles dans la bannette de l'entreprise pour la saisie.**
{% endhint %}
