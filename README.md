Example embedding html contents using Shadow DOM and Declarative Shadow DOM.

Tested oEmbed Drupal content to another CMS. Tested with ES6 module media gallery.

Shadow DOM is set on client side and requires some JS updates but Declarative Shadow DOM is set on server side and it is very easy to set up and use. 

Since Declarative Shadow DOM renders on server it is much more efficient and the page view source is available, which might be a concern with shadow DOM for SEO.

Useful if the embeded html have its own css and javascript and you don't want it to obstruct other sections of your page. You could also achieve this with iframe but if you need an alternative solution this works well!

