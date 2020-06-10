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
[I love you, a little , a lot, passionately ... not at all](https://www.codewars.com/kata/57f24e6a18e9fad8eb000296)
```javascript
function howMuchILoveYou(nbPetals) {
  const array = [ "I love you", "a little", "a lot", "passionately", "madly", "not at all"]
if (nbPetals % array.length == 0){
return array[array.length - 1];
}
return array[(nbPetals % array.length) -1];
}
```
[For Twins: 2. Math operations](https://www.codewars.com/kata/59c287b16bddd291c700009a)
```javascript
function iceBrickVolume(radius, bottleLength, rimLength) {
 return  2 * radius  ** 2 * (bottleLength - rimLength );
}
```
[Third Angle of a Triangle](https://www.codewars.com/kata/5a023c426975981341000014)
```javascript
function otherAngle(a, b) {
  return 180 - a - b;
}
```
[Super Duper Easy]()https://www.codewars.com/kata/55a5bfaa756cfede78000026
```javascript
function problem(x){
  return (typeof(x) == "string" ? 'Error' : (x *50 + 6));
  }
```
[Type of sum](https://www.codewars.com/kata/5a2e9ae2b6cfd7692a0000ba)
```javascript
function typeOfSum(a, b) {
return typeof (a+b);
}
```
[Convert a Number to a String!](https://www.codewars.com/kata/5265326f5fda8eb1160004c8)
```javascript
function numberToString(num) {
 return String (num);
}
```
[Number toString](https://www.codewars.com/kata/53934feec44762736c00044b)
```javascript
var a = "123".toString();
```
[Convert a Boolean to a String](https://www.codewars.com/kata/551b4501ac0447318f0009cd)
```javascript
function booleanToString(b){
return (b===true ? "true" : "false");
}
```
[Sum The Strings](https://www.codewars.com/kata/5966e33c4e686b508700002d)
```javascript
function sumStr(a,b) {
  return (Number(a)+ Number(b)) + "";
}
```
[Convert a String to a Number!](https://www.codewars.com/kata/544675c6f971f7399a000e79)
```javascript
var stringToNumber = function(str){
  return +str;
}
```
[Formatting decimal places #0](https://www.codewars.com/kata/5641a03210e973055a00000d)
```javascript
function twoDecimalPlaces(n) {
return +n.toFixed(2);
}
```
[Count Odd Numbers below n](https://www.codewars.com/kata/59342039eb450e39970000a6)
```javascript
function oddCount(n){
  return(n%2 === 0 ? n/2 :(n-1)/2);
}
```
[Area of a Square](https://www.codewars.com/kata/5748838ce2fab90b86001b1a)
```javascript
function squareArea(A){
  return Math.round((2*A/Math.PI)**2*100)/100;
}

```
[Keep Hydrated!](https://www.codewars.com/kata/582cb0224e56e068d800003c)
```javascript
function litres(time) {
  return Math.floor(time * 0.5);
}
```
[Chuck Norris VII - True or False? (Beginner)](https://www.codewars.com/kata/570669d8cb7293a2d1001473)
```javascript
function ifChuckSaysSo(){
return 0!=0;
}

```
[Simple Comparison?](https://www.codewars.com/kata/57f6ecdfcca6e045d2001207)
```javascript
function add(a, b){
  return a ==b ? true : false;
}
```
[Is he gonna survive?](https://www.codewars.com/kata/59ca8246d751df55cc00014c)
```javascript
function hero(bullets, dragons){
return ((bullets / 2) >= dragons ? true : false); 
}
```
[Even or Odd](https://www.codewars.com/kata/53da3dbb4a5168369a0000fe)
```javascript
function even_or_odd(number) {
return (number % 2 === 0) ? "Even" : "Odd";
}
```
[Determine offspring sex based on genes XX and XY chromosomes](https://www.codewars.com/kata/56530b444e831334c0000020)
```javascript
function chromosomeCheck(sperm) {
  if(sperm == "XX"){
  return "Congratulations! You're going to have a daughter."}
  else if (sperm == "XY"){ 
  return "Congratulations! You're going to have a son.";}
}
```
[What's the real floor?](https://www.codewars.com/kata/574b3b1599d8f897470018f6 )
```javascript
function getRealFloor(n) {
if (n >= 1 && n < 13) {
return (n-1);
} else if (n>=13){
return (n-2);
} else if (n ===0){
return n;
} else if (n<0){
return n;
}
}
```
[Calculate BMI](https://www.codewars.com/kata/57a429e253ba3381850000fb)
```javascript
function bmi(weight, height) {
let bmi = weight/height**2;
  if (bmi <= 18.5){
  return "Underweight";
  } else if(bmi > 18.5 && bmi <= 25.0){
  return "Normal";
  } else if (bmi > 25.0 && bmi <=30.0){
  return "Overweight";
  } else if (bmi > 30) {
  return "Obese";
  }
  
}
```
[Calculate BMI](https://www.codewars.com/kata/57a429e253ba3381850000fb)
```javascript
function bmi(weight, height) {
let bmi = weight/height**2;
  if (bmi <= 18.5){
  return "Underweight";
  } else if(bmi > 18.5 && bmi <= 25.0){
  return "Normal";
  } else if (bmi > 25.0 && bmi <=30.0){
  return "Overweight";
  } else if (bmi > 30) {
  return "Obese";
  }
  
}
```
[Alan Partridge II - Apple Turnover](https://www.codewars.com/kata/580a094553bd9ec5d800007d)
```javascript
function apple(x){
return (x**2 > 1000) ? "It's hotter than the sun!!" : "Help yourself to a honeycomb Yorkie for the glovebox.";
}
```
[Simple multiplication](https://www.codewars.com/kata/583710ccaa6717322c000105)
```javascript
function simpleMultiplication(number) {
if (number % 2 ==0){
return number * 8;
} else {
return number * 9;
}
}
```
[Sleigh Authentication](https://www.codewars.com/kata/52adc142b2651f25a8000643)
```javascript
function Sleigh() {}

Sleigh.prototype.authenticate = function(name, password) {
if (name == "Santa Claus" && password === "Ho Ho Ho!"){
return true;
} else return false;
};
```
[Is n divisible by x and y?](https://www.codewars.com/kata/5545f109004975ea66000086)
```javascript
function isDivisible(n, x, y) {
  return n % x === 0 && n % y === 0;
}
```
[Student's Final Grade](https://www.codewars.com/kata/5ad0d8356165e63c140014d4)
```javascript
function finalGrade (exam, projects) {
  if (exam > 90 || projects > 10) return 100;
  else if (exam > 75 && projects >=5) return 90;
  else if (exam > 50 && projects >=2) return 75;
  else return 0;
}
```