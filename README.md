# Dashicons

Dashicons, the WordPress admin icon font. For the official documentation, please refer to the according [WordPress Developer Resource](https://developer.wordpress.org/resource/dashicons/).

For new icon requests, please [create a new issue on this GitHub repository](https://github.com/WordPress/dashicons/issues/new). If you'd like to work an an icon request, [check out our WIP Dashicons style guide](https://make.wordpress.org/design/dashicons-style-guide/).

For any bugs that appear within WordPress core, please [create a new ticket on WordPress Trac](https://core.trac.wordpress.org/newticket). Use the "Administration" component and the "ui" focus when creating the new ticket, and be sure to include "Dashicons" somewhere in the text of the ticket.

Dashicons is licensed under [GPLv2](http://www.gnu.org/licenses/gpl-2.0.html), or any later version with [font exception](http://www.gnu.org/licenses/gpl-faq.html#FontException).

## Building

To build Dashicons, make sure you have <a href="https://nodejs.org">Node JS</a> installed, and if you're on a Mac, also <a href="https://brew.sh/">Brew</a>.

Then on the commandline:

```
brew install ttfautohint fontforge --with-python
npm install
```

From now on you can type `npm run build` to generate the minified SVG files and sprite. 
