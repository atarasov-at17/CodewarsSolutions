Hello!


https://www.codewars.com/kata/5715eaedb436cf5606000381
```javascript
function positiveSum(arr) {
  let res = 0;
  for (let i = 0; i < arr.length; i++) {
  if (arr[i] > 0) {
   res += arr[i];
}
}
  return res;
}
* https://www.codewars.com/kata/59342039eb450e39970000a6
```javascript
function oddCount(n){
 return Math.floor( n / 2 );
 }

* https://www.codewars.com/kata/switch-it-up/train/javascript
```javascript
function switchItUp(number){
let arr = ['Zero', 'One', 'Two', 'Three', 'Four', 'Five', 'Six','Seven', 'Eight', 'Nine'];
return arr[number];
}
* new solution

* second new solution
* https://www.codewars.com/kata/5a00e05cc374cb34d100000d
```javascript

const reverseSeq = n => {
  const arr = [];
  for(let i = n; i > 0; i--){
   arr.push(i); 
  }
  return arr;
};

* Hello 

new docs
new branch

hello

* https://www.codewars.com/kata/print-a-rectangle-using-asterisks/train/javascript

```JavaScript

function getRectangleString(w, h) {
  const rn = '\r\n';
  const tb = '*'.repeat(w) + rn;
  const center = (w > 1) ? ('*' + ' '.repeat(w - 2) + '*' + rn).repeat(h - 2) : '';
  return h > 1 ? (tb + center + tb) : tb.repeat(h);
  
  }


Hard day 

*
``` JavaScript

function toBinary(n){
  return +n.toString(2);
}