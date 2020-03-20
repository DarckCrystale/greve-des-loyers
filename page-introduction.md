---
title: Comment ajouter une nouvelle page au site ?
subtitle: Documentation et exemples pour rajouter de nouvelles pages au site
layout: page
show_sidebar: false
menubar: menubar_participation_mode_d_emploi
---

Vous trouverez ici des explications détaillées vous permettant de rajouter du de nouvelles pages au site.

Le mode d'emploi est en cours de réalisation, n'hésitez pas à revenir régulièrement pour consulter le nouveau contenu !

## Options des pages

Nous réalisons les pages en Markdown. Différentes options vous sont proposées pour les personaliser si vous le souhaitez.

```yaml
---
layout: page
title: Titre de la page
subtitle: Sous-titre de la page
image: /chemin/vers/l/image.jpg
description: Description meta de la page
hero_image: /chemin/vers/l/image/du/hero.jpg
hero_height: is-fullheight
---
```

Au cas où vous ne définiriez pas les entrées suivantes, les réglages par défaut seront utilisés :
- `subtitle`
- `image`
- `hero_height`

Au cas où vous ne définiriez pas l'entrée `hero_image`, aucune image ne sera utilisée dans le hero.

### layout

L'entrée `layout` permet de définir la disposition de la page. Merci de systématiquement utiliser le layout `page` pour les pages du site.

### title

L'entrée `title` permet de définir le titre de la page, affiché dans la grande zone colorée sous la barre de navigation.

### subtitle

L'entrée `subtitle` permet de définir le sous-titre de la page, affiché dans la grande zone colorée sous la barre de navigation, sous le titre. Cette entrée est optionnelle.

### image

L'entrée `image` permet de définir le chemin vers une image qui sera utilisée derrière le titre et le sous-titre de la page, à la place de la grande zone rouge. Cette entrée est optionnelle.

### description

L'entrée `description` permet de définir la description qui sera affichée en guise de résumé de la page. Cette entrée est notamment utile au référencement. Cette entrée est optionnelle.

### hero_image

L'entrée `hero_image` permet de définir le chemin vers une image qui sera utilisée comme arrière plan du hero de la page, à la place de la grande zone grise. Cette entrée est optionnelle.

### hero_height

L'entrée `hero_height` permet de définir le la hauteur du hero de la page. Cette entrée est optionnelle.

## Créer une nouvelle page

Une page se fabrique en deux étapes :

- 1/ créer la page
- 2/ afficher la page dans les menus adéquats

*Suite du tutoriel en cours de réalisation*
