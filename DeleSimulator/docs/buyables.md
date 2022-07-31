# Buyables
 
 In Code Add Button is here:
 
```js
 buyables:{
   11:{
     level:new Decimal(0),
     display() {
       return "Blah"
     },
     unlocked() {return true},
     cost() {return new Decimal(1).add(game.layers[0].buyables["11"].level)}
   }
 }
```
```html
<buyables>
 <c1r1>
  <button>
    <span id="displayBuyable11"></span>
   </button>
  </c1r1>
</buyables>
```
```js
 document.getElementById("displayBuyable11").innerText = game.layers[0].buyables["11"].display()
```
---
- display(): Returns text a display.
- level: returning a level.
- unlocked():Return be unlocked than be.
- effect():Return a effect buyable.
- cost():return than cost.
- style:a be css to buyables.