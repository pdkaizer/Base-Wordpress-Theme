# Base Wordpress theme

Based on Underscores http://underscores.me/, (C) 2012-2016 Automattic, Inc., [GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html) and improved with [SASS](https://sass-lang.com/), [Gulp](https://gulpjs.com/), [Susy](http://oddbird.net/susy/), [Bourbon](https://www.bourbon.io/) and [Breakpoint-SASS](http://breakpoint-sass.com/).

Getting Started
---------------

Download or clone 'WP Base' from GitHub. The first thing you want to do is copy the `WP Base` directory and change the name to something else (like, say, 'my-awesome-theme'), and then you'll need to do a five-step find and replace on the name in all the templates.

* Search for: 'WP_Base' and replace with: 'my-awesome-theme'
* Search for: WP_Base_ and replace with: my-awesome-theme_
* Search for:  WP_Base and replace with:  my-awesome-theme
* Search for: WP_Base- and replace with: my-awesome-theme-

In terminal cd into your theme directory and `npm install` to install the Node packages.

Compiling the CSS from SASS
---------------------------

All the SASS partials are in the scss directory and complie to the style.css file. Edit the SASS files and run a `gulp` comand to compile the css.


