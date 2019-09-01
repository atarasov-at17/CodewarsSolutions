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

Check check how is it work
++++++++++++++++++++++++++

Javascript

const s = [45, 87, 53, 95, -1, 456, 0];


  const f =[];
  let min = s[0];
  let max = s[0];
  let minIndex = 0;
  
  for(let i = 1; i < s.length; i++){
    if(s[i] < min) {
      min = s[i];
      minIndex = i;
    }
    
    if(s[i] > max) max = s[i];
 }
 
//nsole.log(min, max, minIndex);

for(let i = 0; i < s.length; i++){
f.push(s[i]);
}

f.push(max + 1);

for(let i = minIndex; i < s.length; i++) {
f.push(s[i]);
}

console.log(f);

```Javascript

Skip welcome & menu and move to editor
Textarea editor mode
JS Bin features

    Getting started
    Keyboard Shortcuts
    Exporting/importing gist

Pro features

    Private bins
    Dropbox backup
    Vanity URLs

Upgrade to pro now
Blog

    The Return and The Refactor

Help

    Versions: Processors & core libraries
    Ajax request to bins

//  let arr = [10, 2, -4, 10, 6, -4, 98];

​

// // // [10, 2, -4, 6, 98];

// // function unique (arr){

// //   let a = []; 

// //   for (let i = 0; i < arr.length; i++){

    

// //    //for (let j = 0; j < a.length; j++){

// //     //if (a[j === arr[i]) return true;

  

// //     if (!a.includes(arr [i])) {

// //       a.push(arr[i]);

// //     }

// //   }

// //   return a;

// // }

// // console.log(unique(arr));

​

​

// function unique2 (arr){

//   const a = {};

//   const f = [];

  

// //   10: true,

// //    2 : tru,

// //       '-4': true,

// //         6: true,

// //           98: true

          

// //O(1), O(n)

  

//   for (let i = 0; i < arr.length; i++){

//     if (!a[arr[i]]) {

//       f.push(arr[i]);

//       a[arr[i]] = true;

      

//       console.log(a);

//     }

//   }

//   return f;

// }

​

======================

  

 let arr = [10, 2, 4, 10, 6, 4, 8]

  

  function unique3(arr){

    let sort = Array(20).fill(0);

    let result = [];

    

    for(let i = 0; i < arr.length; i++){

      if (sort[arr[i]] === 0) {

        result.push(arr[i]);

        sort[arr[i]]++;

      }

    }

  return result;
}
console.log(unique2(arr));

``` hello
Check check


Проверка работы

system don't work

```https://www.codewars.com/kata/find-the-difference-in-age-between-oldest-and-youngest-family-members/train/javascript
   
   function differenceInAges(ages){
    let min = ages[0],
        max = ages[0];
    for (let i = 0; i <ages.length; i++){
      if (ages[i] < min) min = ages[i];
      if (ages[i] > max) max = ages[i];
    }
    return [min, max, max - min];
   }

*javascript

```Area of a Square
   https://www.codewars.com/kata/area-of-a-square/train/javascript
   
   function squareArea(A){
     return +(4 * Math.pow(A, 2)/Math.pow(Math.PI, 2)).toFixed(2);
   }

* Javascript

```https://www.codewars.com/kata/nba-full-48-minutes-average/train/javascript
   function pointsPer48(ppg, mpg) {
    if (mpg === 0) return 0;
    return +(ppg * 48 / mpg).toFixed(1);
   }

