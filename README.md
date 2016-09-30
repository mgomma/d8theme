# d8theme

Introduction:

  Simple blank theme  to inject any style and have custom html for elements easily.
  Supports ar, en styles in separate files for people don't like [dir="rtl"].
  Remove default drupal libraries so you get blank pages waiting for your styles and scripts. 
  Add many extra theme suggestions see .theme file.
  Templates folder has grouped html.twig files so you could add your own wrappers and markup.

Use case:

  You have a template or theme the client have bought it from theme forest or developed by front end developer,
  you asked to implement in drupal 8 that theme help you do the job easily.

Usage:

  Define your own regions.
  Add your own markup in .html.twig files templates folder to build your html document structure.
  Add you own css and js in assets folder and add the relative path d8theme.libraries.yml file like global-styling.
  Let your library be loaded automatically by adding it in d8theme.info.yml file like global-styling.
  Add images fonts too in assets.

Debug:

  Enable site mode dev to easily debug see https://www.drupaleasy.com/quicktips/enabling-development-mode-local-drupal-8-site.
  See the page source and you will find twig template suggestions and from where the markup built, 
  you could build your own by copying that file to the templates folder so it becomes your own so you could alter the html.
  Add more them suggestions to have more html.twig files get your hand dirty with .theme file that has,
  some useful alterations could be your guide line.

Contribute:

  Fork and do pull requests to add your enhancements or upload Patches on issues.  

@TODO:

  Record video documents and briefly illustrate theme system and how to use that theme 
  Make it parent themes and test child themes.
  Add screeshot. 

