# cw_solved_tasks
[8 kyu](8kyu.md)
```javascript
[Calculate average](https://www.codewars.com/kata/57a2013acf1fa5bfc4000921)
function find_average(array) {
 let sum = 0;
 for(let i = 0; i< array.length; i++){
 sum += array[i];
 }
  return sum /  array.length;
}
```
[Area of a Square](https://www.codewars.com/kata/5748838ce2fab90b86001b1a)
```javascript
function squareArea(A){
  return Math.round((2*A/Math.PI)**2*100)/100;
}
```
[Is n divisible by x and y?](https://www.codewars.com/kata/5545f109004975ea66000086)
```javascript
function isDivisible(n, x, y) {
  return n % x === 0 && n % y === 0;
}
```