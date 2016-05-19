# apPopup
A super jQuery popup plugin. Design for developers, it's simple to use.

# Installation:
Add just before closing your head tag:
```<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/animatecss/3.5.1/animate.min.css">```

Add this just before your closing body tag, after you've included jQuery:
```<script src="/your/path/apPopup.js"></script>```
## Basic Usage
Basic example
```$("#popup").apPopup();```

Passing in options
```$("#popup").apPopup({
     optionName: optionValue
   });```
Passing in option from data attribute:
```<div id="popup" data-popup-options='{"optionName":"optionValue"}'></div>```

