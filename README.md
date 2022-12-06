# Checklist de bonnes pratiques pour la contribution de contenu sur WordPress

Cette checklist est à destination des personnes intervenant sur un site pour en rédiger les contenus (contribution). Elle est basée sur une sélection de critères du [Référentiel Général d’Amélioration de l'Accessibilité (RGAA)](https://accessibilite.numerique.gouv.fr/), du [Référentiel Général d’Eco-conception des Services Numériques (RGESN)](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/) et de [règles Opquast](https://checklists.opquast.com/fr/assurance-qualite-web/).

## Images

1. [] Préparer une alternative textuelle pour les images porteuses d’information.  
Pour plus d’informations, [consulter notre guide pour choisir le bon texte alternatif pour vos images](https://www.whodunit.fr/comment-choisir-le-texte-alternatif-de-vos-images-sur-wordpress/).  
__(Accessibilité)__ __(Référencement)__

2. [] Choisir le format image adapté à la typologie d’image et au contexte d’affichage : utiliser de préférence le format vectoriel comme le SVG lorsque cela est possible (illustrations, icônes, logos, graphiques...), le format JPEG pour des photos et le format PNG pour des illustrations avec aplats de couleurs.  
Note : les images concernées seront automatiquement converties au format WebP et toutes les images du site seront automatiquement optimisées lors de la mise en production du site.  
__(Eco-conception)__

## Liens

3. [] Prévoir un intitulé (texte visible et cliquable) pertinent. Éviter les formulations génériques de type « en savoir plus » ou « lire la suite ».
__(Accessibilité)__ __(Référencement)__

4. [] Spécifier lorsqu’un lien ouvre une nouvelle fenêtre.  
Exemple : "consulter nos mentions légales (nouvelle fenêtre)"  
__(Accessibilité)__ __(Expérience d’utilisation)__

5. [] Le soulignement du texte est strictement réservé aux liens.  
__(Accessibilité)__ __(Expérience d’utilisation)__  

6. [] Vérifier que les liens utilisés sur le site sont bien des liens valides et ne tombent pas sur une page d’erreur 404.  
__(Expérience d’utilisation)__

## Langues / internationalisation

7. [] Indiquer les changements de langue (via l’éditeur de blocs en utilisant le bouton de formatage de l’attribut de langue [fourni par l’extension dédiée de Whodunit](https://fr.wordpress.org/plugins/lang-attribute/)).  
__(Accessibilité)__

8. [] Indiquer lorsqu’un lien mène vers une page qui n’est pas dans la même langue que la page consultée, soit directement dans le texte, soit à l’aide de l’attribut `hreflang`. Exemple : "consulter notre politique internationale (en anglais)".  
__(Accessibilité)__  

9. [] Si le site ou la page a une vocation internationale, l’indicatif téléphonique des numéros de téléphone est indiqué, et le pays est indiqué sur les adresse postales.
__(Expérience d’utilisation)__
