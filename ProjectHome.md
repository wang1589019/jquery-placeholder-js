This plugin is used to support the HTML5 placeholder attribute on most non-HTML5-compliant browsers.

It might be different from other implementations in the following ways:
  * Does not require additional css
  * Does not create additional HTML components
  * Handles form submit event, placeholder text will not be submitted
  * Preserves user's custom setting including color of the text, and onblur event.

Usage:

$.Placeholder.init(); // default setting

$.Placeholder.init({ color : 'rgb(255, 255, 0)' }); // custom placeholder text color

Please see demo.html in the svn / download for more details.