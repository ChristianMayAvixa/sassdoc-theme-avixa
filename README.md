# SassDoc Default Theme

This is a fork of [SassDoc](https://github.com/SassDoc/sassdoc)'s default theme customized for use in AVIXA's web team. 

This theme uses [Nunjucks](https://mozilla.github.io/nunjucks/) as a template engine.

## Customising the view

There are some possibilites to customise the theme's view. Essentially what's being displayed, what's not, and what are the project informations to be displayed in the header and footer.

To learn how to customise the theme's view, please read [the documentation on SassDoc's site](http://sassdoc.com/customising-the-view/). Fear not! It's all about creating a configuration file. No big deal.

Instructions to update:
-Make your changes
-Increment the version number by 0.0.1
-Run `Make` in git bash
-Run `npm publish` to update the npm package
-In the main repo, increment the required version of this package by 0.0.1
-In the main repo, run `yarn install`
-In the main repo, run `yarn run build-sass-docs`