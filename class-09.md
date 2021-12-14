** Reading Notes **

Events - event handling

Event - Fired 

Type: 
click
submit
mouseover
keypress - key up, key down
Event listener - code triggered when event fired
Event handler - function that will run the code in response to the event

DOM LEVEL - 
1. DOM pushes element we want to listen to 
2. element.addEventListener('click', functionName) is a click on the defined area
  example: myDiv.addEventListener('click, handleClick);
    when using asynchronous code aka code that is not ran in order give different names to different clicks

callback function - fucntion that is entered as a parameter of function or method when used as an argument

the callback function is named but not called until the event sees fit

event bubbling - allows you listen to an event on a main when an article  is being accessed

event capturing - allows you to listen to an event in an article while the main is being accessed

events are objects 
