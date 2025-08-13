---
description: Paramétrage JeDéclare
priority: 5
chatbot_keywords: 
  - paramétrage
  - jedeclare
  - récupération
  - flux
---

# Paramétrage JeDéclare

### <sup>**Prérequis & Permissions**</sup>

{% hint style="success" %}
Seul un utilisateur ayant le droit [**Autoriser l’accès à la configuration de la plateforme**](../../administration/detail-des-droits.md) et le droit **Autoriser l’accès à l’administration de la plateforme** peut effectuer le premier paramétrage de l'API JeDéclare
{% endhint %}

***

### <sup>**Contexte & Recommandations**</sup>

L'API JeDéclare permet de récupérer automatiquement les mouvements bancaires de vos clients via des identifiants de flux JeDéclare.

***

### <sup>**Prérequis obligatoires**</sup>

Posséder un compte de **récupération de flux** JeDéclare

***

### <sup>**Préparer l'environnement**</sup>

{% hint style="info" %}
Le rapprochement des entreprises s'effectue par leurs raisons sociales.
{% endhint %}

***

### <sup>Vidéo interactive 💡</sup>

JeDéclare Administrateur

{% @arcade/embed url="https://app.arcade.software/share/oQ0mr5fyWOGdeIsBogcO" flowId="oQ0mr5fyWOGdeIsBogcO" %}

JeDéclare Entreprise

{% @arcade/embed url="https://app.arcade.software/share/QTqachQltDZ5Hc2WoWKO" flowId="QTqachQltDZ5Hc2WoWKO" %}

***

### <sup>**Configurer l'agrégateur JeDéclare**</sup>

1. Depuis votre compte administrateur, rendez-vous dans le menu **Paramètres**.
2. Sélectionnez **Configuration**, puis cliquez sur **Agrégateurs**. Cliquez sur **+ Ajouter** et sélectionnez **JeDeclare.com**.
3. Renseignez votre compte "**récupérateur de flux**" JeDéclare puis cliquez sur **Enregistrer**
4. Cochez l'activation de l'entreprise souhaitée et cliquez sur **Enregistrer**
5. Une manipulation reste à faire dans l’entreprise, voir la [vidéo intéractive](parametrage-jedeclare.md#video-interactive)

**JeDéclare est maintenant paramétré et opérationnel**

***

### <sup>**Questions fréquentes**</sup>

**Vous n'avez pas de compte récupérateur de flux ?**

Effectuez une demande directement auprès de JeDéclare pour obtenir vos identifiants.

**Le rapprochement des entreprises ne fonctionne pas ?**

Vérifiez que les raisons sociales dans votre système correspondent exactement à celles de JeDéclare.

**Vous souhaitez désactiver une entreprise ?**

Décochez l'activation dans les paramètres de l'agrégateur et enregistrez.

***

### <sup>**Avertissement**</sup>

{% hint style="warning" %}
Seuls les administrateurs peuvent paramétrer les agrégateurs. Le rapprochement s'effectue automatiquement par raison sociale.
{% endhint %}
