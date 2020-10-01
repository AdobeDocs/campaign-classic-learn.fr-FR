---
title: Panneau de contrôle
seo-title: Panneau de contrôle
description: Le panneau de contrôle permet de surveiller et de gérer votre capacité de stockage SFTP par instance et d’ajouter des adresses IP aux listes autorisées.
seo-description: Le panneau de contrôle permet de surveiller et de gérer votre capacité de stockage SFTP par instance et d’ajouter des adresses IP aux listes autorisées.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 98%

---


# [!UICONTROL Panneau de contrôle]

>[!NOTE]
>
>Les termes « [!UICONTROL liste blanche] » et « [!UICONTROL liste noire] » ont été remplacés par les termes « [!UICONTROL liste autorisée] » et « [!UICONTROL liste bloquée] » dans la documentation d’Adobe Campaign.
>Certaines occurrences de ces termes peuvent toujours figurer dans l’interface utilisateur du produit, les noms d’option, le code interne, ainsi que dans les tutoriels vidéo. Ils seront remplacés dans les prochaines versions du panneau de contrôle.

Le [!UICONTROL panneau de contrôle] permet aux administrateurs Adobe Campaign de surveiller les ressources essentielles et d’effectuer des tâches administratives, comme gérer la capacité de stockage SFTP par instance ou ajouter des adresses IP aux [!UICONTROL listes autorisées].

## Accès au [!UICONTROL panneau de contrôle]

Pour accéder au panneau de contrôle, rendez-vous sur la page d’accueil Experience Cloud : [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com) :

* **[!UICONTROL Accueil Experience Cloud]** > **[!UICONTROL Accès rapide]**

   ou
* **[!UICONTROL Accueil Experience Cloud]** > [!UICONTROL Sélecteur de solution] : **Campaign** > Carte **[!UICONTROL panneau de contrôle]**

   ou

* Directement à partir de l’URL : [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Conditions préalables requises

Avant de commencer, remplissez les conditions préalables suivantes :

### Confirmer [!DNL IMS Org ID]

Vous devez connaître votre [!DNL IMS org ID]. La vidéo ci-dessous montre où vous pouvez trouver l’[!DNL IMS org ID] de votre instance.

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Vérification[!DNL IMS Org ID](00:26 min)*

### Droits d’administrateur

Les droits d’administrateur sont requis pour accéder au [!UICONTROL panneau de contrôle].
La vidéo ci-dessous explique comment ajouter un administrateur à une instance Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Comment ajouter un administrateur au profil produit « [!UICONTROL Administrateurs] » pour pouvoir utiliser le[!UICONTROL panneau de contrôle](01:03 min)*

## Tutoriels sur le [!UICONTROL panneau de contrôle]

* **Gestion des serveurs SFTP**

   *Découvrez comment surveiller la capacité du serveur, ajouter des adresses IP aux[!UICONTROL listes autorisées]et ajouter des clés SSH*.

   * [Surveillance de la capacité du serveur, ajout d’adresses IP aux listes autorisées et ajout de clés SSH](/help/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Génération d’une clé SSH](/help/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Connexion à un serveur SFTP](/help/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Délégation de sous-domaines](/help/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Découvrez comment déléguer entièrement un sous-domaine à[!UICONTROL Adobe Campaign]*.

* **[Ajout de certificats SSL](/help/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Découvrez comment ajouter des certificats SSL pour sécuriser vos sous-domaines à l’aide du panneau de contrôle.*

* **[Ajout d’autorisations d’URL](/help/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *Découvrez comment ajouter des URL externes à la liste des URL autorisées afin que votre instance puisse s’y connecter.*

* **[ajouter des adresses IP aux listes autorisées](/help/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Découvrez comment configurer de nouvelles connexions à vos instances en ajoutant des plages d’adresses IP[!UICONTROL aux listes autorisées].*

* **[Gestion des enregistrements TXT Google](/help/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Découvrez comment ajouter des enregistrement de vérification de site[!DNL Google TXT]aux sous-domaines utilisés pour envoyer des emails aux adresses[!DNL GMAIL]par le biais du[!UICONTROL panneau de contrôle Campaign].*

* **Gestion des clés GPG**

   *Découvrez comment générer et installer une paire de clés publique/privée sur une instance Campaign spécifiée pour le cryptage des données sortantes. Apprenez également comment importer et installer une clé publique sur une instance Campaign pour le décryptage des données entrantes :*

   * [Génération et installation de clés GPG pour le cryptage des données](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Utilisation d’une clé GPG pour crypter des données](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Décryptage des données](./gpg-key-management/decrypting-data.md)

* **[Résolution des problèmes du panneau de contrôle](/help/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Comprendre comment résoudre les problèmes du[!UICONTROL panneau de contrôle]*

## Autres ressources

* [Centre d&#39;aide relatif au panneau de contrôle](https://docs.adobe.com/content/help/fr-FR/control-panel/using/control-panel-home.html)