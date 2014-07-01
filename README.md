no_respect
============

no_respect is a theme for Octopress. It uses a flat-ui CSS navbar and ditches the typical content preview that most octopress themes take advantage of. 

It's a modified version of [respectMattt](https://github.com/midnightSuyama/respectMattt) by midnightSuyama

This readme was originally written by midnightSuyama and adapted for this project by segordon.

## Install

	$ cd octopress
	$ git clone git://github.com/segordon/no_respect.git .themes/no_respect
	$ rake install['no_respect']
	$ rake generate

If zsh, please use `rake install\['no_respect'\]`.

## Configuration

remember to set the default index pagination value higher than the default in your _config.yml file! Without those content previews the blog links take signifigantly less space.

### Theme

Change category names in `.themes/no_respect/source/_includes/post/theme.html`.

## Acknowledgements

* [CSS Menu Maker](http://cssmenumaker.com/)
* [respectMattt](https://github.com/midnightSuyama/respectMattt)
* [Bootstrap](http://getbootstrap.com)
* [Font Awesome](http://fortawesome.github.io/Font-Awesome/)
* [jQuery](http://jquery.com)
* [Isotope](http://isotope.metafizzy.co)
* [Lettering.js](http://letteringjs.com)
* [Subtle Patterns](http://subtlepatterns.com)
* [mini Social Icons](http://wolfrosch.com)
