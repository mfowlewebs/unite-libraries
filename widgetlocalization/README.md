## Widget Localization

**Note: since April 2012 development and support for Opera Unite has been discontinued. This includes the Opera Unite functionality inside the Opera desktop browser itself, as well as the Opera Unite servers that provided the public `user.operaunite.com` URLs.**

widgetLocalization derives the user agent's locale using the algorithm found in http://www.w3.org/TR/widgets/#step-5--derive-the-user-agents-locale. You can then use the gettext library to retrieve and handle the appropriate language files for that locale, if they are available.

### JSDoc
Documentation can be generated with JSDoc (either version [2](http://code.google.com/p/jsdoc-toolkit/) or [3](https://github.com/micmath/jsdoc)).