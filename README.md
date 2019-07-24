
* https://www.codewars.com/kata/convert-number-to-reversed-array-of-digits/train/javascript

```javascript

function digitize(n) {
 return n.toString().split('').reverse().map(Number)
}


========================


*
```javascript
Sleigh.prototype.authenticate = function(name, password) {
  return name == "Santa Claus" && password == "Ho Ho Ho!";
};

* https://www.codewars.com/kata/57241e0f440cd279b5000829/solutions/javascript

```javascript

function sumMul(n,m){
  if (n >= m) return "INVALID";

var sum = 0;
  for (var i = n; i < m; i+=n) {
    sum += i;
  }
  return sum;
}