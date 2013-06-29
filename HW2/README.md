### Node libraries

[restler](https://github.com/danwrong/restler) REST client library for node.js.

[CSV](https://github.com/wdavidw/node-csv) parser with simple api, full of options and tested against large datasets.

[accounting](https://github.com/josscrowcroft/accounting.js) number, money and currency parsing/formatting library 

### Closure in JavaScript

http://jondavidjohn.com/blog/2011/09/javascript-event-handler-persistance-with-closures
http://stackoverflow.com/questions/111102/how-do-javascript-closures-work

```javascript
/*
I need to know how many times a button has been clicked, and do something on every third click…
All variables outside the returned function are available to the returned function, 
 but are not directly available to the returned function object….
 */
var element = document.getElementById('button');

element.onclick = (function() {
    // init the count to 0
    var count = 0;
    
    return function(e) {
        //count
        count++;
    
        if (count === 3) {
            // do something every third time
            alert("Third time's the charm!");
            //reset counter
            count = 0;
        }
    };
})();

```
