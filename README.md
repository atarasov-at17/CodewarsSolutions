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

* https://www.codewars.com/kata/get-nth-even-number/train/javascript

```javascript

 function nthEven(n){
 
   return n * 2 - 2;
   }

* https://www.codewars.com/kata/difference-of-volumes-of-cuboids/train/javascript
```JavaScript
function findDifference(a, b) {
  return Math.abs(( a[0] * a[1] * a[2] ) - ( b[0] * b[1] * b[2] ));
}

*https://www.codewars.com/kata/5a3f2925b6cfd78fb0000040/solutions/javascript

Javascript

function solve(s){
  if (s.length % 2) return -1;
    while (/\(\)/g.test(s)) s = s.replace(/\(\)/g, "");
  let cnt = 0;  
    for (let i = 0; i < s.length -1; i += 2) {
      s[i] !== s[i + 1] ? cnt+=2 : cnt++;   
    }
  return cnt;
}

* https://www.codewars.com/kata/can-we-divide-it/train/javascript

javascript

function isDivideBy(number, a, b) {
  return number % a === 0 && number % b === 0;
}

* https://www.codewars.com/kata/577bd8d4ae2807c64b00045b/solutions/java

```Java

public class Kata {
  public static String declareWinner(Fighter fighter1, Fighter fighter2, String firstAttacker) {
        int moves1 = (int) Math.ceil( (double)fighter2.health / fighter1.damagePerAttack);
        int moves2 = (int) Math.ceil( (double)fighter1.health / fighter2.damagePerAttack);
        if (moves1 > moves2) {
            return fighter2.name;
        } else if (moves1 < moves2) {
            return fighter1.name;
        } else {
            return firstAttacker;
        }
  }
}

* 
Hello world
update

+++++++
Hello

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



Hi
