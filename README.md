no_respect
============

no_respect is a theme for Octopress. It uses a flat-ui CSS navbar and ditches the typical content preview that most octopress themes take advantage of in favor of a cleaner post-title-only index. 

It's a modified version of [respectMattt](https://github.com/midnightSuyama/respectMattt) by midnightSuyama

This readme was originally written by midnightSuyama and adapted for this project by segordon.

Updates may be slow, as the universal parts are pulled periodically from the theme in use at [segordon.net](http://segordon.net)

## Example

This theme is currently in use at [segordon.net](http://segordon.net/)

## Install

	$ cd octopress
	$ git clone git://github.com/segordon/no_respect.git .themes/no_respect
	$ rake install['no_respect']
	$ rake generate

If zsh, please use `rake install\['no_respect'\]`, also remember that it's usually beneficial for zsh uses to alias rake with noglob. ( add "alias rake="noglob rake" "to your .zshrc)

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

## Todo

better/further split of html/css in use within _includes/custom
