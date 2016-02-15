# Graphical Web [![Build Status](https://travis-ci.org/met-office-lab/graphical-web-website.svg?branch=gh-pages)](https://travis-ci.org/met-office-lab/graphical-web-website)

A conference for visualizing the connected world.

## Writing this website on GitHub

As the conference topic is around websites and using web technologies it only makes sense to develop the conference website in the open.

The website has been built using the [Jekyll](https://jekyllrb.com/) static website generator.

## Browser Support

This website is designed to run on the latest version of all modern browsers.

## Contributions

Contributions are welcome to this repository.

To get started you must clone this repository and run an `npm install`. If you don't have the Grunt CLI tool installed you'll also need to run `npm install -g grunt-cli`.

Then you can use the following grunt commands:

 * `grunt build` - builds the jekyll website into `_site`.
 * `grunt serve` - builds the website and starts a local webserver at http://localhost:4000 for local development.
 * `grunt test` - builds the website and runs tests agains the html and links.
 * `grunt purge` - purges the production CDN, for use by travis only and requires environment variables to be set.

## License

The Graphical Web logo and surrounding artwork are reserved for the use of the Graphical Web conference only.

The written and video content provided on the website are released under the [Creative Commons BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/3.0/) license.

The website code itself, minus the logos and content mentioned above, is licensed under the [GPLv3](http://www.gnu.org/licenses/gpl-3.0.en.html) license. This may be released as a separate repository if there is demand.
