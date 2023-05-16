## idées à trier 

**Setup Wizard** : lors de la premiere ouverture une fenetre propose de modifier la langue de l'interface

**Onglet Aide** dans la fentre de bibliotheque

**Info bulles** sur les catégories de livres (fentre de bibliotheque)

Besoin de faciliter personalisation #forks

set a different location for the “library.” #user-need

Possibilité d'imprimer


## known limitations
* Reset parametres affichage
* Supprimer données utilisateur

## to be done in 2023
* zoom images svg
* tts jap (ruby)
* vertical writing mode

## Limites et difficultées techniques

Il est complexe et risqué d'ajouter du contenu dans l'espace de lecture même (cela implique de modifier le fichier à la volée et expose à des problémes de cascade css). C'est pourquoi les volets de parametre, navigation recherche sont dans des volets en surimpression du contenu.


## Limitations / issues

Opening eBooks in Thorium causes a copy of the publication to be saved to the user profile. A lot of my use is on a managed system, and this causes my user profile to exceed its memory capacity every couple of days. 
I haven’t been able to find a setting to opt out of this feature or to set a different location for the “library.”
The workaround I’ve been using is to manually delete the copied ebook files a couple times a week, but this does become rather cumbersome. I’m hoping there’s a better solution, or that a future update of Thorium could include the option to set the Thorium library to a different location.
(Karisma “Charlie” Tobin thru email)


## pistes

https://github.com/opds-community/drafts/discussions/49#discussioncomment-894634

We use the [Web Annotation Protocol](https://www.w3.org/TR/annotation-protocol/) to sync bookmarks and last reading position across devices. At a glance it covers all the use cases here, and it's a well-defined protocol with multiple independent implementations.

## references

https://product-design-roadmap.com/
