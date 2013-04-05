jQuery Autocompletion
==============

Extra small Autocompletion plugin for jQuery and Zepto.js

Basic usage
-----

Include jQuery (or Zepto.js), `autocompletion.js` and `autocompletion.css` or it's minified versions to your page. Like this:

    <script src="jquery.min.js"></script>    
    <script src="autocompletion.js"></script>
    <link href="autocompletion.css" rel="stylesheet">
   
Apply the Autocompletion plugin to input:
    
    $('input#autocompletion').autocompletion({
        source: ['Mother', 'Father', 'Sister', 'Brother']  // Also it can be a function. See below.
    });

Ajax source
-----

Options
-----

License
-----
