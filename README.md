jQuery Hashchange Event Plugin
==============================

The jQuery hashchange event plugin allow you to bind to the "hashChange" event on your pages. The hashChange
event occurs when the address hash value is changed user interaction with your page.

Usage
-----

    <script type="text/javascript">
    // the callback will receive the new and old hash values as arguments
    $(window).hashChange(callbackFunction);
    
    // or you can bind to the "hashChange" event
    $(window).bind("hashChange", function(e, newHash, oldHash) {
        console.log("new: " +  newHash);
        console.log("old: " + oldHash);
    });
    </script>


Dependancies
------------

 - jQuery 1.5+

Optionally, the plugin will detect Modernizer (requires 2.0+) to verify if the current client
supports the "hashchange" event (html5).


