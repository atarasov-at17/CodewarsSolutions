
* https://www.codewars.com/kata/convert-number-to-reversed-array-of-digits/train/javascript

```javascript

function digitize(n) {
 return n.toString().split('').reverse().map(Number)
}
