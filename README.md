# Masonry API

Provides an API for integrating the jQuery Masonry plugin with Drupal.

From [desandro.github.io/masonry](http://desandro.github.io/masonry/docs/intro.html):

  >  Masonry is a JavaScript grid layout library. It works by placing elements in optimal position based on available vertical space, sort of like a mason fitting stones in a wall.

As this is an API module, you will likely want to download some of the sub-modules below that implement this API to provide Masonry functionality to various parts of your site.
Additionally, no styling is provided by this API module or any of the sub-modules. You will need to add your own CSS as described [here](http://masonry.desandro.com/#css).

## Dependencies

- [imagesLoaded](https://backdropcms.org/project/imagesloaded)

## Installation

 - Install this module using the official
  [Backdrop CMS instructions](https://backdropcms.org/guide/modules)

## Developers

  If your module requires the library provided by this wrapper, you can access the
  JavaScript by:

  - Requiring this module as a dependency in your module
  - Loading the library in your module as follows: `backdrop_add_library('masonry', 'masonry');`

## Issues

Bugs and Feature requests should be reported in the
[Issue Queue](https://github.com/backdrop-contrib/masonry/issues)

## Current Maintainers

 - [Laryn Kragt Bakker](https://github.com/laryn) - [CEDC.org](https://cedc.org)
 - Co-maintainers welcome

## Credits

- Ported to Backdrop CMS by [Laryn Kragt Bakker](https://github.com/laryn) - [CEDC.org](https://cedc.org).
- Maintainers for the Drupal module: [BWPanda](https://github.com/BWPanda) and [Dom.](https://www.drupal.org/u/dom).

## License

This project is GPL v2 software. See the [LICENSE.txt](https://github.com/backdrop-contrib/masonry/blob/1.x-1.x/LICENSE.txt)
file in this directory for complete text.
