#DOCUMENTATION




##HTML



* X-UA-Compatible
Internet Explorer has many rendering engines ready for use. What this line of code basically does is force IE to use the most up to date rendering engine that it has available, so that your pages will render as well as possible. It then goes on to talk about Chrome Frame. Chrome Frame is a plugin for IE6, 7, and 8 which brings all the rendering, and js power of Google Chrome to IE. If the user has it installed, we render our site using it.

* google-site-verification
provides webmaster tools with verification of site ownership

* Touch Icons – inspiration from h5bp and (mathiasbynens.be/notes/touch-icons)
iPad 3+ (with Retina Display): apple-touch-icon-144x144-precomposed.png or apple-touch-icon-144x144.png
iPhone 4+ (with Retina Display): apple-touch-icon-114x114-precomposed.png or apple-touch-icon-114x114.png
first- and second-generation iPad: apple-touch-icon-72x72-precomposed.png or apple-touch-icon-72x72.png
non-Retina iPhone and iPod Touch: apple-touch-icon-57x57-precomposed.png or apple-touch-icon-57x57.png
fallback for everything else (possibly including non-Apple devices): apple-touch-icon-precomposed.png and apple-touch-icon.png



* Modernizer [http://modernizr.com/]


* jQuery loading fallback
A vast majority of sites these days make use of the jQuery JavaScript library. A vast majority also make use of Google’s hosted version of the library for faster loading speed’s, and better cross site caching. However, what if there is ever a problem and jQuery is not loaded from Google? Well here is your backup. What it basically does is check if jQuery is loaded from Google. If not, then we load it locally from our own version of jQuery.


* Google Analytics
This is simply an optimised version of Google’s asynchronous tracking snippet. Always at teh bottom of each page








##Useful Resources
html selectors - http://www.w3.org/TR/CSS2/selector.html  
HTML5 draft spec - http://www.w3.org/TR/html5/ 
Responsive design patterns - http://bradfrost.github.com/this-is-responsive/patterns.html