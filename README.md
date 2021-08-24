# Schoolab - Test technique - Lead developer

## Introduction

Ce test évalue votre capacité à trouver une solution technique **simple et efficace** à un problème donné. Essayez donc de ne pas y passer plus de **2 ou 3h**. Nous vous laissons le choix des technologies et outils mais celui-ci doit être justifié.

Nous cherchons à évaluer autant votre **compréhension du problème** que votre capacité à le **résoudre techniquement**.

## Instructions

Votre réponse doit comporter 2 éléments :

* La solution technique elle-même
* Un Google Doc (1 page maximum en taille 12) expliquant :
  * Votre compréhension du problème
  * Votre choix d'outils et/ou technologies
  * Les difficultés que vous avez rencontrées

Votre solution technique doit être développée en Ruby ou Javascript et peut utiliser un framework (Rails, Sinatra, Express, Next, etc.). Vous pouvez également vous appuyer sur des outils *no code* s'ils vous permettent de gagner du temps sans impacter l'expérience utilisateur. Dans tous les cas, votre choix devra être justifié dans le Google Doc.

Si votre solution inclut un programme ou une application, vous créerez un repository Github privé et inviterez @pierredemilly en lecture.
Si votre solution inclut un outil SaaS ou no-code, vous indiquerez dans votre Google Doc les liens et/ou identifiants pour y accéder.

## Problème

Dans le contexte sanitaire actuel, les restaurants et bars doivent proposer à leurs clients une expérience dématérialisée. Nous souhaitons donc leur proposer un système de QR code pour permettre aux client d'accéder au menu.

Votre solution doit comporter 2 éléments :
* Un formulaire permettant d'entrer les coordonnées de l'établissement et d'uploader le menu en PDF
* Un système de génération de QR codes uniques et qui renvoient vers le menu PDF de l'établissement.

Chaque établissement doit avoir son propre QR code et doit pouvoir l'imprimer après l'avoir uploadé.
Nous vous laissons définir les coordonnées à demander dans le formulaire.

S'il vous reste du temps, vous pouvez explorer une ou plusieurs fonctionnalités avancées :
* L'établissement reçoit son QR code par email
* Le QR code à imprimer comporte également le nom de l'établissement, son adresse postale, ses horaires, ce qui vous semble utile
* L'établissement peut remplacer son menu PDF sans avoir à réimprimer le QR code
* Le support client a une interface d'admin où ils voient tous les établissements inscrits ainsi que leur menu PDF
* ...une autre idée d'amélioration !

## Conseils

* Prenez le temps de réfléchir au problème et de choisir vos outils, gems, packages, etc.
* Privilégiez les outils que vous maitrisez ou que vous savez être simples
* N'ajoutez une brique que si elle vous parait indispensable.
* Si vous rencontrez un problème, ne perdez pas de temps et cherchez à le contourner avec une autre approche
* N'hésitez pas à décrire les problèmes que vous avez rencontrés dans votre Google Doc
* Amusez-vous et essayez d'apprendre quelque chose !

Bon courage !
