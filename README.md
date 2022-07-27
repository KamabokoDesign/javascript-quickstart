# Javascript Quickstart
useful javascript functions I use all the time



## unwrapping tags 
to make a clean string (used for scrapers)
```
function unwrap(selector) {
var nodelist = document.querySelectorAll(selector);
nodelist.forEach(function(item, i) {
item.outerHTML = item.innerHTML;
})
}
```
