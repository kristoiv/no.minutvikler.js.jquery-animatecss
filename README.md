no.minutvikler.js.jquery-animatecss
===================================

jQuery-plugin for simplifying the use of Animate.css in your project by providing handy callbacks for when a animation completes (optionally delayed by a constant).


Example of use
==============

```javascript
$('#myObject').animateCss('tada', function() {
    console.log('Tada completed 1sec ago');
}, 1000);

$('#myObject, a, h1, h2').animateCss('zoomInRight', function() {
    console.log('Also works without a delay constant and with a list of multiple jquery selections');
});
```
