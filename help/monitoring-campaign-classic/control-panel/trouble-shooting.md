---
title: Résolution des problèmes du Panneau de contrôle
description: Le Panneau de contrôle permet de surveiller et de gérer votre espace de stockage SFTP par instance et d'ajouter des adresses IP aux listes autorisées.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: fd6e6e36-54e4-4f1a-96fc-1a750e400d50
    internal-label: Campaign Classic v7
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
source-git-commit: d4d4654e5b2dee85947373b8dcf139754844b316
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 81%
---

# Résolution des problèmes du [!UICONTROL Panneau de contrôle]

## Connexion et page d&#39;accueil

### Symptôme : impossible de se connecter à Experience Cloud

**Que faire :**
L’utilisateur ou l’utilisatrice doit rechercher l’ID d’organisation IMS (xxx). L&#39;administrateur doit ajouter l&#39;utilisateur au profil de produit « Campaign-xxx-Admins » pour chaque instance qu&#39;il souhaite gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;utilisateur.

### Symptôme : dans la page d&#39;accueil Experience Cloud, les liens permettant d&#39;accéder au [!UICONTROL Panneau de contrôle] ne sont pas visibles pour un utilisateur.

**Cause :**
Les utilisateurs ne verront pas les liens tant qu’ils ne seront pas ajoutés en tant qu’utilisateurs au profil de produit _Campaign-xxx-Administrators/Admin_.

**Que faire :**
L’administrateur ou l’administratrice doit ajouter l’utilisateur ou l’utilisatrice au profil de produit _Campaign-xxx-Admins_ pour chaque instance à gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;utilisateur.

### Symptôme : une instance n&#39;est pas répertoriée dans le [!UICONTROL Panneau de contrôle]

**Cause :**
L’utilisateur doit probablement être ajouté en tant que profil de produit « utilisateur » _Campaign-xxx-Administrators/Admin_ pour l’instance qui est absente.

**Que faire :**
L’administrateur ou l’administratrice doit ajouter l’utilisateur ou l’utilisatrice au profil de produit _Campaign-xxx-Admins_ pour chaque instance à gérer. Si l&#39;utilisateur est un administrateur de toutes les instances, il doit s&#39;ajouter en tant qu&#39;&quot;utilisateur&quot;.

### Vidéos utiles

>[!VIDEO](https://video.tv.adobe.com/v/34941?captions=fre_fr&quality=12&learn=on){transcript=true}

*Vérification de l&#39;ID org. IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/34775?captions=fre_fr&quality=12&learn=on){transcript=true}

*Comment ajouter un administrateur aux administrateurs de profil de produit pour pouvoir utiliser le [!UICONTROL Panneau de contrôle] (01:03 min)*

### Documentation utile

* [Découvrir le panneau de contrôle](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)
* [Gestion des autorisations pour le [!UICONTROL Panneau de contrôle]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)

## Établissement de la connexion au serveur SFTP (client ou API)

La connexion aux serveurs SFTP requiert les actions suivantes :

* [!UICONTROL Ajout à la liste autorisée] de l&#39;adresse IP à partir de laquelle vous vous connectez au serveur SFTP
* Paire de clés privée/publique devant être enregistrée auprès d&#39;Adobe Campaign
* Si vous vous connectez directement au serveur SFTP, vous aurez également besoin du logiciel client SFTP.

### Documentation utile {#helpful-docs}

* [Connexion à votre serveur SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr)

