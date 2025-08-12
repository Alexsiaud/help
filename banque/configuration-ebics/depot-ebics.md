---
hidden: true
---

# Dépôt EBICS

### <sup>**Prérequis & Permissions**</sup>

✍️ Seul un utilisateur avec le droit [**Déposer des documents**](../../administration/detail-des-droits.md) dans le classeur ou l’entreprise peut déposer des documents dans la bannette.

***

### <sup>**Contexte & Recommandations**</sup>

L'import EBICS (Electronic Banking Internet Communication Standard) permet d'intégrer des mouvements bancaires dans INGENEO au format CFONB ou OFX.

***

### <sup>**Quand utiliser cette fonctionnalité :**</sup>

* Quand [l’import POWENS](broken-reference) (scrapping bancaire) ou [JeDéclare](../connecteurs-tiers/parametrage-jedeclare.md) n’est pas possible
* Dépôt de mouvements multi-entreprises

⚠️ Consultez la documentation dédiée au [paramétrage](parametrage-ebics.md) avant de passer au dépôt.

***

### <sup>**Préparer l'environnement**</sup>

⚠️ **Attention** : Un fichier EBICS mal formaté ou corrompu peut provoquer des erreurs d'import.

**Formats compatibles obligatoires :**

* **Format CFONB** : Standard français pour les échanges bancaires, privilégié pour les banques françaises
* **Format OFX** : Format international, compatible avec la plupart des institutions bancaires

***

### Vidéo interactive :bulb:

{% @arcade/embed flowId="ZPuTbQElU2U42wsRPvoa" url="https://app.arcade.software/share/ZPuTbQElU2U42wsRPvoa" %}

***

### <sup>**Importer un fichier EBICS**</sup>

⚠️ **Important** : Assurez-vous d'être dans la bonne entreprise avant l'import pour éviter les erreurs de comptabilisation.

1. Depuis votre interface INGENEO
2. Rendez-vous dans le menu **Bannettes**
3. Sélectionnez le classeur **Banque**
4. Cliquez sur le bouton **+ Ajouter**
5. Recherchez et sélectionnez votre fichier EBICS depuis votre ordinateur
6. Confirmez l'import du fichier

Ou :

* Cliquez sur l’icône « importer un fichier bancaire CFONB / OFX » situé au-dessus de la liste des entreprises

✍️ **Résultat attendu** : Votre fichier EBICS sera traité et les mouvements bancaires seront disponibles pour saisie comptable dans le classeur **Banque**.

***

### <sup>**Questions fréquentes**</sup>

**Votre fichier EBICS n'est pas accepté ?**

Vérifiez que le format est bien CFONB ou OFX. Certaines banques proposent plusieurs formats d'export.

***

### <sup>**Avertissement**</sup>

⚠️ **Gestion des doublons** : L'import d'un même fichier EBICS plusieurs fois peut créer des mouvements en double. Vérifiez vos imports avant validation comptable.
