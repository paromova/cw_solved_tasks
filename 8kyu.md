[Remove First and Last Character Part Two](https://www.codewars.com/kata/570597e258b58f6edc00230d)
```javascript
function array(arr){
  const newArr = arr.split(",");
  return newArr.length<3 ? null : newArr.slice(1, newArr.length-1).toString().replace(/,/gi," ");
}
```
[Reversed Strings](https://www.codewars.com/kata/5168bb5dfe9a00b126000018)
```javascript
function solution(str){
  let reverse = [];
  for(let i = 0; i<str.length; i++){
  reverse.unshift(str[i]);
  }
  return reverse.join("");
}
```
[Is it a palindrome?](https://www.codewars.com/kata/57a1fd2ce298a731b20006a4)
```javascript
function isPalindrome(x) {
let s = x.split('').reverse().join("").toLowerCase();
return s == x.toLowerCase();

//   let s = "";
//   for(let i = x.length -1; i>=0; i--){
//   s += x[i];
//   }
//   return s.toLowerCase() == x.toLowerCase();
}
```
[The Wide-Mouthed frog!](https://www.codewars.com/kata/57ec8bd8f670e9a47a000f89/train/javascript)
```javascript
function mouthSize(animal) {
  return animal.toLowerCase() == 'alligator' ? 'small' : 'wide';
}
```
[Do I get a bonus?](https://www.codewars.com/kata/56f6ad906b88de513f000d96)
```javascript
function bonusTime(salary, bonus) {
if (bonus){
return ("\u00A3" + (salary * 10));
} else {
return ("\u00A3" + salary);
}
}

bonusTime(10000, true);
bonusTime(1919, false);
```
[5 without numbers !!](https://www.codewars.com/kata/59441520102eaa25260000bf)
```javascript
function unusualFive() {
let array = ["", "", "", "", ""];
return array.length;
}
```
[Keep up the hoop](https://www.codewars.com/kata/55cb632c1a5d7b3ad0000145)
```javascript
function hoopCount (n) {
if(n>=10){
return "Great, now move on to tricks";
}else{
return "Keep at it until you get it";
}
}
```
[Sort and Star](https://www.codewars.com/kata/57cfdf34902f6ba3d300001e)
```javascript
function twoSort(s) {
const sortedArray = s.sort((a,b) => (a > b ? 1 : -1));
let first = sortedArray[0];
const newArray = [];
for(let i = 0; i< first.length; i++){
x = first[i] + "***";
newArray.push(x);
}
return newArray.join("").slice(0,-3);
}
```
[Draw stairs](https://www.codewars.com/kata/5b4e779c578c6a898e0005c5)
```javascript
function drawStairs(n) {
 let step = 'I';
 for(let i = 1; i<n;i++){
 step += "\n" + " ".repeat(i) + "I";
 }
 return step;
}

```