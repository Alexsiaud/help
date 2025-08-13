---
description: Créer une entreprise, un nouveau dossier
priority: 7
chatbot_keywords: 
  - dossier
  - entreprise
  - code dossier
  - site par defaut
  - nouveau dossier
---

# Créer une entreprise

### <sup>**Prérequis & Permissions**</sup>

{% hint style="success" %}
Seul un utilisateur ayant le droit [**Autoriser la création d’entreprise**](../administration/detail-des-droits.md) sera en mesure de créer de nouvelles entreprises
{% endhint %}

***

### <sup>**Contexte & Recommandations**</sup>

La création d'une entreprise permet d'initialiser un nouveau dossier comptable.

Cette action est nécessaire avant de pouvoir traiter les factures ou accéder aux [paramètres avancés](parametrages-generaux.md).

***

### <sup>Vidéo interactive 💡</sup>

{% @arcade/embed url="https://app.arcade.software/share/Ekl1mfs0I4ZlmeMQmkoz" flowId="Ekl1mfs0I4ZlmeMQmkoz" %}

***

### <sup>**Créer l'entreprise**</sup>

{% hint style="danger" %}
Le code dossier doit être identique à celui du logiciel comptable pour permettre la migration des données.
{% endhint %}

{% hint style="warning" %}
Assurez-vous d'avoir le fichier FEC à jour avant de commencer la procédure.
{% endhint %}

Depuis votre interface principale, suivez ces étapes :

1. Dans le menu de gauche, cliquez sur **Entreprise**
2. Cliquez sur **Ajouter**
3. Dans la page **Généralités**, renseignez tous les champs requis
4. Le champ **Code dossier** doit être identique à celui du logiciel comptable
5. Si vous n’avez pas créé de site, sélectionnez **site par défaut**
6. Cliquez sur **Suivant.**
7. Importer un fichier **FEC** (recommandé)
8. Les libellés d'écriture sont proposés par défaut et modifiables par clic droit dans leurs champs respectifs afin de choisir les variables d’automatisation
9. Cliquez sur **Enregistrer** en bas de page

{% hint style="success" %}
Importer un FEC permet la création des [référentiels comptables](referentiels-comptables.md) (codes journaux, comptes de tiers et comptes comptables) mais il permet aussi de récupérer les occurrences afin de permettre à la plateforme de faire des propositions de saisie adaptées dès le démarrage de la saisie.
{% endhint %}

***

#### **Option : Sélectionner un modèle de dossier**

{% hint style="warning" %}
La [création du modèle](../administration/modeles-dentreprises.md) doit être effectuée avant la création de l’entreprise.
{% endhint %}

1. Sélectionnez dans le menu déroulant le modèle désiré
2. Activez le ou les différents imports souhaités
3. Cliquez sur **Enregistrer**

***

### <sup>**Finaliser la création**</sup>

* Après l'enregistrement, sélectionnez l'action souhaitée dans le menu :
  * **+ … puis créer une nouvelle entreprise**
  * **+ … puis traiter les factures**
  * **+ … puis accéder aux paramètres avancés**

***

### <sup>**Questions fréquentes**</sup>

#### **Vous souhaitez migrer des données depuis votre logiciel comptable ?**

Utilisez l'option d'import FEC qui permet une migration complète et automatique des écritures comptables existantes.

#### **Vous rencontrez des erreurs lors de l'import du fichier FEC ?**

Vérifiez que le fichier FEC est au bon format et que les codes journaux sont bien présents.

#### **Vous voulez modifier les paramètres après création ?**

Accédez aux [paramètres avancés](parametrages-generaux.md) de l'entreprise via le menu entreprise.

***

### <sup>**Avertissement**</sup>

{% hint style="warning" %}
Une fois l'entreprise créée, assurez-vous de vérifier la cohérence des données importées avant de commencer le traitement des factures.
{% endhint %}
