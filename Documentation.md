DOCUMENTATION
=================================================================================================================



HTML
=================================================================================================================


* X-UA-Compatible
Internet Explorer has many rendering engines ready for use. What this line of code basically does is force IE to use the most up to date rendering engine that it has available, so that your pages will render as well as possible. It then goes on to talk about Chrome Frame. Chrome Frame is a plugin for IE6, 7, and 8 which brings all the rendering, and js power of Google Chrome to IE. If the user has it installed, we render our site using it. For more information on Chrome Frame, and how you can even prompt users without it to install it, check here.


* google-site-verification
provides webmaster tools with verification of site ownership


* Modernizer [http://modernizr.com/]


* jQuery loading fallback
A vast majority of sites these days make use of the jQuery JavaScript library. A vast majority also make use of Google’s hosted version of the library for faster loading speed’s, and better cross site caching. However, what if there is ever a problem and jQuery is not loaded from Google? Well here is your backup. What it basically does is check if jQuery is loaded from Google. If not, then we load it locally from our own version of jQuery.


* Google Analytics
This is simply an optimised version of Google’s asynchronous tracking snippet. Always at teh bottom of each page








Useful Resources
html selectors - http://www.w3.org/TR/CSS2/selector.html  
HTML5 draft spec - http://www.w3.org/TR/html5/ 
Responsive design patterns - http://bradfrost.github.com/this-is-responsive/patterns.html