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
