## Hot Tips from Lunch.js

- used comparison operators (< ,> , ===. etc) with Node in vagrant/terminal. 
- refactored hungry === false && hungry === true to use the not (!) operator for nicer to read Javascript
- worked iteratively-- small bits! 
- used console.log to find values of 'hungry' and 'avalilibleTime', as follows:
```javascript
function whatToDoForLunch(hungry, availableTime) {
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
}
```
- hungry will output as a boolean (true/false) and availibleTime will pass a number into the function 
the "hungry is" part of the console.log prints that string to the terminal with the result of our variable, hungry. this makes it easier to find in the sea of stuff thats in the terminal 