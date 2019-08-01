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


* nothing

* https://www.codewars.com/kata/576bb71bbbcf0951d5000044/discuss/javascript

```JavaScript

function countPositivesSumNegatives(input) {
    if (!input || !input.length) return [];
    let a = 0, b = 0;
    input.forEach(el => {
     if (el > 0) {
     a++;
    } else {
      b += el;
    }
  });
   return [a, b];
   }

https://www.codewars.com/kata/lombok-encapsulation/train/java

```Java
 
public class EncapsulationDemo {
    private int number;
    private String stringValue;
    private Object anObject;

    public int getNumber() {
        return number;
    }

    public void setNumber(int number) {
        this.number = number;
    }

    public String getStringValue() {
        return stringValue;
    }

    public void setStringValue(String stringValue) {
        this.stringValue = stringValue;
    }

    public Object getAnObject() {
        return anObject;
    }

    public void setAnObject(Object anObject) {
        this.anObject = anObject;
    }

    public EncapsulationDemo() {
    }

    public EncapsulationDemo(int number, String stringValue, Object anObject) {
        this.number = number;
        this.stringValue = stringValue;
        this.anObject = anObject;
    }
}
