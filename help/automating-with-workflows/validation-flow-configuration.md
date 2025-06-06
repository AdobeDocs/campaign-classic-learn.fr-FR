---
title: Configuration des workflows de validation dans Adobe Campaign Classic
description: Découvrez comment configurer différents workflows de validation.
feature: Workflows, Approvals
jira: KT-1566
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 96%

---


# Création de workflows de validation

Adobe Campaign offre plusieurs options aux spécialistes marketing pour examiner et fournir le contenu des diffusions, la cible des campagnes, l&#39;extraction des données et les validations de budget.

Ce tutoriel explique comment configurer différents workflows de validation.

## Prérequis {#prerequisite}

Avant d&#39;activer les étapes de validation, l&#39;équipe marketing doit définir les différents validants :

* Le rôle de validant Adobe Campaign dans une activité de validation peut être soit un seul validant (opérateur), soit un groupe de validants (rôle opérateur).
* Pour permettre aux développeurs de campagnes de sélectionner les validants dans une campagne ou une diffusion, les validants et groupes de validants doivent être configurés dans Adobe Campaign par un administrateur.

## Configuration des validations pour les campagnes   {#configuring-approvals-for-campaigns}

Si vous disposez du même jeu de validants pour toutes les diffusions de votre workflow de campagne, appliquez la fonctionnalité de validation de la campagne, en configurant les validations et les validants au niveau de la campagne. Les tâches de validation et les validants sont redirigés vers chaque activité de diffusion de votre workflow une fois celui-ci exécuté.

>[!VIDEO](https://video.tv.adobe.com/v/30230?quality=12&learn=on&captions=fre_fr){transcript=true}

## Configuration des validations pour les diffusions   {#configuring-approvals-for-deliveries}

Vous pouvez également configurer les validations au niveau de la diffusion. Si les étapes de validation des diffusions et les validants diffèrent des étapes de validation de le la campagne et des validants, les paramètres de la diffusion remplacent les paramètres de la campagne.

>[!VIDEO](https://video.tv.adobe.com/v/27477?quality=12&learn=on&captions=fre_fr){transcript=true}

## Configuration d&#39;une activité de validation   {#configuring-an-approval-activity}

Contrairement aux validations de diffusion ou de campagne, l&#39;activité de validation permet de créer un processus de validation au sein d&#39;un workflow. Ainsi, la logique de sélection du ciblage peut être validée avant le lancement de la diffusion. Cela permet également la validation à plusieurs niveaux dans le workflow, si nécessaire.

>[!VIDEO](https://video.tv.adobe.com/v/27482?quality=12&learn=on&captions=fre_fr){transcript=true}

Pour plus d&#39;informations, consultez la [documentation sur la validation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=fr).
