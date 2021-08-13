---
title: "Liste de contrôle des politiques sur l’analyse Web du SNC"
description: "La présente liste de contrôle vise à faciliter le travail de toute équipe de prestation de services du SNC qui veut s’assurer que l’utilisation de leur service d’analyse Web est conforme à la Norme sur la protection de la vie privée et le Web analytique."
date: 2020-06-22
datePublished: 2021-08-10
author: "Sam Burton, Victoria Chan"
draft: false
---

**La présente liste de contrôle vise à** faciliter le travail de toute équipe de prestation de services du Service numérique canadien (SNC) qui veut s’assurer que l’utilisation de leur service d’analyse Web est conforme à la [Norme sur la protection de la vie privée et le Web analytique](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=26761).

**Des questions?** Demandez au conseiller en politiques de votre équipe de prestation ou à toute personne de l’équipe des politiques du SNC! #policy sur Slack est un excellent point de départ.

**L’anonymisation de l’adresse IP est activée.** La Norme sur la protection de la vie privée et le Web analytique exige que nous activions l’anonymisation des adresses IP pour tout outil d’analyse Web que nous utilisons, de sorte qu’il ne stocke pas de renseignements personnels.

_Google Analytics [GA] :_ 

* Pour activer l’anonymisation, il faut modifier le code du produit qui télécharge GA. L’approche varie selon la façon dont GA est intégré au produit. Google dispose d’un [site illustrant son processus d’anonymisation de l’adresse IP, avec quelques liens décrivant l’activation](https://support.google.com/analytics/answer/2763052?hl=fr). 
* Une fois que l’anonymisation est activée, vous pouvez vérifier si le produit rend des adresses IP anonymes :
    1. Chargez le site du produit dans Chrome ou Firefox.
    2. Cliquez avec le bouton droit sur la page et sélectionnez « Inspecter » ou « Inspecter l’élément » dans le menu qui s’affiche.
    3. Une nouvelle fenêtre devrait apparaître. Il s’agit de la fenêtre des outils de développement. Naviguez jusqu’à l’onglet « Réseau » et actualisez le site du produit pour télécharger de nouvelles données. (Cet onglet répertorie toutes les ressources chargées pour afficher une page Web.)
    4. Dans la case Filtre de l’onglet Réseau, tapez « collect » (collecter). Il devrait maintenant y avoir une entrée dans la liste, quelque chose qui commence par « collect?v=1& ». Sélectionnez-la.
    5. Dans Chrome, sélectionne le sous-onglet « En-têtes » et faites défiler jusqu’à la section « Paramètres de chaîne de requête ». Dans Firefox, choisissez le sous-onglet « Params ». Vous voulez voir « aip : 1" dans la liste. Si vous voyez cette entrée, l’anonymisation de l’adresse IP est activée!

**Toutes les autres options d’analyse qui recueillent des renseignements personnels sont désactivées**

_Google Analytics :_

* Cela comprend la désactivation des données démographiques (par exemple, extrapolation et stockage des renseignements sur l’âge, et le sexe des utilisateurs). 
* Passez en revue les [Bonnes pratiques permettant d’éviter l’envoi d’informations personnelles](https://support.google.com/analytics/answer/6366371?hl=fr&ref_topic=2919631) avec un développeur de votre équipe afin de vous assurer qu’aucun renseignement personnel n’est transmis par inadvertance à Google.

**La période de conservation des données est fixée à six mois au maximum, ou l’option la plus courte disponible**

_Google Analytics :_

* Définissez la période de conservation des données à 14 mois. Google Analytics ne permet pas une période de conservation plus courte que celle-ci, et la plupart des données recueillies par GA sont exemptées de la limite de conservation de six mois, car elles sont regroupées.

**L’avis sur la protection des renseignements personnels du service répond à toutes les exigences suivantes, énoncées à l’annexe B de la [Norme sur la protection de la vie privée et le Web analytique](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=26761)** :

* Une déclaration indiquant quelle est l’autorité légale pour la collecte de ces renseignements.
* Une explication de ce qu’est le Web analytique et les objectifs de l’utilisation des outils de Web analytique par l’institution.
* Un énoncé indiquant quels renseignements personnels, y compris l’adresse IP, sont automatiquement recueillis sur les visiteurs par l’institution fédérale.
* Un énoncé indiquant aux visiteurs si l’adresse IP et d’autres données dans des marqueurs numériques sont recueillies et utilisées à l’interne par l’institution pour le Web analytique ou si elles sont divulguées ou transmises à un fournisseur tiers externe à cette même fin.
* Dans les cas où l’adresse IP et d’autres données dans les marqueurs numériques sont divulguées ou transmises à un fournisseur tiers pour le Web analytique, une explication est fournie quant à la manière dont la protection de la vie privée des visiteurs des sites Web du gouvernement du Canada est assurée, soit, au minimum, grâce à l’activation d’une fonction d’anonymisation grâce à laquelle le fournisseur tiers dépersonnalise l’adresse IP.
* Si les données divulguées ou transmises pour le Web analytique vont à l’extérieur du Canada, comme aux États-Unis, il est nécessaire d’ajouter un énoncé qui l’indique, de même qu’une référence à toutes les lois auxquelles les renseignements sont assujettis, comme dans le cas de la [USA Patriot Act](http://www.fincen.gov/statutes_regs/patriot/).
* Un énoncé indiquant la période maximale de conservation de tout renseignement personnel recueilli aux fins du Web analytique. 

**Décidez si ou quand il faut arrêter la collecte de données au moyen d’une plateforme d’analyse du SNC**

* Le SNC peut continuer ou ne pas continuer à recueillir des données analytiques après le transfert d’un service à un partenaire. 
* Tant que le SNC recueille des données analytiques (par exemple, au moyen d’une instance de Google Analytics appartenant au SNC), l’autorisation de collecte du SNC doit rester dans la déclaration de confidentialité.
