# Checklist de bonnes pratiques pour la contribution de contenu sur WordPress

Cette checklist est à destination des personnes intervenant sur un site pour en rédiger les contenus (contribution). Elle est basée sur une sélection de critères du [Référentiel Général d’Amélioration de l'Accessibilité (RGAA)](https://accessibilite.numerique.gouv.fr/), du [Référentiel Général d’Eco-conception des Services Numériques (RGESN)](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/) et de [règles Opquast](https://checklists.opquast.com/fr/assurance-qualite-web/).

Dernière modification le 6 décembre 2022.  
Ce document est disponible sous licence [Creative Commons BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.fr) / GPLv3.  
Auteur : Agence Whodunit  
Contact : Jean-Baptiste Audras – <jean-baptiste@whodunit.fr>

## Images

1. Préparer une alternative textuelle pour les images porteuses d’information.  
Pour plus d’informations, [consulter notre guide pour choisir le bon texte alternatif pour vos images](https://www.whodunit.fr/comment-choisir-le-texte-alternatif-de-vos-images-sur-wordpress/).  
__(Accessibilité)__ __(Référencement)__

2. Choisir le format image adapté à la typologie d’image et au contexte d’affichage : utiliser de préférence le format vectoriel comme le SVG lorsque cela est possible (illustrations, icônes, logos, graphiques...), le format JPEG pour des photos et le format PNG pour des illustrations avec aplats de couleurs.  
Note : les images concernées seront automatiquement converties au format WebP et toutes les images du site seront automatiquement optimisées lors de la mise en production du site.  
__(Eco-conception)__

## Liens

3. Prévoir un intitulé (texte visible et cliquable) pertinent. Éviter les formulations génériques de type « en savoir plus » ou « lire la suite ».
__(Accessibilité)__ __(Référencement)__

4. Spécifier lorsqu’un lien ouvre une nouvelle fenêtre.  
Exemple : "consulter nos mentions légales (nouvelle fenêtre)"  
__(Accessibilité)__ __(Expérience d’utilisation)__

5. Le soulignement du texte est strictement réservé aux liens.  
__(Accessibilité)__ __(Expérience d’utilisation)__  

6. Vérifier que les liens utilisés sur le site sont bien des liens valides et ne tombent pas sur une page d’erreur 404.  
__(Expérience d’utilisation)__

## Langues / internationalisation

7. Indiquer les changements de langue (via l’éditeur de blocs en utilisant le bouton de formatage de l’attribut de langue [fourni par l’extension dédiée de Whodunit](https://fr.wordpress.org/plugins/lang-attribute/)).  
__(Accessibilité)__

8. Indiquer lorsqu’un lien mène vers une page qui n’est pas dans la même langue que la page consultée, soit directement dans le texte, soit à l’aide de l’attribut `hreflang`. Exemple : "consulter notre politique internationale (en anglais)".  
__(Accessibilité)__  

9. Si le site ou la page a une vocation internationale, l’indicatif téléphonique des numéros de téléphone est indiqué, et le pays est indiqué sur les adresse postales.  
__(Expérience d’utilisation)__

## Contenus textuels

10. La hiérarchie des titres et sous-titres est cohérente sur chaque page, en utilisant les 6 niveaux de titres à votre disposition.  
Veiller à ce que la structure ne comporte pas de « trous » : un titre de niveau 2 ne doit pas être suivi d’un titre 4, 5 ou 6, par exemple, mais d’un titre de niveau 2 ou de niveau 3.  
__(Accessibilité)__ __(Référencement)__

11. Les éléments présentés sous forme de liste doivent utiliser le bloc liste (soit numérotée, soit à puces).  
__(Accessibilité)__

12. Formatage : ne pas utiliser de texte justifié.  
__(Accessibilité)__ __(Expérience d’utilisation)__

13. Abréviations : indiquer la signification des acronymes et abréviations lors de leur première occurrence. Exemple : « Notre site est conforme au Référentiel Général d’Amélioration de l’Accessibilité (RGAA). Le RGAA permet de s’assurer que le site est consultables par toutes et tous ».  
Il est aussi possible d’utiliser [l’extension dédiée de Whodunit](https://fr.wordpress.org/plugins/abbreviation-button-for-the-block-editor/) (bouton de formatage présent sur chaque bloc).  
__(Accessibilité)__

14. Les éléments textuels et graphiques des pages de contenu utilisent la charte graphique (couleurs, typos) disponible dans votre backoffice, pour assurer la cohérence et la persistance de la charte au travers de l’ensemble du site.  
__(Expérience d’utilisation)__

15. Les mises en majuscules à des fins décoratives sont faites à l’aide des styles. Si vous avez un besoin régulier d’utiliser des majuscules, nous pouvons créer un bouton de formatage pour cela.  
__(Expérience d’utilisation)__

16. Le titre principal de chaque page permet d’identifier son contenu.  
__(Expérience d’utilisation)__ __(Référencement)__

## Contenus téléchargeables

17. Indiquer le format et le poids des fichiers téléchargeables. Exemple : "télécharger notre brochure (PDF, 56 Ko)".  
__(Accessibilité)__

18. Le nommage des fichiers disponibles en téléchargement doit permettre d’en identifier le contenu et la provenance.  
__(Expérience d’utilisation)__

19. La langue des fichiers proposés en téléchargement est indiquée si elle diffère de la langue de la page où le fichier peut-être téléchargé.  
__(Expérience d’utilisation)__

## Contenus multimédias et interactifs

20. Les vidéos proposant une bande sonore doivent être sous-titrées ou une transcription textuelle doit être proposée.  
__(Accessibilité)__ __(Référencement)__

21. Privilégier l’insertion de vidéos depuis des plateformes tierces Youtube ou Viméo aux vidéos hébergées sur le site (prévoir de déposer les vidéos sur ces plateformes en amont). La lecture des vidéos sera bloquée automatiquement tant que l'internaute n'aura pas donné son consentement pour le dépôt des cookies associés.  
__(Eco-conception)__

22. Les vidéos, animations et autres contenus interactifs doivent apporter une information complémentaire au contenu de la page.  
__(Eco-conception)__ __(Expérience d’utilisation)__

23. Multimédia : les vidéos ne doivent pas être en autoplay.  
__(Eco-conception)__

24. Limiter le nombre de carrousels présents sur le site, et ne pas en avoir plus d’un par page (l’idéal étant de ne pas en avoir).  
__(Eco-conception)__

## Métadonnées

25. Prévoir le contenu de la méta description pour les pages stratégiques. Cette métadonnée sera saisie dans Yoast pour améliorer la visibilité de vos pages dans les résultats de recherche. Longueur maximum : 155 caractères espaces compris.  
__(Référencement)__

26. Prévoir une image d’illustration à mettre en avant pour les pages stratégiques. Cette image est notamment utilisée lors du partage de vos pages sur les réseaux sociaux.  
__(Référencement)__
