# Homework: Review key concepts for Friday's project

Read/review the information highlighted above.

Note *one* concept/fact for each concept and note it in the README in the designated location.

### JavaScript: Timing events
https://www.w3schools.com/js/js_timing.asp

NOTE A KEY CONCEPT HERE:
The window.clearTimeout() method can be written without the window prefix.


### Handling Events: 
Chapter 6 - JavaScript Book and/or https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events

NOTE A KEY CONCEPT HERE:
Event handler property
var btn = document.querySelector('button');

btn.onclick = function() {
  var rndCol = 'rgb(' + random(255) + ',' + random(255) + ',' + random(255) + ')';
  document.body.style.backgroundColor = rndCol;
}
The onclick property is the event handler property being used in this situation. It is essentially a property like any other available on the button (e.g. btn.textContent, or btn.style), but it is a special type — when you set it to be equal to some code, that code will be run when the event fires on the button.


### CSS Background Images: 
https://developer.mozilla.org/en-US/docs/Web/CSS/background-image

NOTE A KEY CONCEPT HERE:How the images are drawn relative to the box and its borders is defined by the background-clip and background-origin CSS properties.

