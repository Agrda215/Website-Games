# Upgrades

 In Code Add Button is here:
 
 ```js
 upgrades:{
   11:{
     description:"Blah",
     cost:new Decimal(1)
   }
 }
```
```html
<upgrades>
 <c1r1>
  <button>
    <span id="upgradeDesc11"></span>
    <br>
    <span id="upgradeCost11"></span>
   </button>
  </c1r1>
</upgrades>
```
```js
 document.getElementById("upgradeDesc11").innerText = game.layers[0].upgrades["11"].description
 document.getElementById("upgradeCost11").innerText = game.layers[0].upgrades["11"].cost
```
---
- title:Returns Be Title.
- description:at than desCRIPTion.
- cost:at to cost now need to `new Decimal(Extra Features :))`.
- unlocked: Return be unlocked.
- style: A be css to upgrades.