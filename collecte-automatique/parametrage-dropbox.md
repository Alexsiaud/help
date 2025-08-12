---
hidden: true
---

# Paramétrage Dropbox

### <sub>**Prérequis & Permissions**</sub>

{% hint style="success" %}
Seul un utilisateur ayant le droit [**Autoriser l’accès au paramétrage de la collecte**](../administration/detail-des-droits.md) peut créer un canal de collecte Dropbox.
{% endhint %}

L'utilisateur doit également disposer des identifiants Dropbox du compte ou pouvoir faire une demande au propriétaire du compte.

***

### <sup>**Contexte & Recommandations**</sup>

**Dropbox** est adapté pour la réception automatisée de documents déposés dans le cloud par vos clients. Les collectes s'effectuent une fois par jour automatiquement.

***

**Quand l'utiliser :**

* Import régulier de documents clients
* Dépôt sécurisé de pièces comptables
* Automatisation de la collecte documentaire
* Partage de fichiers volumineux avec vos clients

**Limitations importantes :**

* Un document collecté ne sera jamais collecté une seconde fois, même s'il reste dans l'espace
* Collecte automatique limitée à une fois par jour
* Nécessite un compte Dropbox valide avec identifiants disponibles

***

### <sup>Vidéo interactive 💡</sup>

{% @arcade/embed url="https://app.arcade.software/share/7zXHcTuYxlw1H4A2fhum" flowId="7zXHcTuYxlw1H4A2fhum" %}

### <sup>**Préparer l'environnement**</sup>

**Assurez-vous d'avoir les identifiants Dropbox avant de commencer la configuration. Sans ces informations, vous devrez faire une demande au propriétaire du compte.** **Critères obligatoires :**

* Utilisateur destinataire créé dans la plateforme
* Classeur de destination défini pour organiser les documents reçus

***

### <sup>**Créer un canal de collecte Dropbox**</sup>

1. Accédez au menu **Collecte** puis cliquez sur **Nouveau canal**
2. Sélectionnez **Dropbox** comme type de canal
3. Saisissez les identifiants Dropbox requis
4. Choisissez le dossier de dépôt dans la configuration des répertoires récupérés

***

### <sup>**Gestion des collectes**</sup>

{% hint style="info" %}
La collecte automatique s'effectue **une fois par jour**.
{% endhint %}

Pour une collecte manuelle :

1. Depuis la liste des canaux de collecte, cliquez sur **Exécuter manuellement le processus de collecte**
2. Confirmez l'exécution en cliquant sur **Confirmer l'exécution du process**
3. Un message de confirmation indiquera la bonne réception

***

**Consulter l'historique :**

Menu **Collecte > Historique** pour visualiser toutes les collectes effectuées

***

### <sup>**Questions fréquentes**</sup>

**Vous souhaitez vérifier l'état des collectes ?**

Rendez-vous dans **Collecte > Historique** pour consulter l'historique complet des réceptions.

**Vous ne trouvez pas l'utilisateur Dropbox dans la liste ?**

Créez d'abord cet utilisateur en tant qu'utilisateur externe dans Administration > Utilisateur, puis recommencez la sélection.

**Vous voulez modifier la fréquence de collecte ?**

La collecte automatique est fixée à une fois par jour. Utilisez la collecte manuelle pour des besoins ponctuels.

**Vous ne recevez plus de documents ?**

Vérifiez que la connexion Dropbox est toujours active en éditant le canal de collecte. Un document déjà collecté ne sera jamais collecté une seconde fois.

***

### <sup>**Avertissement**</sup>

{% hint style="warning" %}
Les documents réceptionnés sont automatiquement traités par l'OCR et disponibles dans la bannette de l'entreprise pour la saisie.
{% endhint %}
