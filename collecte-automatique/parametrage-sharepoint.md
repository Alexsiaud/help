---
hidden: true
---

# Paramétrage SharePoint

### <sup>**Prérequis & Permissions**</sup>

{% hint style="info" %}
Seul un utilisateur ayant le droit [**Autoriser l’accès au paramétrage de la collecte**](../administration/detail-des-droits.md) créer un canal de collecte Sharepoint.
{% endhint %}

***

### <sup>**Contexte & Recommandations**</sup>

* La collecte automatisée de documents depuis un espace partagé Microsoft
* Le dépôt régulier de documents par vos clients dans un environnement sécurisé
* L'intégration avec les outils Microsoft de votre client

***

### Vidéo interactive 💡[&#xD;](https://app.arcade.software/share/Ekl1mfs0I4ZlmeMQmkoz)

{% @arcade/embed flowId="7zXHcTuYxlw1H4A2fhum" url="https://app.arcade.software/share/7zXHcTuYxlw1H4A2fhum" %}

### <sup>**Préparer l'environnement**</sup>

{% hint style="info" %}
**Une mauvaise configuration du classeur de destination peut entraîner une mauvaise collecte des documents**

**Critères obligatoires avant création :**

* Avoir un classeur de destination créé
* Disposer des identifiants du compte SharePoint associé (requis pour l'authentification de la connexion), à défaut le contact de l’utilisateur détenant les identifiants
{% endhint %}

***

## **Créer le canal de collecte SharePoint**

1. Depuis votre interface, rendez-vous dans **Entreprise** puis sélectionnez l'entreprise concernée.
2. Cliquez sur **Collecte** puis sur **Ajouter**
3. Sélectionnez **SharePoint** dans le menu déroulant **Type**
4. Saisissez un **libellé** descriptif pour identifier le canal
5. Paramétrez les options de collecte souhaitées (actions automatiques, rotation, détection page blanche, découpe)
6. Cliquez sur **Enregistrer**

{% hint style="info" %}
**Une fenêtre de connexion SharePoint s'ouvrira automatiquement - gardez vos identifiants à portée de main. Finaliser la connexion SharePoint.**
{% endhint %}

{% hint style="info" %}
**Sans validation de la connexion SharePoint, le canal ne pourra pas collecter de documents.**
{% endhint %}

### **Si vous avez les identifiants SharePoint :**

1. Renseignez les champs de connexion dans la fenêtre qui s'est ouverte
2. Validez la connexion

### **Si vous n'avez pas les identifiants :**

1. Créez l'utilisateur dans Paramètres / Utilisateurs si nécessaire
2. Cliquez sur **Cliquer-ici pour envoyer une demande de connexion à un utilisateur**
3. Sélectionnez l'**utilisateur** ayant les accès
4. L’utilisateur va recevoir une notification et pourra renseigner ses identifiants

{% hint style="info" %}
**Vous pouvez tester la collecte manuellement via "Exécuter manuellement le processus de collecte".**
{% endhint %}

***

## **Questions fréquentes**

### **Vous ne trouvez pas l'utilisateur dans la liste ?**

Créez-le dans le menu Administration de votre entreprise, puis cliquez sur **+** pour créer un nouvel utilisateur.

### **Vous voulez consulter l'historique des collectes ?**

Rendez-vous dans **menu Collecte** puis cliquez sur **Historique** pour voir tous les documents réceptionnés.
